---
title: 'Inconsistency of cross-validation for structure learning in Gaussian graphical models'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Wai Ming Tai
  - Mladen Kolar
  - Bryon Aragam

# Author notes (optional)
author_notes:
  # - 'Equal contribution'
  # - 'Equal contribution'

date: '2023-12-28T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-03-15T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *International Conference on Artificial Intelligence and Statistics*
publication_short: In *AISTATS*

abstract: Despite numerous years of research into the merits and trade-offs of various model selection criteria, obtaining robust results that elucidate the behavior of cross-validation remains a challenging endeavor. In this paper, we highlight the inherent limitations of cross-validation when employed to discern the structure of a Gaussian graphical model. We provide finite-sample bounds on the probability that the Lasso estimator for the neighborhood of a node within a Gaussian graphical model, optimized using a prediction oracle, misidentifies the neighborhood. Our results pertain to both undirected and directed acyclic graphs, encompassing general, sparse covariance structures. To support our theoretical findings, we conduct an empirical investigation of this inconsistency by contrasting our outcomes with other commonly used information criteria through an extensive simulation study. Given that many algorithms designed to learn the structure of graphical models require hyperparameter selection, the precise calibration of this hyperparameter is paramount for accurately estimating the inherent structure. Consequently, our observations shed light on this widely recognized practical challenge.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/abs/2312.17047'
url_code: 'https://github.com/zhao-lyu/GGM'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ''
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
#   - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---
<!-- 
{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
