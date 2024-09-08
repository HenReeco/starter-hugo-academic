---
title: "Phenotyping mammary gland of dairy cows through histological image analysis"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
other authors:
- Alysia Vang
- Guilherme L. Menezes
- Guilherme J. M. Rosa
- Laura L. Hernandez
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

abstract: Mammary gland growth is an important phenotype due to its correlation with future lactation performance. Currently, biopsies represent the standard procedure to procure histological data to assess mammary gland development. However, analyzing individual microscopic images is a labor-intensive and time-consuming task that can only provide a few visual and manual measurements, limiting the ability to extract meaningful or novel phenotypes. Computer vision has been a powerful tool in medical sciences for real-time identification and segmentation of biological tissues, as well as quantitative analysis on tissue size, and geometric features. Therefore, this study aims to implement a computer vision system for the multilabel semantic segmentation of microscopic images from biopsies of the mammary gland using a U-net model. The segmentation model was trained on over 80,000 samples, as a result of patching 80 high-resolution histological tissue biopsies from 20 dairy calves at 10, 26, 39, and 52 wk of age, and tested on 56 images (56,000 patches from 14 animals). Tissue growth was analyzed with a linear mixed model including diet, week, and their interaction as fixed effects, birthweight as a covariate, and animal as a random effect. The segmentation model achieved an intersection over union of 0.88. The correlations between predicted and observed adipose, stroma, and duct area in the testing set were 0.99, 0.99, and 0.97, respectively. There was a significant effect (P < 0.03) of week on adipose and stroma area (% of total issue), ducts and adipose circularity, and ducts and stroma eccentricity. The adipose tissue area (%) increased 5 times from wk 10 to 26 and 1.34 times from wk 26 to 52. This suggests a nonlinear and decelerating growth development of the mammary gland during the period evaluated. Although the association between such rate of growth and lactation performance should be investigated, the use of image-based features can allow for large-scale phen

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