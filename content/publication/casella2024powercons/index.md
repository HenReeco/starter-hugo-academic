---
title: "A Human-Centered Power Conservation Framework based on Reverse Auction Theory and Machine Learning"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
other authors:
- Simone Silvestri
- D. A. Baker
- Sajal K. Das

# Author notes (optional)
author_notes:
- "First author"
# - "Equal contribution"

date: "2024-04-05T00:00:00Z"
doi: "https://doi.org/10.1145/365634"

# Schedule page publish date (NOT publication's date).
publishDate: "2024-04-05T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *ACM Transactions on Cyber-Physical Systems, 2024*
publication_short: In *ACM Transactions on Cyber-Physical Systems, 2024*

abstract: Extreme outside temperatures resulting from heat waves, winter storms, and similar weather-related events trigger the Heating Ventilation and Air Conditioning (HVAC) systems, resulting in challenging, and potentially catastrophic, peak loads. As a consequence, such extreme outside temperatures put a strain on power grids and may thus lead to blackouts. In order to avoid the financial and personal repercussions of peak loads, demand response and power conservation represent promising solutions. Despite numerous efforts, it has been shown that the current state-of-the-art fails to consider - i) the complexity of human behavior when interacting with power conservation systems; and ii) realistic home-level power dynamics. As a consequence, this leads to approaches that are i) ineffective due to poor long-term user engagement; and ii) too abstract to be used in real-world settings. In this paper, we propose an auction-theory-based power conservation framework for HVAC designed to address such individual human component through a three-fold approach - personalized preferences of power conservation, models of realistic user behavior, and realistic home-level power dynamics. In our framework, the System Operator (SO) sends Load Serving Entities (LSEs) the required power saving to tackle peak loads at the residential distribution feeder. Each LSE then prompts its users to provide bids, i.e., personalized preferences of thermostat temperature adjustments, along with corresponding financial compensations. We employ models of realistic user behavior by means of online surveys to gather user bids and evaluate user interaction with such system. Realistic home-level power dynamics are implemented by our machine-learning-based Power Saving Predictions (PSP) algorithm, calculating the individual power savings in each user’s home resulting from such bids. A machine-learning-based Power Saving Predictions (PSP) algorithm is executed by the users’ Smart Energy Management System (SEMS). PSP translates temperature adjustments into the corresponding power savings. Then, the SEMS sends bids back to the LSE, which selects the auction winners through an optimization problem called POwer Conservation Optimization (POCO). We prove that POCO is NP-hard, and thus provide two approaches to solve this problem. One approach is an optimal pseudo-polynomial algorithm called DYnamic programming Power Saving (DYPS), while the second is a heuristic polynomial-time algorithm called Greedy Ranking Allocation (GRAN). EnergyPlus, the high-fidelity and gold-standard energy simulator funded by the U.S. Department of Energy, was used to validate our experiments, as well as to collect data to train PSP. We further evaluate the results of the auctions across several scenarios, showing that, as expected, DYPS finds the optimal solution, while GRAN outperforms recent state-of-the-art approaches.

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