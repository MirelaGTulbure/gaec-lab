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
url_pdf: 'https://pdf.sciencedirectassets.com/272592/1-s2.0-S0301479723X0022X/1-s2.0-S0301479723024039/main.pdf?X-Amz-Security-Token=IQoJb3JpZ2luX2VjEF0aCXVzLWVhc3QtMSJGMEQCIDYjQUvwhLtomFaajqIxRUeMRQYLgOWz5nQmRVRpuNbgAiAzs2UpgHTXVCAMEygz%2BWEe%2FykO9z2skQtoBTr%2FLp6Pvyq8BQj2%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAUaDDA1OTAwMzU0Njg2NSIMgIbA1GfAO9fBU4PTKpAFvm8fpS%2BvXwniKYiWnTJ3UCxjYACZdq6gYeUV8C7G8gzlgNrMlvtCb24gqlqVliKmOg6WHrA%2FDI6ojwTFJPSbldPuM%2FK13XTqunG%2ByKJj8RWloaSjzJilMh69Pjuec5Fn5%2BkbQ6VUBhxw5HfomJ%2FR3AWc9qH8DpOl8s4izKeJB0JYgihY7O470Aoe0ZrxQ4U50Da%2F8FV5JGHv8FVKJLSnAUEgaY9EsgBLRZmQVH11%2BsddnA5bLVq9erQiv7AByj8QvABYZYwbP6iiGIK1zwpfZIwlpjoGDZNSOJAGMD5JsBUpWDTTi9cBr%2F1jLMm6vqkQNRHRZl2lJCkj9ZgjS4wMTpZQFJnaNgh4OFC7K0u1IJykW97KQ1pAHY3C5b0CN8LfpK3HYQGc4aw42ZpHwWINC45YIRgB%2BG47%2FxQzEffGhgYGXr%2FuZA17sDXJfXqThOc%2FkvdCFZUs%2FA0miIfAaoteh3b8emgFBpQXymeE3r6%2FaT8ZKKc2Yaj05zqGkcKWvnHGt%2FRmrKnpyXyfONJZF%2FcgrLjC02CM6GlnXOB%2B%2BH8aaISpulm6m6ndsJrIbdYBrEOcBi%2B7p7a6eD%2FCuMWCkbZu8kUSeyvn9p%2BDyXsvXlFc65Q8mL8hb12T4LLVt26P7uhMzXgRjTonnZQM9reqVHhwGHD6QaQyGQ4orY5rTBrZcjJJT27KXTP%2FFyxAOtk3vhn4sVB1ahTYpFgqgTtOVsCe2U2GP%2Bux6nRwmP44LdDpXvo1DXg6zSVlocvbSWinL3JDI2tepNubRr6jP2JQJ5KlmLxU6hXUh%2BrNXUU%2B3NXiQUwdMmMXWq6f5Vj2lzYac5Ebbq%2FyGf5ZQ1slJol9FPLAyQL9q6wuF7oGgBcChF0ftgMwlN72rAY6sgEnQfh4%2BpY2Z0d3CvZpY2sIZ3D26IFYroaTfGiWw0WLUpy8vigAgsHDPhHr1USuXK0Kr3CHo%2B12eBmShgl4t7IEnBEzILIHUbn01zMR3s7F1bjRYaXCQRsQ%2BhSMafQ7abYTnk%2Bh1tO6Z6%2FkOrlUZPHuCkUlsA070fbeR9TdNOYLIUPpsP%2B8IN2UIWmlmr4E44Tb%2B1gt%2FNzrmGQMMCxsHFSn%2FI0N4mc0eG7R4GsQR7YVQzc4&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20240109T213427Z&X-Amz-SignedHeaders=host&X-Amz-Expires=300&X-Amz-Credential=ASIAQ3PHCVTY4PEDR3IU%2F20240109%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Signature=a8846676f9b189024ec2bbece199eff22c0f74356eb501d401407d0851b5468a&hash=bf87cbfa41e978149a05d80b8cd7843db2ffa13a3fa8ef9fad7fe043ffd8272f&host=68042c943591013ac2b2430a89b270f6af2c76d8dfd086a07176afe7c76c2c61&pii=S0301479723024039&tid=spdf-4b4f0b2b-7838-48df-b97d-64546e64c8f9&sid=6521393d500fd8493b6809d-5b1de31985c8gxrqa&type=client&tsoh=d3d3LnNjaWVuY2VkaXJlY3QuY29t&ua=131c585b5302000306&rr=842fcdedbdd0062b&cc=us'
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

