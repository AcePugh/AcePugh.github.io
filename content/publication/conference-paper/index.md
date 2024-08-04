---
title: 'Yield prediction in a peanut breeding program using remote sensing data and machine learning algorithms'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Andrew Young
  - Manisha Ojha
  - Yves Emendack
  - Jacobo Sanchez
  - Zhanguo Xin
  - Naveen Puppala

# Author notes (optional)
#author_notes:
date: '2024-02-19'
doi: 'https://doi.org/10.3389/fpls.2024.1339864'

# Schedule page publish date (NOT publication's date).
#publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-research']

# Publication name and optional abbreviated publication name.
publication: In *Frontiers in Plant Science*
#publication_short: In *F*

abstract: Peanut is a critical food crop worldwide, and the development of high-throughput phenotyping techniques is essential for enhancing the crop’s genetic gain rate. Given the obvious challenges of directly estimating peanut yields through remote sensing, an approach that utilizes above-ground phenotypes to estimate underground yield is necessary. To that end, this study leveraged unmanned aerial vehicles (UAVs) for high-throughput phenotyping of surface traits in peanut. Using a diverse set of peanut germplasm planted in 2021 and 2022, UAV flight missions were repeatedly conducted to capture image data that were used to construct high-resolution multitemporal sigmoidal growth curves based on apparent characteristics, such as canopy cover and canopy height. Latent phenotypes extracted from these growth curves and their first derivatives informed the development of advanced machine learning models, specifically random forest and eXtreme Gradient Boosting (XGBoost), to estimate yield in the peanut plots. The random forest model exhibited exceptional predictive accuracy (R2 = 0.93), while XGBoost was also reasonably effective (R2 = 0.88). When using confusion matrices to evaluate the classification abilities of each model, the two models proved valuable in a breeding pipeline, particularly for filtering out underperforming genotypes. In addition, the random forest model excelled in identifying top-performing material while minimizing Type I and Type II errors. Overall, these findings underscore the potential of machine learning models, especially random forests and XGBoost, in predicting peanut yield and improving the efficiency of peanut breeding programs.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin #condimentum.

tags:
  - Drones
  - Machine Learning
  - Peanut

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
url_dataset: 'https://github.com/HugoBlox/hugo-blox-builder'
url_poster: ''
url_project: ''
url_slides: ''
url_source: 'https://github.com/HugoBlox/hugo-blox-builder'
url_video: 'https://youtube.com'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption:
  focal_point: ''
  preview_only: false

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

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
