---
title: "Mapping individual tree health using full-waveform airborne laser scans and imaging spectroscopy: A case study for a floodplain eucalypt forest"
authors:
- yurishendryk
- markbroich
- admin
- Sergey V.Alexandrov

author_notes:
- "Corresponding Author"

date: "2016-02-15T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2015-11-12T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Remote Sensing of Environment"
publication_short: ""

abstract: Full-waveform airborne laser scanning (ALS) is a powerful tool for characterizing and monitoring forest structure over large areas at the individual tree level. Most of the existing ALS-based algorithms for individual tree delineation from the point cloud are top-down, which are accurate for delineating cone-shaped conifers, but have lower delineation accuracies over more structurally complex broad-leaf forests. Therefore, in this study we developed a new bottom-up algorithm for detecting trunks and delineating individual trees with complex shapes, such as eucalypts. Experiments were conducted in the largest river red gum forest in the world, located in the south-east of Australia, that experienced severe dieback over the past six decades. For detection of individual tree trunks, we used a novel approach based on conditional Euclidean distance clustering that takes advantage of spacing between laser returns. Overall, the algorithm developed in our study was able to detect up to 67% of field-measured trees with diameter larger than or equal to 13 cm. By filtering ALS based on the intensity, return number and returned pulse width values, we were able to differentiate between woody and leaf tree components, thus improving the accuracy of tree trunk detections by 5% as compared to non-filtered ALS. The detected trunks were used to seed random walks on graph algorithm for tree crown delineation. The accuracy of tree crown delineation for different ALS point cloud densities was assessed in terms of tree height and crown width and resulted in up to 68% of field-measured trees being correctly delineated. The double increase in point density from ~ 12 points/m2 to ~ 24 points/m2 resulted in tree trunk detection increase of 11% (from 56% to 67%) and percentage of correctly delineated crowns increase of 13% (from 55% to 68%). Our results confirm an algorithm that can be used to accurately delineate individual trees with complex structures (e.g. eucalypts and other broadleaves) and highlight the importance of full-waveform ALS for individual tree delineation.

# Summary. An optional shortened abstract.
summary: Full-waveform airborne laser scanning (ALS) is a powerful tool for characterizing and monitoring forest structure over large areas at the individual tree level. Most of the existing ALS-based algorithms for individual tree delineation from the point cloud are top-down, which are accurate for delineating cone-shaped conifers, but have lower delineation accuracies over more structurally complex broad-leaf forests.

tags:

featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://www.sciencedirect.com/science/article/abs/pii/S0034425715301966
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
projects: 


# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides:
---


