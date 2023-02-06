---
title: "Can we detect more ephemeral floods with higher density harmonized Landsat 8/Sentinel 2 data compared to just one sensor?"
authors:
- admin
- markbroich
- Junchang Ju
- viniperin
- molliegaines
- Simon Yin
- Stephen V. Stehman 
- Tamlin Pavelsky
- Joachim Mai
- Luc Betbeder-Matibet
- Jeffrey G Masek

date: "2020-12-07T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-12-07T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *American Geophysical Union*
publication_short: In *AGU*

abstract: Floods, defined as water that temporarily submerges land for over 72 hours or longer, are the largest natural hazard in terms of life loss and economic damage. Effective and immediate disaster response management can reduce the impact of floods but it requires near real-time information on flood occurrence, typically derived based on Earth Observation data. Several water-mapping efforts at large scale have used optical data, despite the fact that cloud cover compromises image time series. This is because systematically acquired optical data providing global coverage have been available for over 40 years. Previous work based on optical data used either high temporal but lower spatial resolution data (e.g. daily MODIS) or lower temporal resolution but higher spatial resolution data (e.g. Landsat). Both data sources have limitations as they may miss small floods/flood edges in the case of MODIS or ephemeral floods in the case of Landsat. With the launch of NASA’s Landsat-8 (L8) and two Sentinel-2 (S2) satellites by the European Space Agency, it is now feasible to acquire optical observations once every 3-4 days. To assess whether the increased temporal frequency of multi-sensor data improves our ability to detect surface water and flooding extent compared to a single sensor, we focused on Australia’s Murray-Darling Basin (MDB), a dynamic dryland basin that experiences ephemeral floods. We used NASA’s Harmonized Landsat/Sentinel-2 (HLS, https://hls.gsfc.nasa.gov/) Surface Reflectance Product, a seamless data set combining L8 and S2 observations, as input to machine learning-based mapping of surface water and flooding. We chose 2019 as the most recent year of full image record of HLS data, with all three sensors operating at full capacity. We show that large short-lived flooding events were detected only by HLS (the combined dataset) but have been entirely missed by L8 (see figure). We found that the area of water (permanent and flooding) identified with HLS was overall greater than that identified by L8. The year 2019 was Australia’s driest years on record. In 2019 there were extremely low river flows, reduced or depleted urban water supplies with several smaller towns running out of regular water supplies entirely, few flood events and drying wetlands. Despite the sparse occurrence of floods in 2019 in the MDB, HLS has been able to detect floods in cases when one sensor (L8) alone was not. The dense optical time series offered by the HLS data set is thus critical for capturing dynamic phenomena, such as ephemeral floods in dryland systems. This work also highlights the importance of existing harmonized data products such as HLS.

# Summary. An optional shortened abstract.
summary: Floods, defined as water that temporarily submerges land for over 72 hours or longer, are the largest natural hazard in terms of life loss and economic damage. Effective and immediate disaster response management can reduce the impact of floods but it requires near real-time information on flood occurrence, typically derived based on Earth Observation data.

tags:
- HLS Flood detection
- lab-related

featured: true

links:
- name: AGU Link
  url: https://agu.confex.com/agu/fm20/meetingapp.cgi/Paper/743162
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
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- 'HLS-Floods'

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides:
---

