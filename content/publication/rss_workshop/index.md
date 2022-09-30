---
title: 'Framework and Software for Real-Time Multi-Contact Model Predictive Control'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Adam Wei
  - Michael Posa

# Author notes (optional)
author_notes:
  - ''
  - ''

date: '2022-01-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: ''

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *RSS Workshop*
publication_short: In *RSS Workshop*

abstract: Our recent work on consensus complementarity control (C3) proposes a model predictive control algorithm for hybrid systems that make and break contact with their environment. C3 is based on the alternating direction method of multipliers (ADMM), that is capable of high-speed reasoning over potential contact events. Via a consensus formulation, the approach enables parallelization of the contact scheduling problem and is able to run at real-time rates. In this abstract, we build upon this with software improvements that increase the run-time by approximately 2 times over our previous implementation (achieving 25 Hz rate for a problem with 19 states, 12 complementarity variables and 0.5 seconds prediction horizon). Additionally we integrated our software with Drake [4]. The software parses models in URDF format into a non-smooth linear complementarity system and generates a controller that solves the optimal control problem. In addition to our previous work, we also validated our approach on a 3D manipulation example.

# Summary. An optional shortened abstract.
summary:

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name:
#   url: 

url_pdf: 'https://github.com/AlpAydinoglu/starter-hugo-academic/blob/main/static/uploads/Framework_and_Software_for_Real_Time_Multi_Contact_Model_Predictive_Control.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
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
