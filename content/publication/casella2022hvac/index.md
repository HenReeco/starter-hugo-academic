---
title: "HVAC Power Conservation through Reverse Auctions and Machine Learning"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
other authors:
- Atieh R. Khamesi
- Simone Silvestri
- D. A. Baker
- Sajal K. Das

# Author notes (optional)
author_notes:
- "First author"
# - "Equal contribution"

date: "2022-03-03T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2022-03-03T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the International Conference on Pervasive Computing and Communications (PerCom), 2022 - 18/178 accepted papers*
publication_short: In *Proceedings of the International Conference on Pervasive Computing and Communications (PerCom), 2022 - 18/178 accepted papers*

abstract: Prolonged rotating outages and exorbitant energy bills, recently experienced in California and Texas, have exposed the limitations and need for modernizing electric power systems. The occurrence of such events is a consequence of peak loads, often due to extreme outside temperatures that simultaneously trigger Heating Ventilation Air Conditioning (HVAC) systems. Leveraging pervasive computing technologies, such as smart meters and smart thermostats, this paper introduces a comprehensive approach to perform residential HVAC power conservation and prevent these catastrophic events. Differently from previous solutions, our approach models realistic user behavior and HVAC dynamics of individual homes. Specifically, we formulate a novel reverse auction-based problem, called POwer Conservation Optimization (POCO). The goal is to perform power conservation by motivating users to temporarily adjust their HVAC thermostat settings in exchange for financial rewards. We prove that POCO ensures truthfulness and individual rationality of the auction mechanism, although it is an NP-hard problem. Therefore, we propose an efficient heuristic, called Greedy Ranking AllocatioN (GRAN), which we prove ensures the same formal properties, while incurring only a polynomial complexity. To predict power savings resulting from an HVAC thermostat adjustments, we propose a novel machine learning-based technique called Power Saving Prediction (PSP). In addition, we conduct an online survey to study the willingness to adopt the proposed system and to model realistic user behavior. Survey results show willingness of adoption above 79% and a highly heterogeneous and non-linear user behavior. We perform extensive experiments using high-fidelity simulator EnergyPlus. Results show that PSP outperforms a state-of-the-art solution obtaining 85% predictions within a 5% error margin. Furthermore, GRAN achieves near-optimal performance, outperforming a recent state-of-the-art approach obtaining results between 58% and 68% closer to the optimum.

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
- 1smartgrids

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