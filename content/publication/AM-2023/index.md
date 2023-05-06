---
title: 'Fill in the Blank: Transferrable Deep Learning Approaches to Recover Missing Physical Field Information'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
 - admin 
 - Markus J. Buehler

# Author notes (optional)
# author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2023-03-19'
doi: 'https://doi.org/10.1002/adma.202301449'

# Schedule page publish date (NOT publication's date).
# publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: In *Advanced Materials*
publication_short: In *Adv. Mater.*

abstract: Solving materials engineering tasks is often hindered by limited information, such as in inverse problems with only boundary data information or design tasks with a simple objective but a vast search space. To address these challenges, multiple deep learning (DL) architectures are leveraged to predict missing mechanical information given limited known data in part of the domain, and further characterize the composite geometries from the recovered mechanical fields for 2D and 3D complex microstructures. In 2D, a conditional generative adversarial network (GAN) is utilized to complete partially masked field maps and predict the composite geometry with convolutional models with great accuracy and generality by making precise predictions on field data with mixed stress/strain components, hierarchical geometries, distinct materials properties and various types of microstructures including ill-posed inverse problems. In 3D, a Transformer-based architecture is implemented to predict complete 3D mechanical fields from input field snapshots. The model manifests excellent performance regardless of microstructural complexity and recovers the entire bulk field even from a single surface field image, allowing internal structural characterization from only boundary measurements. The whole frameworks provide efficient ways for analysis and design with incomplete information and allow the direct inverse translation from properties back to materials structures.
# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
 - name: Paper Link
   url: https://onlinelibrary.wiley.com/doi/full/10.1002/adma.202301449#
 - name: Code
   url: https://github.com/lamm-mit/FieldCompleter

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

