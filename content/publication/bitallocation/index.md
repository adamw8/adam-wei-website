---
title: 'BitAllocation: A Resource Allocation Algorithm For Fixed-Point Quantization'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin

# Author notes (optional)
author_notes:
  - ''
  - ''

date: '2021-01-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: ''

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['0']

# Publication name and optional abbreviated publication name.
publication: 
publication_short: 

abstract: The growing size and computational complexity of state-of-the-art deep convolutional networks (DCNs) have greatly increased the memory, time, and power requirements of inference in many computer vision applications. Fixed-point quantization is an effective method that can alleviate some of these issues, but comes at the cost of reduced classification accuracy. In an attempt to minimize this accuracy degradation, we developed BitAllocation, a quantization pipeline that can aggressively compress DCNs to fixed-point data types without the need for retraining. Our key insight is to formulate quantization as a variation of the discrete resource allocation problem, where a \textit{budget} of bits is to be allocated across the weights and activations in a way that minimizes the total quantization error. Although this problem is NP-hard, we develop a near linear time algorithm that solves it optimally for practical applications. Using this algorithm and no further retraining, we quantized 7 ImageNet DCNs to an average bitwidth of 5.5-6.25 bits with a 1-3\% drop in top-1 accuracy. This corresponded to a 5.51x and 27.5x reduction in model size and cost of multiplications respectively. Although this paper presents an application in machine learning quantization, our algorithm can be used in other fields that involve resource allocation, such as economics, project management, and computer systems.

# Summary. An optional shortened abstract.
summary:

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name:
#   url: 

url_pdf: 'https://github.com/adamw8/adam-wei-website/blob/main/static/uploads/Adam-Wei-BitAllocation.pdf'
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
