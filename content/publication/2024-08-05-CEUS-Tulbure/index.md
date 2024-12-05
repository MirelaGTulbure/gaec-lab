---
title: "Creating spatially complete zoning maps using machine learning"
authors:
- Margaret A. Lawrimore
- Georgina M. Sanchez
- Cayla Cothron
- admin
- Todd K. BenDor
- Ross K. Meentemeyer

author_notes:
- "Author"

date: "2024-07-31T00:00:00Z"
doi: "https://doi.org/10.1016/j.compenvurbsys.2024.102157"

# Schedule page publish date (NOT publication's date).
publishDate: "2024-12-05T16:50:00Z"

# Indicate if this is related to GAEC by typing "Lab Related" if not, leave blank
categories: "Lab Related" 

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Computers, Environment and Urban Systems"
publication_short: ""

abstract: Zoning regulates land use and intensity of urban development at the county and municipal level in the United States, promoting economic growth, community health, and environmental preservation. However, limited availability of zoning data at scale hinders regional assessments of regulations and coordinated resilience planning efforts. In this study, we developed an open-source, replicable, and transferable framework to predict spatially complete zoning in areas where zoning information is publicly unavailable. We applied a Hierarchical Random Forest algorithm to predict multilevel zoning districts, including three core districts (residential, non-residential, mixed use) and 13 sub-districts. To mimic real-world data accessibility challenges, we evaluated two models, one filling gaps within a county (within-county) and the other extrapolating for counties with no available data (between-county). We tested our models statewide in North Carolina (NC), USA, and developed the State's first comprehensive zoning map. We found strong predictive performance for our within-county model (∼99% accuracy; macro averaged F1 score of ∼0.97) irrespective of district breakdown (i.e., core and sub). However, our between-county model performance was lower and varied depending on the training counties sampled and the district breakdown considered (19–90% accuracy; macro averaged F1 score of 0.105–0.451). Our framework provides spatially complete zoning maps for previously inaccessible locations, enabling researchers and planners to conduct large-scale comprehensive zoning assessments.

# Summary. An optional shortened abstract.
summary: []

tags:
- Land use policy
- Land use regulation
- Machine learning
- Random forest
- Urban planning
- Zoning

featured: false

# links:
# - name: ""
#   url: ""
url_pdf: 'https://www-sciencedirect-com.prox.lib.ncsu.edu/science/article/pii/S0198971524000863/pdfft?md5=7daed9abb061f1175b558db182628fc0&pid=1-s2.0-S0198971524000863-main.pdf'
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
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

