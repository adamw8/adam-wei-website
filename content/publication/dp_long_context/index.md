---
title: 'Training and Evaluating Diffusion Policies with Long Context Lengths'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Abhinav Agarwal
  - admin
  - Taylan Kargin
  - Michael Zeng
  - Cole Becker
  - Arif Kerem Dayı
  - Pablo Parrilo
  - Asuman Ozdaglar
  - Russ Tedrake

date: '2026-06-15T00:00:00Z'

# Schedule page publish date (NOT publication's date).
publishDate: ''

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['3']

# Publication name and optional abbreviated publication name.
publication: Preprint
publication_short: Preprint

abstract: "Imitation learning has enabled highly-dexterous robotic manipulation from RGB observations. Policies trained with these methods, however, typically condition robot actions on only a short history of observations. These policies cannot solve tasks that require memory and can get stuck repeatedly executing the same failing motions. In this work, we first benchmark policy performance as context length is incrementally increased from short to long, across a spectrum of tasks with varying local stability and memory requirements, and in multiple data regimes. To our knowledge, this is the first study to investigate context length in imitation learning at this level of detail. Our results challenge prior claims: naively scaling context length is not as brittle as advertised in literature. With an appropriate conditioning method and denoising backbone (UNet+Cross-Attention), single-task policies achieve high success rates on many tasks in the usual data regime even with naive scaling. Next, we propose a training algorithm to jointly train policies at multiple context lengths, further reducing the sample complexity of long-context learning. Finally, we apply our findings to re-evaluate some previously proposed solutions to long-context imitation learning."

summary:

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name:
#   url: 

url_pdf: 'https://arxiv.org/abs/2606.16447'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: 'https://dp-with-long-context.github.io/'
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
