---
title: "Surface water and flooding dynamics data set based on seasonally continuous Landsat data (1986-2011) in a dryland river basin"
authors:
- admin
- markbroich

author_notes:
- "Corresponding Author"

date: "2018-12-18T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2016-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["0"]

# Publication name and optional abbreviated publication name.
publication: "Dataset - Zenodo"
publication_short: ""

abstract: Please refer to the above mentioned publication for a description of the data and interpretation of the patterns. The animations are based on statistically validated surface water and flooding extent dynamics data derived from seasonally continous Landsat TM/ETM+ and random forest models from 1986 to 2011 over Australia's Murray-Darling Basin. The overall accuracy was over 99% and producer's accuracy for water 87% +/- 3%. 

tags:
- Murray–Darling Basin

featured: false

links:
- name: "Dataset Link"
  url: https://zenodo.org/record/2441784#.YMtv7mhKguU
url_pdf: 
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
projects: ['MDB-Floods']

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides:
---

The layers provided here are part of the following publication: [Tulbure, M.G. and M. Broich (2018)](https://www.sciencedirect.com/science/article/pii/S0048969718347466).

The method is described in [Tulbure et al. (2016)](https://www.sciencedirect.com/science/article/pii/S0034425716300621).

Data are provided in GeoTIFF format per season per year. File naming convention is as follows:
yy_inund_freq_season_SamplingMethod. For example, "99_inund_freq_winter_max" will represent inundation frequency for winter 1999 resampled using a maximum resampling method. 

Inundation frequency represents the number of times a pixel has been flagged as flooded out of the times that pixel had valid observations * 100. Valid observation exclude no data values and clouds. The valid range of inundation frequency is 0-100 [%], with 255 indicating no data values. Data type is eight bit unsigned integer (uint8). 

The data were resampled to 120m resolution to reduce file size. The resampling methods used include max (e.g. selects the max value of all non-NODATA contributing 30m pixels) and mean (median and min can be provided upon request). If you are unsure which resampling to use, you may want to start with the mean.  