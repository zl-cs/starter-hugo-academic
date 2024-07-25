---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "The Blind and the Elephant: A Preference-aware Edge VideoAnalytics Scheduler for Maximizing System Benefit"
authors: 
- admin 
- Hongzi Zhu
- Yunzhe Li 
- Jiangang Shen
- Minyi Guo
date: 2024-08-13T17:00:38+08:00
#doi: "10.1109/IPDPS49936.2021.00100"

# Schedule page publish date (NOT publication's date).
publishDate: 2024

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "53rd International Conference on Parallel Processing (ICPP)"
publication_short: "ICPP 2024"

abstract: "Video analytics is the killer workload in edge computing, which in-volves the scheduler’s complex decisions to balance analysis perfor-mance (latency and accuracy) and resource consumption (network,computation, and energy). Traditional schedulers address this as asingle-objective optimization problem with fixed weights, unableto precisely capture unknown system preferences due to intricatepricing rules across various service levels and resource costs, con-sequently leading to suboptimal system benefit like monetary gain. In this paper, we propose a Bayesian optimization-driven multi-objective scheduler, PaMO, that can proactively explore the systempricing preference by pairwise comparing outcome vectors of all ob-jectives. Moreover, PaMO designs a heuristic scheduling algorithmwith a zero-delay jitter guarantee to avoid performance degrada-tion caused by resource contention and uses a revised Bayesianoptimization algorithm to make video configuration and scheduling decisions. Experiments on real video analytics workloadsshow that PaMO can achieve up to 53.9% benefit gain compared tostate-of-the-art scheduling methods."

# Summary. An optional shortened abstract.
summary: "In this paper, we propose a Bayesian optimization-driven multi-objective scheduler, PaMO, that can proactively explore the systempricing preference by pairwise comparing outcome vectors of all ob-jectives. Moreover, PaMO designs a heuristic scheduling algorithmwith a zero-delay jitter guarantee to avoid performance degrada-tion caused by resource contention and uses a revised Bayesianoptimization algorithm to make video configuration and scheduling decisions."

tags: [edge computing]
categories: [edge computing]
featured: true

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf:
url_code:
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
