
---
title: DL for Crystalline Solids 
summary: GNN-based approach to predict atomic properties (e.g. atomic stress/energy) from structural defects distribution for crystalline solids. 
tags:
  - Atomic


# Optional external URL for project (replaces project detail page).
# external_link: ''

image:
  caption: ''
  focal_point: Smart

links:
  - name: Code
    url: https://github.com/lamm-mit/atomic2field
  - name: Related paper (Npj. Comput. Mater., 2022)
    url: https://www.nature.com/articles/s41524-022-00879-4
url_code: 'https://github.com/lamm-mit/atomic2field'
url_pdf: ''
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
#   slides: example
---

Structural defects are abundant in solids, and vital to the macroscopic materials properties. However, a defect-property linkage typically requires significant efforts from experiments or simulations, and often contains limited information due to the breadth of nanoscopic design space. Here we report a graph neural network (GNN)-based approach to achieve direct translation between mesoscale crystalline structures and atom-level properties, emphasizing the effects of structural defects. Our end-to-end method offers great performance and generality in predicting both atomic stress and potential energy of multiple systems with different defects. Furthermore, the approach also precisely captures derivative properties which strictly observe physical laws and reproduces evolution of properties with varying boundary conditions. By incorporating a genetic algorithm, we then design de novo atomic structures with optimum global properties and target local patterns. The method would significantly enhance the efficiency of evaluating atomic behaviors given structural imperfections and accelerates the design process at the meso-level.
