---
title: "Towards global flood mapping with machine learning based on the Harmonized Landsat-Sentinel 2 data"
authors:
- admin
- markbroich
- molliegaines
- Stephen V. Stehman
- Tamlin Pavelsky
- Vinicus Perin
- Junchang Ju
- Simon Yin
- Joachim Mai
- Luc Betbeder-Matibet

author_notes:
- "Corresponding Author"


date: "2021-12-16T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-12-16T00:00:00Z"

# Indicate if this is related to GAEC by typing "Lab Related" if not, leave blank
categories: 

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "AGU"
publication_short: ""

abstract: Floods are the largest natural hazard in terms of life loss and economic damage, regardless of their cause. In the United States alone, floods cause billions of dollars in property damage, with an estimate exceeding $78 billion due to fluvial floods in any given year. Effective and immediate disaster response management can reduce the impact of floods but it requires near real-time information on flood occurrence. To best allocate limited resources and prioritize response actions during hazardous floods, emergency responders need near real-time information on flood-water extent, typically derived based on Earth Observation (EO) data. Satellite remote sensing offers the only means of monitoring and quantifying flooding extent dynamics and the availability of public domain, systematically acquired satellite data archives, together with improvements in algorithms and available computing power have led to huge leaps in the recent years in mapping surface water dynamics and flooding. A large proportion of the prior work has relied on optical data, including MODIS and Landsat thus trading high temporal resolution with daily maps in the case of MODIS or higher spatial resolution but coarser temporal resolution in the case of Landsat. However, the recent availability of NASA’s Harmonized Landsat/Sentinel-2 (HLS, https://hls.gsfc.nasa.gov/) Surface Reflectance Product, a seamless data set combining Landsat 8 and Sentinel 2 observations, is promising in detecting floods at Landsat resolution and 3-day interval. New work in a dryland basin that experiences ephemeral floods showed that large short-lived flooding events were detected only by HLS (the combined dataset) but have been entirely missed by Landsat 8. Here we picked major flood events globally labeled with collocated Harmonized-Sentinel-2 data and applied machine learning models for flood detection. The most important features for flood detection included the SWIR bands, the automated water extraction indices, and vegetation indices. Future work will integrate Sentinel 1 radar data collocated to the Harmonized-Sentinel-2 data for improved detection of floods during cloudy conditions. This work also highlights the importance of existing harmonized data products such as HLS.

# Summary. An optional shortened abstract.
summary: 

tags:
- Flooding
- MODIS
- Landsat
- HLS

featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://agu.confex.com/agu/fm21/meetingapp.cgi/Paper/911456
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
projects: ['Multi-Sensor-Flood']

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---


