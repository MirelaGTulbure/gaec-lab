---
title: "A multi-sensor satellite imagery approach to monitor on-farm reservoirs"
authors:
- viniperin
- admin
- molliegaines
- Michele L. Reba
- Mary A. Yaeger

author_notes:
- "Corresponding Author"


date: "2022-01-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2022-01-01T00:00:00Z"

# Indicate if this is related to GAEC by typing "lab-related" if not, leave blank
categories: "lab-related"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Remote Sensing of Environment"
publication_short: ""

abstract: Fresh water stored by on-farm reservoirs (OFRs) is an important component of surface hydrology and is critical for meeting global irrigation needs. Farmers use OFRs to store water during the wet season and for crop irrigation during the dry season, yet their seasonal and inter-annual variability and downstream impacts are not quantified. Therefore, OFRs’ sub-weekly surface area changes are critical to understanding their dynamics and mitigating their downstream impacts. However, prior to the recent increase in satellite imagery availability and improve- ment in sensors’ spatial resolution, monitoring the OFRs’ sub-weekly surface area changes across space and time was challenging because OFRs occur in high numbers (i.e. hundreds) and are small water bodies (< 50 ha). We propose a novel multi-sensor approach to monitor OFRs surface areas, developed based on 736 OFRs in eastern Arkansas, USA, which leverages the use of PlanetScope (PS), RapidEye (RE), Sentinel 2 (S2), and Sentinel 1 (S1). First, we estimate the uncertainties in surface area for each sensor by comparing the surface area estimates to a validation dataset, and by comparing RE, S2 and S1 to PS—the sensor with the highest spatial resolution (i.e. 3.125 m). Second, we use the uncertainties of each sensor with a data assimilation algorithm based on the Kalman filter to obtain sub-weekly surface area time series for all OFRs. Our results show the lowest uncertainties for PS, followed by RE, S2 and S1. These uncertainties varied according to the OFRs’ size and shape complexities. The surface area estimates derived from the Kalman filter including only the optical sensors resulted in high agreement (r2 > 0.95) and small uncertainties (4–8%) when compared to the validation dataset. We found higher uncertainties (5–14%) when adding S1 to the Kalman filter—this is related to the higher uncertainties found for S1 (~20%). The algorithm can assimilate optical and radar satellite data to increase the OFRs’ surface area time series cadence allowing us to investigate sub-weekly surface area changes. The algorithm is not sensor-specific, and it accounts for the uncertainties in both the sensors observations and the resulting surface areas, which are key advantages when compared to other algorithms used to combine satellite data. By improving the surface area observations cadence and providing the surface area uncertainties, the approach presented in this study has the potential to enhance water conservation plans by allowing better assessment and management of the OFRs.

# Summary. An optional shortened abstract.
summary: 

tags:
- On-farm reservoirs

featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://www.sciencedirect.com/science/article/abs/pii/S0034425721005162
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
  caption: 'From the publication: Fig. 4 (a and b, left). "OFRs outlines (pink lines) overlaid on high-resolution Google maps satellite imagery." and Fig. 12 (a and b, right). "Sub-weekly surface area time series obtained from the Kalman filter for the study case OFRs...Gray shaded area represents +/− one and two standard deviations. The r2 and MAPE values were derived from the Kalman filter comparisons with the independent [PlanetScope] subset.'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: ['On-farm-reservoirs']

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides:
---


