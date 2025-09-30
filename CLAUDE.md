# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Overview

This is an academic personal website built with Hugo and the Wowchemy Academic theme (v5.6.0). The site showcases publications, talks/events, and professional profile information for Adam Wei, a robotics PhD student at MIT.

## Development Commands

### Building and Serving
- **Local development server**: `hugo server` (live reload enabled)
- **Build production site**: `hugo --gc --minify`
- **Build with future-dated content**: `hugo --gc --minify --buildFuture`

The site requires Hugo version 0.97.3 or compatible (specified in netlify.toml).

### Deployment
- The site is configured for Netlify deployment
- Production builds automatically from the `main` branch
- Deploy previews build with `hugo --gc --minify --buildFuture -b $DEPLOY_PRIME_URL`

## Content Architecture

### Publications (`content/publication/`)
Each publication is a separate directory containing:
- `index.md`: Front matter with metadata (title, authors, abstract, dates, publication type, URLs)
- `cite.bib`: BibTeX citation
- `featured.jpg/png`: Optional featured image

Publication types follow the Academic theme convention:
- 0 = Uncategorized
- 1 = Conference paper
- 2 = Journal article
- 3 = Preprint / Working Paper
- 4 = Report
- 5 = Book
- 6 = Book section
- 7 = Thesis
- 8 = Patent

### Talks/Events (`content/event/`)
Each talk/event is a separate directory with `index.md` containing:
- Event title, URL, location, and abstract
- Date and time information (with optional end time)
- Links to slides, code, PDF, video
- Optional associated projects

### Author Profile (`content/authors/admin/`)
The `_index.md` file contains all profile information including:
- Name, role, organization
- Bio and interests
- Education history
- Social media links and contact info

### Home Page Widgets (`content/home/`)
Page sections are configured as individual markdown files:
- `about.md`: Biography widget
- `publications.md`: Publications list
- `talks.md`: Talks/events list
- `contact.md`: Contact information
- Each widget has `weight` parameter to control ordering

## Configuration Structure

### Main Config (`config/_default/config.yaml`)
- Site title, baseURL, language settings
- Hugo modules (Wowchemy theme and plugins)
- Permalinks structure (talks use `/talk/:slug/`)
- Taxonomies: tags, categories, publication_types, authors
- Output formats and imaging settings

### Site Parameters (`config/_default/params.yaml`)
- Theme appearance (currently using "minimal" theme)
- SEO and analytics settings
- Navigation bar configuration
- Footer and copyright
- Feature toggles (math rendering, syntax highlighting, search provider)

## Content Management Workflow

### Adding a New Publication
1. Create directory: `content/publication/[short-name]/`
2. Add `index.md` with complete front matter
3. Add `cite.bib` with BibTeX entry
4. Optionally add `featured.jpg/png` for images
5. Set appropriate `publication_types` value
6. Use `admin` in authors list to link to the main profile

### Adding a New Talk
1. Create directory: `content/event/[event-name]/`
2. Add `index.md` with event details
3. Include event URL, location, abstract
4. Set proper date (controls display order)
5. Add slide/video URLs if available

### Updating Profile Information
Edit `content/authors/admin/_index.md` to update:
- Current role, bio, interests
- Education and affiliations
- Social media links

## Theme and Styling

The site uses the Wowchemy Academic theme with:
- Minimal theme variant for both day/night modes
- Large font size (L)
- Circle avatar shape
- Custom permalinks for events/talks

## Important Notes

- Hugo version 0.97.3 is specified in netlify.toml for consistent builds
- The theme is imported as a Hugo module (not a Git submodule)
- Content can include LaTeX math, code blocks, and rich markdown
- Future-dated content is excluded from production builds unless `--buildFuture` flag is used
- The `admin` author username links publications/talks to the main profile
