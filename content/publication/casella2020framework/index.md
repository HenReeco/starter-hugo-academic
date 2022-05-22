---
title: "A framework for the recognition of horse gaits through wearable devices"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
other authors:
- Atieh R. Khamesi
- Simone Silvestri

# Author notes (optional)
author_notes:
- "First author"
# - "Equal contribution"

date: "2020-09-01T00:00:00Z"
doi: "https://doi.org/10.1016/j.pmcj.2020.101213"

# Schedule page publish date (NOT publication's date).
publishDate: "2020-09-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *Elsevier Pervasive and Mobile Computing, Vol. 67, Pages 101213, 2020*
publication_short: In *Elsevier Pervasive and Mobile Computing, Vol. 67, Pages 101213, 2020*

abstract: The wearable devices market has been growing exponentially in the last few years and it is expected to count up to 930 million devices by the end of 2021. A common application of wearable devices is Human Activity Recognition (HAR), i.e., the ability of using the sensing capabilities of these devices to monitor and infer human activities. However, Animal Activity Recognition (AAR) has received significantly less attention, and most works on AAR are generally based on invasive specialized devices carried by or implanted on animals. Conversely, in this work we exploit the potential of portable and unobtrusive devices, namely smartwatches, for AAR and specifically for horse gaits recognition. This application finds natural use in horse riding, to improve the structure and balance of the horse work and training. We develop a framework that can be used in a fog computing system composed by a smartphone and a smartwatch for the recognition of horse gaits. The framework performs classification by means of a machine learning approach trained on ad-hoc features based on accelerometer data. The framework allows an offline and an online modes of operation. In the offline mode, the smartwatch is used to collect the accelerometer data and transfer it to the smartphone at the end of the riding session. The feature extraction and classification can be processed directly on the smartphone or offloaded to the cloud. Conversely, in the online mode, the smartwatch is responsible to collect and process the data, thus being able to provide real-time feedback to the rider. This modality also allows to reduce computation, storage, and energy burden on the smartwatch through an adaptive setting of the sampling frequency. We implement our approach on a system composed by a Fitbit Ionic smartwatch and a Samsung Galaxy S10. We use two horses to evaluate the performance, versus recently proposed AAR approaches. Results show that our framework achieves significantly higher classification accuracy. Furthermore, the online scheme enables flexible real-time feedback, at the expense of a small loss in the classification accuracy.

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
  caption: 'Image credit: '
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.

# to add this in other pages:
projects:
- 2animals

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