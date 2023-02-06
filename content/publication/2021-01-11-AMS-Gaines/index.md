---
title: "Preliminary comparison and evaluation of soil moisture simulated in GFSv15 and GFSv16"
authors:
- Youlong Xia
- Helin Wei
- molliegaines
- Jesse Meng
- George Gayno
- Hang Lei
- Rongqian Yang
- Yihua Wu
- Fanglin Yang
- Michael J. Barlage
- Daryl T. Kleist
- Vijay S. Tallapragada

author_notes:
- "Corresponding Author"


date: "2021-01-11T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-01-11T00:00:00Z"

# Indicate if this is related to GAEC by typing "lab-related" if not, leave blank
categories:

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "AMS"
publication_short: ""

abstract: Accurate estimation of land surface states is critical for improving prediction of coupled global weather and climate forecast systems, especially in regions with strong land-atmosphere interactions (e.g., semi-arid/”hot spots”). Soil moisture observations are sparse and not appropriate for direct use as initial and/or boundary conditions for these systems. Land states produced from these coupled systems often have large errors and drifts owing to substantial biases in the surface forcing (e.g., precipitation). The Global Land Data Assimilation System (GLDAS) utilizes the best available in-situ and remotely sensed observations of land surface properties and surface forcing data to produce enhanced fields of land surface states. The GLDAS does not assimilate observations directly via a data assimilation algorithm, but rather, runs an uncoupled land model by using observed precipitation and additional surface forcings from the parent coupled model (e.g., Global Data Assimilation System GDAS). The GLDAS is run once per day to provide initial soil moisture and temperature to the atmospheric model. Based on such a concept, the NCEP GLDAS will become part of the next version Global Forecast System (GFSv16), which is undergoing retrospective and real-time testing and scheduled to be implemented into operations in February 2021. This presentation summarizes some preliminary comparison and evaluation results of GFSv16 and GFSv15 soil moisture products. These products are first compared with the soil moisture simulated from the North American Land Data Assimilation System (NLDAS), and then evaluated against in-situ observations from the International Soil Moisture Network. The comparison and evaluation are performed for multiple seasons. The preliminary results show that GLDAS/GFSv16 is closer to GFSv15 when compared with NLDAS and in-situ observations. Large differences between modeled and observed soil moisture may come from (1) spatial scale mismatch, (2) different soil types, (3) surface meteorological forcing errors, and (4) Noah land model parameters and structure errors (e.g., inaccurate and/or missing soil and hydrological processes). The reasons for these errors need to be investigated in the future. The presentation also summarizes the potential impact of soil moisture on near-surface temperature and humidity when simulated and observed precipitation is used to generate soil moisture separately.

# Summary. An optional shortened abstract.
summary: 

tags:
- Soil
- Soil moisture
- GLDAS
- NLDAS

featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://ams.confex.com/ams/101ANNUAL/meetingapp.cgi/Paper/378593
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
  caption: 'From the paper, "As
NLDAS, ops GFSv15, and GFSv16 use the Noah model with slight
differences, precipitation amount difference produced in ops GFSv15 may
be a major reason for soil moisture difference when compared with para
GLDAS/GFSv16 and NLDAS precipitation" '
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


