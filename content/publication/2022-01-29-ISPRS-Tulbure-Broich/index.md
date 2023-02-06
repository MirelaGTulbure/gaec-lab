---
title: "Can we detect more ephemeral floods with higher density harmonized Landsat Sentinel 2 data compared to Landsat 8 alone?"
authors:
- admin
- MARKBROICH
- viniperin
- molliegaines
- Junchang Ju
- Stephen V. Stehman 
- Tamlin Pavelsky
- Jeffrey G. Masek 
- Simon Yin 
- Joachim Mai 
- Luc Betbeder-Matibet

author_notes:
- "Corresponding Author"


date: "2022-01-29T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2022-01-29T00:00:00Z"

# Indicate if this is related to GAEC by typing "lab-related" if not, leave blank
categories: "lab-related"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "ISPRS Journal of Photogrammetry and Remote Sensing"
publication_short: ""

abstract: Spatiotemporal quantification of surface water and flooding is essential given that floods are among the largest natural hazards. Effective disaster response management requires near real-time information on flood extent. Satellite remote sensing is the only way of monitoring these dynamics across vast areas and over time. Previous water and flood mapping efforts have relied on optical time series, despite cloud contamination. This reliance on optical data is due to the availability of systematically acquired and easily accessible optical data globally for over 40 years. Prior research used either MODIS or Landsat data, trading either high temporal density but lower spatial resolution or lower cadence but higher spatial resolution. Both MODIS and Landsat pose limitations as Landsat can miss ephemeral floods, whereas MODIS misses small floods and inaccurately delineates flood edges. Leveraging high temporal frequency of 3–4 days of the existing Landsat-8 (L8) and two Sentinel-2 (S2) satellites combined, in this research, we assessed whether the increased temporal frequency of the three sensors improves our ability to detect surface water and flooding extent compared to a single sensor (L8 alone). Our study area was Australia’s Murray-Darling Basin, one of the world’s largest dryland basins that experiences ephemeral floods. We applied machine learning to NASA’s Harmonized Landsat Sentinel-2 (HLS) Surface Reflectance Product, which combines L8 and S2 observations, to map surface water and flooding dynamics. Our overall accuracy, estimated from a stratified random sample, was 99%. Our user’s and producer’s accuracy for the water class was 80% (±3.6%, standard error) and 76% (±5.8%). We focused on 2019, one of the most recent years when all three HLS sensors operated at full capacity. Our results show that water area (permanent and flooding) identified with the HLS was greater than that identified by L8, and some short-lived flooding events were detected only by the HLS. Comparison with high resolution (3 m) PlanetScope data identified extensive mixed pixels at the 30 m HLS resolution, highlighting the need for improved spatial resolution in future work. The HLS has been able to detect floods in cases when one sensor (L8) alone was not, despite 2019 being one of the driest years in the area, with few flooding events. The dense optical time-series offered by the HLS data is thus critical for capturing temporally dynamic phenomena (i.e., ephemeral floods in drylands), highlighting the importance of harmonized data such as the HLS.

# Summary. An optional shortened abstract.
summary: 

tags:
- HLS Flood Detection
- lab-related

featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://www.sciencedirect.com/science/article/abs/pii/S0924271622000338?via%3Dihub
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
  caption: 'Figure 3 from the publication. "Surface water and flooding frequency using L8 (left), S2 (middle), and HLS data in 2019 in the MDB (top row) and four regions (rows 2–5) to illustrate the difference in L8, S2, and the HLS." '
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: ['Multi-Sensor-Floods']

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

### Media Coverage:
- <a href="https://landsat.gsfc.nasa.gov/article/time-is-of-the-essence-when-monitoring-dryland-floods/">NASA Landsat Science - Time is of the Essence When Monitoring Dryland Floods</a>