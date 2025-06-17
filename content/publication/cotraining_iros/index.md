---
title: 'Empirical Analysis of Sim-and-Real Cotraining Of Diffusion Policies For Planar Pushing from Pixels'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Abhinav Agarwal
  - Boyuan Chen
  - Rohan Bosworth
  - Nicholas Pfaff
  - Russ Tedrake

# Author notes (optional)
author_notes:
  - ''
  - ''

date: '2025-03-28T00:00:00Z'

# Schedule page publish date (NOT publication's date).
publishDate: ''

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['3']

# Publication name and optional abbreviated publication name.
publication: IROS 2025
publication_short: IROS 2025

abstract: In imitation learning for robotics, cotraining with demonstration data generated both in simulation and on real hardware has emerged as a powerful recipe to overcome the sim2real gap. This work seeks to elucidate basic principles of this sim-and-real cotraining to help inform simulation design, sim-and-real dataset creation, and policy training. Focusing narrowly on the canonical task of planar pushing from camera inputs enabled us to be thorough in our study. These experiments confirm that cotraining with simulated data can dramatically improve performance in real, especially when real data is limited. Performance gains scale with simulated data, but eventually plateau; real-world data increases this performance ceiling. The results also suggest that reducing the domain gap in physics may be more important than visual fidelity for non-prehensile manipulation tasks. Perhaps surprisingly, having some visual domain gap actually helps the cotrained policy -- binary probes reveal that high-performing policies learn to distinguish simulated domains from real. We conclude by investigating this nuance and mechanisms that facilitate positive transfer between sim-and-real. In total, our experiments span over 40 real-world policies (evaluated on 800+ trials) and 200 simulated policies (evaluated on 40,000+ trials).

summary:

image:
  focal_point: Right

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name:
#   url: 

url_pdf: 'https://arxiv.org/abs/2503.22634'
url_code: 'https://github.com/orgs/sim-and-real-cotraining/repositories'
url_dataset: ''
url_poster: ''
url_project: 'https://sim-and-real-cotraining.github.io/'
url_slides: 'https://slides.com/weiadam/amazon-coro-symposium-2025'
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: 'Smart'
  preview_only: true

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
