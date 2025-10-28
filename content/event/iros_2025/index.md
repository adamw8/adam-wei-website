---
title: Empirical Analysis of Sim-and-Real Cotraining For Diffusion Policies

event: IROS 2025
event_url: https://www.iros25.org/

location: Hangzhou, China

abstract: 'In imitation learning for robotics, cotraining with demonstration data generated both in simulation and on real hardware has emerged as a powerful recipe to overcome the sim2real gap and scale up data collection. I will present a set of thorough and focused experiments that elucidate basic principles of this sim-and-real cotraining to inform simulation design, sim-and-real dataset creation, and policy training. These experiments confirm that cotraining with simulated data can dramatically improve performance in the real world, especially when real data is limited. I will also discuss how different distribution shifts between the real and synthetic datasets affect policy performance and inform simulator design for data generation. Perhaps surprisingly, having some visual domain gap actually helps the cotrained policy. I will conclude by discussing this nuance and other mechanisms that help facilitate positive transfer between sim-and-real. For a more detailed set of slides with animations, please see my talk from the Amazon CoRo 2025 Symposium'

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2025-10-21T16:45:00Z'
# date_end: '2030-06-01T15:00:00Z'
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2017-01-01T00:00:00Z'

authors: [admin]
tags: []

# Is this a featured talk? (true/false)
featured: false

image:
  caption: 'Slides are available [**here**](https://adamwei.com/uploads/cotraining_iros_2025_slides.pdf).'
  focal_point: Right

url_code: ''
url_pdf: ''
url_slides: 'https://adamwei.com/uploads/cotraining_iros_2025_slides.pdf'
url_video: ''

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects:
  - 'context/publication/cotraining_iros/index.md'
---