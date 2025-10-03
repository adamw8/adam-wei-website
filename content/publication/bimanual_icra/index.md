---
title: 'How Well do Diffusion Policies Learn Kinematic Constraint Manifolds?'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Lexi Foland
  - Thomas Cohn
  - admin
  - Nicholas Pfaff
  - Boyuan Chen
  - Russ Tedrake

# Author notes (optional)
author_notes:
  - ''
  - ''

date: '2025-09-15T00:00:00Z' # TODO: update

# Schedule page publish date (NOT publication's date).
publishDate: ''

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['3'] # TODO: update

# Publication name and optional abbreviated publication name.
publication: Under Review ICRA 2026
publication_short: Under Review ICRA 2026

abstract: "Diffusion policies have shown impressive results in robot imitation learning, even for tasks that require satisfaction of kinematic equality constraints. However, task performance alone is not a reliable indicator of the policy's ability to precisely learn constraints in the training data. To investigate, we analyze how well diffusion policies discover these manifolds with a case study on a bimanual pick-and-place task that encourages fulfillment of a kinematic constraint for success. We study how three factors affect trained policies: dataset size, dataset quality, and manifold curvature. Our experiments show diffusion policies learn a coarse approximation of the constraint manifold with learning affected negatively by decreases in both dataset size and quality. On the other hand, the curvature of the constraint manifold showed inconclusive correlations with both constraint satisfaction and task success. A hardware evaluation verifies the applicability of our results in the real world."

summary:

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name:
#   url: 

# TODO: upate all inks
url_pdf: 'https://arxiv.org/abs/2510.01404'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: 'https://lexifol.github.io/diffusion-learns-kinematic/'
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: 'Smart'
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: ''


# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ''
---
