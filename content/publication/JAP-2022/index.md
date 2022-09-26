---
title: 'Rapid mechanical property prediction and de novo design of three-dimensional spider webs through graph and GraphPerceiver neural networks'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Wei Lu
  - admin
  - Markus J. Buehler

# Author notes (optional)
# author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2022-08-17'
doi: ''

# Schedule page publish date (NOT publication's date).
# publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: In *Journal of Applied Physics*
publication_short: In *JAP*

abstract: Spider webs feature advanced structural performance due to the evolutionary success of over more than 3 × 109 years, including lightweight design and exceptional mechanical properties. Spider webs are appealing for bio-inspired design since web designs serve multiple functions including mechanical protection and prey catching. However, high computational cost and limited quantified web properties render extensive spider web studies challenging in part due to the high structural complexity and randomness of fiber arrangements in 3D webs. Here, we report a computational method to relate spider web graph microstructures to effective mechanical properties, focusing on strength and toughness, and upscaling from the microscopic to the mesoscale level. The new computational framework uses deep neural networks, trained on graph-structured Cyrtophora citricola spider web mechanical data, in order to capture complex cross-scale structural relationships. Three different models are developed and compared. First, two Graph Neural Network (GNN) models, a Graph Convolutional Network, and a Principal Neighborhood Aggregation method. Second, a GraphPerceiver transformer model that is fed similar input data as provided to the GNN approach but within a natural language modeling context using self-attention mechanisms. The GraphPerceiver model can achieve similar performance as the GNN model, offering added flexibility for building deep learning models of diverse hierarchical biological materials. As an application of the model, we propose a computational optimization tool for synthetic web design that is used to generate synthetic, de novo spider web architectures. Finally, multi-objective optimization enables us to discover web structures that meet specific mechanical properties as design objectives.
# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
 - name: Paper Link
   url: https://aip.scitation.org/doi/figure/10.1063/5.0097589

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

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
