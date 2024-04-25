---
title: 'A Self-Improvable Polymer Discovery Framework Based on Conditional Generative Model'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
 - Xiangyun Lei
 - Weike Ye
 - admin 
 - Daniel Schweigert
 - Ha-Kyung Kwon
 - Arash Khajeh

# Author notes (optional)
# author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2024-02-22'
doi: 'https://arxiv.org/abs/2312.04013'

# Schedule page publish date (NOT publication's date).
# publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: In *ArXiv*
publication_short: In *ArXiv*

abstract: In this work, we introduce a polymer discovery platform designed to identify polymers with tailored properties efficiently, exemplified through the discovery of high-performance polymer electrolytes. The platform integrates three core components including a conditioned generative model, validation modules, and a feedback mechanism, creating a self-improving system for material innovation. To demonstrate the efficacy of this platform, it is used to identify polymer electrolyte materials with high ionic conductivity. A simple conditional generative model, based on the minGPT architecture, can effectively generate candidate polymers that exhibit a mean ionic conductivity that is significantly greater than those in the original training set. This approach, coupled with molecular dynamics simulations for validation and a specifically designed acquisition mechanism, allows the platform to refine its output iteratively. Notably, after the first iteration, we observed an increase in both the mean and the lower bound of the ionic conductivity of the new polymer candidates. The platform's effectiveness is underscored by the identification of 19 polymer repeating units, each displaying a computed ionic conductivity surpassing that of Polyethylene Oxide (PEO). The discovery of these polymers validates the platform's efficacy in identifying potential polymer materials. Acknowledging current limitations, future work will focus on enhancing modeling techniques, validation processes, and acquisition strategies, aiming for broader applicability in polymer science and machine learning.
# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
 - name: Paper Link
   url: https://arxiv.org/abs/2312.04013

url_pdf: ''
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
  caption: ''
  focal_point: Smart
  # preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#   slides: example
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

