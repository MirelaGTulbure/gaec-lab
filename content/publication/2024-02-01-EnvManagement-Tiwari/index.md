---
title: "Automated in-season rice crop mapping using Sentinel time-series data and Google Earth Engine: A case study in climate-risk prone Bangladesh"
authors:
- varuntiwari
- admin
- juliocaineta
- molliegaines
- viniperin
- Mustafa Kamal
- Timothy J. Krupnik
- Md Abdullah Aziz
- AFM Tariqul Islam

author_notes:
- "Corresponding author"

date: "2024-02-01T00:00:00Z"
doi: "https://doi.org/10.1016/j.jenvman.2023.119615"

# Schedule page publish date (NOT publication's date).
publishDate: "2023-12-21T00:00:00Z"

# Indicate if this is related to GAEC by typing "Lab Related" if not, leave blank
categories: "Lab Related" 

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Journal of Environmental Management"
publication_short: ""

abstract: High-resolution mapping of rice fields is crucial for understanding and managing rice cultivation in countries like Bangladesh, particularly in the face of climate change. Rice is a vital crop, cultivated in small scale farms that contributes significantly to the economy and food security in Bangladesh. Accurate mapping can facilitate improved rice production, the development of sustainable agricultural management policies, and formulation of strategies for adapting to climatic risks. 

To address the need for timely and accurate rice mapping, we developed a framework specifically designed for the diverse environmental conditions in Bangladesh. We utilized Sentinel-1 and Sentinel-2 time-series data to identify transplantation and peak seasons and employed the multi-Otsu automatic thresholding approach to map rice during the peak season (April–May). We also compared the performance of a random forest (RF) classifier with the multi-Otsu approach using two different data combinations; D1, which utilizes data from the transplantation and peak seasons (D1 RF) and D2, which utilizes data from the transplantation to the harvest seasons (D2 RF).

Our results demonstrated that the multi-Otsu approach achieved an overall classification accuracy (OCA) ranging from 61.18% to 94.43% across all crop zones. The D2 RF showed the highest mean OCA (92.15%) among the fourteen crop zones, followed by D1 RF (89.47%) and multi-Otsu (85.27%). Although the multi-Otsu approach had relatively lower OCA, it proved effective in accurately mapping rice areas prior to harvest, eliminating the need for training samples that can be challenging to obtain during the growing season.

In-season rice area maps generated through this framework are crucial for timely decision-making regarding adaptive management in response to climatic stresses and forecasting area-wide productivity. The scalability of our framework across space and time makes it particularly suitable for addressing field data scarcity challenges in countries like Bangladesh and offers the potential for future operationalization.

# Summary. An optional shortened abstract.
summary: We developed a novel framework to map boro rice at peak season using Sentinel images. These Boro rice maps in Bangladesh showed high classification accuracy (mean of 87.90%). There was no requirement of sample data collection for training the classification model. Multi-Otsu effectively maps rice in low-data areas, outperforming other ML methods and provides stakeholders rice area statistics to support food security management.

tags:
- Synthetic Aperature Radar (SAR)
- Random forest
- Multi-otsu
- Boro rice
- Flooding
- In-season maps

featured: false

# links:
# - name: ""
#   url: ""
url_pdf: 'https://www.sciencedirect.com/science/article/pii/S0301479723024039'
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
  caption: 'Graphical abstract'
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

