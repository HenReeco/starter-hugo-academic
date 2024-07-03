---
title: "A machine learning and optimization framework for the early diagnosis of bovine respiratory disease"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
other authors:
- Melissa C. Cantor
- Megan M. Woodrum Setser
- Simone Silvestri
- Joao H. C. Costa


# Author notes (optional)
author_notes:
- "First author"
# - "Equal contribution"

date: "2023-06-30T00:01:00Z"
doi: "https://doi.org/10.1109/ACCESS.2023.3291348"

# Schedule page publish date (NOT publication's date).
publishDate: "2023-06-30T00:01:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *IEEE Access 2023*
publication_short: In *IEEE Access 2023*

abstract: Bovine Respiratory Disease (BRD) is an infection of the respiratory tract that is the leading reason for antimicrobial use in dairy calves and represents 22% of calf mortalities. The costs and effects of BRD can severely damage a farm’s economy, since raising dairy calves is one of the largest economic investments, and diagnosing BRD requires intensive and specialized labor that is hard to find. Precision technologies based on the Internet of Things (IoT), such as automatic feeders, scales, and accelerometers, can help detect behavioral changes before outward clinical signs of BRD. Such early detection enables early treatment, and thus faster recovery, with less long term effects. In this paper, we propose a framework for BRD diagnosis, its early detection, and identification of BRD persistency status using precision IoT technologies. We adopt a machine learning model paired with a cost-sensitive feature selection problem called Cost Optimization Worth (COW). COW maximizes prediction accuracy given a budget constraint. We show that COW is NP-Hard, and propose an efficient heuristic with polynomial complexity called Cost-Aware Learning Feature (CALF). We validate our methodology on a real dataset collected from 159 calves during the preweaning period. Results show that our approach outperforms a recent state-of-the-art solution. Numerically, we achieve an accuracy of 88% for labeling sick and healthy calves, 70% of sick calves are predicted 4 days prior to diagnosis, and 80% of persistency status calves are detected within the first five days of sickness.

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