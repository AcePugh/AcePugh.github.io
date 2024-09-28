---
title: 'Estimating the Severity of Sugarcane Aphids Infestation on Sorghum with Machine Vision'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Xiaoling Deng
  - J. Alex Thomasson
  - admin
  - Junxi Chen
  - William L. Rooney
  - Michael J. Brewer
  - Yeyin Shi

# Author notes (optional)
#author_notes:
date: '2020-11-02'
#doi: '10.33440/j.ijpaa.20200302.89'

# Schedule page publish date (NOT publication's date).
#publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['Research Paper']

# Publication name and optional abbreviated publication name.
publication: In *International Journal of Precision Agricultural Aviation*
#publication_short: In *F*

abstract: Sugarcane aphid (SCA), Melanaphis sacchari, is one of the most prominent insect pests of grain, forage and bio-energy sorghum in the southern US since 2013. Â The timing and dosage of a pesticide application for SCA depend on a close monitoring of its pressure or severity change in the field. Â To assist the field scouting, digital images were taken using a smart phone in proximity of infected leaves and corresponding image processing algorithms were developed later to estimate the infestation severity in this study. Â Image samples were grouped into four classes according to the infestation severity for aphid management considerations; no threat (0-10 SCA/leaf), insecticide use should be considered (11-125 SCA/leaf), insecticide should be used and yield loss likely (126-500 SCA/leaf), and plant death possible (more than 500 SCA/leaf). Â With 5-fold cross validation, results showed that the best average classification accuracy across the four SCA classes was 85.0% with the modified OVO-SVM algorithm. Â The SCA quantification accuracies achieved in this study using the SVM algorithm showed the promise of using machine learning algorithms in this case of aphid density estimation on sorghum leaves. Â The methodology developed in this study can be modified with more sophisticated machine learning algorithms and more data in the future to be incorporated into a handheld or a mobile remote sensing system to assist growers and researchers with automatically quantifying SCA in a fast and objective manner.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin #condimentum.

tags:
  - Pests
  - Remote Sensing
  - Proximal Sensing

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
  caption: A peanut field in Lubbock, TX
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
