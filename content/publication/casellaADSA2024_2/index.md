---
title: "Exploring symbolic regression for body weight prediction in dairy calves"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
other authors:
- Guilherme J. M. Rosa
- Joao R. R. Dorea

# Author notes (optional)
# author_notes:
# - "First author"
# - "Equal contribution"

date: "2024-06-16T00:00:00Z"
doi: https://www.adsa.org/Portals/0/SiteContent/Docs/Meetings/2024ADSA/Abstracts_BOOK_2024_FINAL.pdf

# Schedule page publish date (NOT publication's date).
publishDate: "2024-06-16T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["0"]

# Publication name and optional abbreviated publication name.
publication: In *ADSA 2024*
publication_short: In *ADSA 2024*

abstract: Monitoring heifer growth development is an important aspect of decision making in dairy farms, as a tool for health assessments, feed management, and breeding selection. Monitoring growth requires frequent body weight (BW) measurements; however, weighing calves is costly and labor-intensive. Computer vision and machine learning (ML) have been proposed as a powerful tool to predict BW in livestock animals. However, most ML techniques involve tuning a large number of parameters that increase the risk of overfitting in small data sets. Besides, these models lack interpretability and do not reveal biological associations between predictors and response variables. Symbolic regression (SR) is a ML approach that leverages genetic algorithms to find analytical equations and their coefficients to describe the output based on the input variables. In this study, we evaluated the use of SR versus gradient boosting trees (GBT) to predict BW in 67 pre-weaning Holstein dairy calves from 2 to 8 weeks of age, and BW of 57.0 ± 14.7 kg. A total of 400 3D images were captured from the dorsal area (top-down view) during weighing on a digital scale, and we extracted 27 biometric features from depth images (area, volume, length, 11 heights and widths along the dorsal area, eccentricity, and extent). Both SR and GBT were evaluated against observed BW using a nested cross-validation (5-fold for hyperparameter tuning and leave-one-out for testing). GBT achieved root mean squared error of prediction (RMSEP) = 7.7 kg, mean absolute error (MAE) = 5.8 kg, R2  = 0.59, and concordance correlation coefficient (CCC) = 0.78. Among the frequently high-ranked equations we found (1) BW = a + b × Volume, (2) BW = √Area + Width6, and (3) BW = (Width5 + c)^d . The median values for a, b, c, and d were 31.53, 0.22, 12.14, and 1.16. SR presented better predictive performance than GBT, with (1) presenting RMSEP = 6.0, MAE = 4.9, R2  = 0.67, and CCC = 0.86. While further investigations are needed on more heterogeneous data sets, SR shows the potential to predict BW using simple linear and nonlinear equations that may generalize well, with low computational cost, and with the benefit of interpretability.

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