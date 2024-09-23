---
title: 'Automated detection and measurement of individual sorghum panicles using density-based clustering of terrestrial lidar data'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Lonesome Malambo
  - Sorin Popescu
  - David W. Horne
  - admin
  - William L. Rooney

# Author notes (optional)
#author_notes:
date: '2019-01-22'
doi: 'https://doi.org/10.1016/j.isprsjprs.2018.12.015'

# Schedule page publish date (NOT publication's date).
#publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['Research Paper']

# Publication name and optional abbreviated publication name.
publication: In *ISPRS Journal of Photogrammetry and Remote Sensing*
#publication_short: In *F*

abstract: Plant breeders normally require an assessment of various plant traits to breed new crop varieties or improve processes in crop production. This assessment, generally referred to as plant phenotyping, often involves significant manual measurement, which creates a bottleneck in breeding programs. Using current high-density terrestrial laser scanning systems presents an opportunity to measure individual plants and organ-specific traits to support various crop improvement and agronomic initiatives. The main goal of this study was to assess the feasibility of applying terrestrial laser scanning (TLS) data for estimating counts and individual dimensions (panicle length, width, and height) of sorghum panicles – the flowering parts of sorghum plants that eventually yield seed when the plants mature. To achieve our goal, we developed and assessed a density-based clustering approach to derive the targeted information from TLS data. Estimated individual panicle data (panicle counts and individual panicle dimensions) from a random sample of 20 plots were compared with LiDAR-derived panicle data. Overall, panicles were detected (counted) with an overall accuracy of 89.3% with a 10.7% omission and 14.3% commission rate. Omission errors were caused mainly by poor point cloud sampling, while commission errors were driven by spectral similarities between panicle and other crop components such as dry foliage. Estimated panicle dimensions were highly correlated with reference LiDAR-derived panicle measurements (Panicle length Pearson correlation (r) = 0.88, Root mean square error (RMSE) = 3.10 cm; panicle width r = 0.79, RMSE = 1.67 cm; plant height r = 1.00, RMSE = 0.80 cm). A plot-level comparison involving 43 plots was also carried out between estimated panicle data and panicle data derived from a sample of harvested panicles and showed moderate to high correlations between the two datasets (Panicle length r = 0.79, RMSE = 2.48 cm; panicle width r = 0.63, RMSE = 1.49 cm; plant height r = 0.86, RMSE = 11.4 cm). The lower correlations with field data may be reflective of the impact of sampling rates, the compaction and dry down of panicles after harvest and experimental error in general. An analysis of the impact of simulated noise on estimates, showed that the developed method is moderately robust to lower noise levels (<30%) but its performance deteriorates at high levels showing the critical need for prior noise filtering. Overall, this study shows that TLS and similar point cloud data has the potential to expedite field-based plant phenotyping tasks.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin #condimentum.

tags:
  - Remote Sensing
  - Trait Identification

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
#url_project: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 
  focal_point: 
  preview_only: false
  orientation: 'none'  # or you can use '0' to indicate no rotation

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---
