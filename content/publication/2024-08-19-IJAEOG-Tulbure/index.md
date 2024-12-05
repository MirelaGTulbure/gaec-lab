---
title: "Taking it further: Leveraging pseudo-labels for field delineation across label-scarce smallholder regions"
authors:
- Philippe Rufin
- Sherrie Wang
- Sa Nogueira Lisboa
- Jan Hemmerling
- admin
- Patrick Meyfroidt

author_notes:
- "Author"

date: "2024-09-13T00:00:00Z"
doi: "https://doi.org/10.1016/j.jag.2024.104149"

# Schedule page publish date (NOT publication's date).
publishDate: "2024-12-04T15:45:00Z"

# Indicate if this is related to GAEC by typing "Lab Related" if not, leave blank
categories: "Lab Related" 

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "International Journal of Applied Earth Observation and Geoinformation"
publication_short: ""

abstract: Satellite-based field delineation has entered a quasi-operational stage due to recent advances in machine learning for computer vision. Transfer learning allows for the resource-efficient transfer of pre-trained field delineation models across heterogeneous geographies. However, the scarcity of labeled data for complex and dynamic smallholder landscapes remains a major bottleneck. The key innovation of this study is to overcome this challenge by using pre-trained models to generate sparse (i.e., not fully annotated) field delineation pseudo-labels for fine-tuning models across geographies and sensor characteristics. We build on a FracTAL ResUNet trained for crop field delineation in India (median field size of 0.24 ha) based on multi-spectral imagery at 1.5 m spatial resolution. We use this model to generate pseudo-labels for the use in Northern Mozambique (median field size of 0.06 ha) based on sub-meter resolution true-color satellite imagery. We designed multiple pseudo-label selection strategies based on field-level probability scores and compared the quantities, area properties, seasonal distribution, and spatial agreement of the pseudo-labels against human-annotated training labels (n = 1,512). We then used the human-annotated labels and the pseudo-labels for model fine-tuning and compared predictions against human field annotations (n = 2,199). We evaluated performance with regards to object-level spatial agreement and site-level field size estimation. Our results indicate i) a good baseline performance of the pre-trained model in both field delineation (mean intersection over union (mIoU) of 0.634) and field size estimation (mean root mean squared error (mRMSE) of 0.071 ha), and ii) the added value of regional fine-tuning with performance improvements in nearly all experiments (mIoU increases of up to 0.060, mRMSE decreases of up to 0.034 ha). Moreover, we found iii) substantial performance increases when using only pseudo-labels (up to 77 % of the mIoU increases and 68 % of the mRMSE decreases obtained by human-annotated labels), and iv) additional performance increases (mIoU+0.008, mRMSE −0.003 ha) when complementing human annotations with pseudo-labels. Pseudo-labels are architecture-agnostic, can be efficiently generated at scale, and thus facilitate domain adaptation in label-scarce settings. The workflow presented here is a stepping stone for overcoming the persisting challenges in mapping heterogeneous smallholder agriculture.

# Summary. An optional shortened abstract.
summary: []

tags:
- Cropland
- Deep Learning
- Earth Observation
- Mozambique
- Sub-Saharan Africa
- Transfer Learning

featured: false

# links:
# - name: ""
#   url: ""
url_pdf: 'https://www.sciencedirect.com/science/article/pii/S156984322400503X/pdfft?md5=4e066a4ed891e221366ef4b7b1c49b88&pid=1-s2.0-S156984322400503X-main.pdf'
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

