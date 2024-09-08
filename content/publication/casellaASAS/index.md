---
title: "Evaluating a foundation model for animal body segmentation based on few-shot learning against a domain-specific deep neural network"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
other authors:
- Joao R. R. Dorea

# Author notes (optional)
# author_notes:
# - "First author"
# - "Equal contribution"

date: "2024-07-21T00:00:00Z"
doi: https://www.adsa.org/Portals/0/SiteContent/Docs/Meetings/2024ADSA/Abstracts_BOOK_2024_FINAL.pdf

# Schedule page publish date (NOT publication's date).
publishDate: "2024-07-21T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["0"]

# Publication name and optional abbreviated publication name.
publication: In *ASAS 2024*
publication_short: In *ASAS 2024*

abstract: Computer vision (CV) has been proposed as a powerful technology to collect individual measurements of livestock animals, such as body weight or body condition score, to name a few. In all these tasks, the first step of image processing is semantic segmentation (SS), which represents the use of deep neural networks to locate pixels that belong to the animal body, while removing the background, which may add noise and other information that are not needed to compute body biometrics. Despite the generalization abilities of CV, oftentimes SS models need to be re-trained on the specific dataset at hand in order to maximize performance, and thus require labor-intensive annotations. With the rise of foundation models like GPT-4, LLaMA, DALL-E, among others, we aim to explore whether a foundation model for SS called SegGPT performs well in a highly specific agricultural scenario, in comparison with a model trained using domain-specific data, i.e., a U-net model trained on our datasets. Our evaluation is carried out over 9 different datasets of top-down depth images over calves’ and cows’ bodies. The combined datasets amount to a total of 4328 images (average count = 541) from 485 animals (average count = 54) from 2 weeks to 7 years of age, and it was collected with a mix of RealSense D435 and Kinect V2 sensors at several farm settings (entering/exiting the milking parlor, in a chute, or during weighing on a scale or weighing cart). We investigated the performance of these two models under several scenarios - training on a single dataset and validating within the same dataset (Same Dataset Internal Validation; SDIV), training on a single dataset and validating on an external dataset (Same Dataset External Validation; SDEV), and training on multiple datasets and validating on an external dataset (Multiple Datasets External Validation; MDEV). For the U-net trained in the SDIV approach, we used a 70/30 train/test split over 100 epochs. SegGPT and U-net presented intersection over union of 0.84 and 0.95, 0.73 and 0.59, 0.84 and 0.91, for SDIV, SDEV, and MDEV, respectively. U-net was not able to segment the animal body with performance similar to SegGPT in a new dataset when trained with a single dataset, but it outperformed SegGPT when trained with multiple datasets. Although U-net performed slightly better on these scenarios, it’s important to highlight that SegGPT only received one prompt (one depth image with its annotation) per dataset and performed reasonably well on unseen (validation) datasets. In conclusion, foundation models for image processing tasks can be an alternative for training domain-specific deep neural networks, which demands labor, annotation, and large datasets to present satisfactory results. However, high performance still requires domain-specific models in similar agricultural scenarios.

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