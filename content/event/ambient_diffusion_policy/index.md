---
title: Ambient Diffusion Policy

event: RSS 2026 Workshops
event_url: 

location: Sydney, Australia

abstract: 'We propose Ambient Diffusion Policy, a simple and principled method for imitation learning from suboptimal data in robotics. High-quality, task-specific robot data is expensive and time-consuming to collect, while suboptimal datasets with lower-quality or out-of-distribution demonstrations are abundant. Existing methods that co-train on both data sources in robotics often fail to separate the meaningful and the harmful features in the suboptimal samples. In contrast, our method extracts only the useful features by introducing a new axis to co-training in robotics: noise-dependent data usage. Ambient Diffusion Policy restricts the contribution of suboptimal data during training to only the high and low diffusion times. To rigorously justify our approach, we first observe that robot action data exhibits a spectral power law. This induces two important properties on the optimal Diffusion Policy that we exploit: a global-to-local hierarchy and locality. We theoretically formalize this discussion using a simplified model. Our experiments validate Ambient Diffusion Policy on four types of suboptimal action data (noisy trajectories, sim-to-real gap, task mismatch, and large-scale data mixtures) across six tasks. The results show that it effectively learns from arbitrary sources of suboptimal data. Notably, it outperforms existing co-training baselines by up to 33% when scaled to Open X-Embodiment - a large dataset with heterogeneous data quality and unstructured distribution shifts. Overall, Ambient Diffusion Policy increases the utility of suboptimal demonstrations and expands the set of usable data sources in robotics.'

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2026-07-01T00:00:00Z' # TODO: set exact date of the most recent (RSS 2026) talk
# date_end: ''
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2017-01-01T00:00:00Z'

authors: [admin]
tags: []

# Is this a featured talk? (true/false)
featured: false

image:
  caption: 'Slides are available [**here**](https://slides.com/weiadam/ambient-diffusion-policy-imitation-learning-from-suboptimal-data-in-robotics).'
  focal_point: Right

url_code: ''
url_pdf: ''
url_slides: 'https://slides.com/weiadam/ambient-diffusion-policy-imitation-learning-from-suboptimal-data-in-robotics'
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
  - 'content/selected_publications/ambient_diffusion_policy/index.md'
---

Presented at:
- **Walden Robotics** — Cambridge, MA · June 2026
- **[RSS 2026 Data-Centric Workshop](https://rss-workshop-2026.github.io/)** — Sydney, Australia · July 2026
- **[RSS 2026 It's The Demos](https://its-the-demos.github.io/)** — Sydney, Australia · July 2026
