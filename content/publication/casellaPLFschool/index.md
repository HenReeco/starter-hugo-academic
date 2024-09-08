---
title: "Forecasting Beef Cattle Growth using Computer Vision and Machine Learning"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
other authors:
- Guilherme L. Menezes
- Alyssa Seitz
- Matthew Akins
- Joao R. R. Dorea

# Author notes (optional)
# author_notes:
# - "First author"
# - "Equal contribution"

date: "2024-09-07T00:00:00Z"
doi: https://sites.google.com/unesp.br/plfschool/program?authuser=0

# Schedule page publish date (NOT publication's date).
publishDate: "2024-09-07T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["0"]

# Publication name and optional abbreviated publication name.
publication: In *SPSAS PLF School 2024*
publication_short: In *SPSAS PLF School 2024*

abstract: Body weight (BW) is an important phenotype in livestock farming as it allows the monitoring of animal health and production, breeding selection, as well as feed management and efficiency. Particularly, in the context of beef cattle, final BW is an important aspect of decision making for optimal harvesting and efficient use of resources. Since performing BW measurements on a large scale is costly and labor-intensive, various studies have investigated the application of Computer Vision (CV) and Machine Learning (ML) techniques for BW predictions. However, existing works primarily focus on predictions of current BW, but do not explore forecasting BW months into the future. To address this gap, we propose an approach that leverages CV and ML to predict BW several months ahead based on animals’ currently available data. In this study, we evaluated the use of Gradient Boosting Trees (GBT) to predict BW at 12 months of age of 95 beef-on-dairy animals followed from a starting age of 159 ± 33 d to a final age of 399 ± 15 d, with final BW 630.2 ± 51.8 kg (mean ± SD). Monthly data consisted of manual measurements (height, length, girth, hip width, weight, age, birthweight, bodyweight, and gender) and biometrics extracted from 3D images captured from the dorsal area (volume, area, circularity, extent, eccentricity, perimeter, major axis length, and pixel area). A pre-processing step was implemented to fill in the data between consecutive monthly manual measurements with a linear interpolation, allowing a consistent age selection in the following experiments. When predicting BW at 360 days of age using all available features, GBT achieved RMSE = 25.8 kg, RMSEp = 4.62 kg, R2 = 0.55 using input features at 160 days of life, RMSE = 23.48 kg, RMSEp = 4.3%, R2 = 0.65 at 230, and RMSE = 15.5 kg, RMSPE = 2.8%, R2 = 0.85 at 300 d. We removed three-dimensional features such as height, and volume, and other complex features such as girth and birthweight. With these features, GBT achieved RMSE = 25.35 kg, RMSEp = 4.5%, R2 = 0.57 using input features at 160 days of life, RMSE = 22.68 kg, RMSPE = 4.17%, R2 = 0.67 at 230 days of life, and RMSE = 15.59 kg, RMSPE = 2.81%, R2 = 0.84 at 300 days of life. Interestingly, GBT seems to better learn growth patterns when fewer features are provided. In summary, this work shows the potential of CV and ML to forecast body growth in beef cattle, which can be a helpful tool to improve growth development based on optimized nutritional strategies. However, further investigations are needed to replace observed bodyweight with its predictions as input feature, and to evaluate performance on more heterogeneous datasets.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

# tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

# url_pdf: ''
# url_code: ''
# url_dataset: ''
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: ''
# url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.

# to add this in other pages:
# projects:
# - 2animals

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->