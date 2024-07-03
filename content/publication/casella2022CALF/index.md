---
title: "Cost-aware Inference of Bovine Respiratory Disease in Calves using Precision Livestock Technology"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
other authors:
- M. C. Cantor
- Simone Silvestri
- D. L. Renaud
- J. H. C. Costa

# Author notes (optional)
author_notes:
- "First author"
# - "Equal contribution"

date: "2022-03-19T00:00:00Z"
doi: "https://doi.org/10.1109/DCOSS54816.2022.00031"

# Schedule page publish date (NOT publication's date).
publishDate: "2022-03-19T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the IEEE International Conference on Distributed Computing in Sensor Systems (DCOSS), 2022*
publication_short: In *Proceedings of the IEEE International Conference on Distributed Computing in Sensor Systems (DCOSS), 2022*

abstract: Bovine Respiratory Disease (BRD) is the second leading cause of death in young dairy calves, and is associated with less growth, and reduced long-term performance such as less milk production, which makes BRD a financial burden on a farm’s economy. Precision technologies, such as accelerometers, automatic feeders, and cameras have been extensively used to collect, summarize, and interpret changes in baseline dairy cattle behavior. While some efforts to evaluate the presence of statistical relationships between calves’ behavior and BRD status have been made, there is very little research in pairing such technologies with manual examinations to improve the accuracy and cost of BRD monitoring. In this paper, we propose a framework for diagnosis and early prediction of BRD in calves. This framework is composed by a machine learning model as well as by a cost-sensitive feature selection problem called Cost Optimization Worth (COW). COW maximizes prediction accuracy given a budget constraint. We show that COW is NP-Hard and propose an efficient heuristic with polynomial complexity. We validate our methodology on a real dataset of 46 automatic and manually collected features, representing 106 calves observed during the preweaning period of 50 days. Our results show that our machine learning model can correctly classify a sick cow with a 97% accuracy and up to 5 days prior to BRD diagnosis, outperforming a recent state-of-the-art approach. Furthermore, our feature selection results show that in a low-budget scenario, manually collected features are more valuable than automated features in detecting sick cows. Conversely, in a high-budget scenario, automated features report higher accuracy for the early prediction of BRD.

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