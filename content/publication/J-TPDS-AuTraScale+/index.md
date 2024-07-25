---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Bayesian-Driven Automated Scaling in Stream Computing with Multiple QoS Targets"
authors: 
- admin 
- Wenli Zheng
- Kuangyu Zheng
- Hongzi Zhu
- Chao Li
- Minyi Guo
#date: 2021-09-13T17:00:38+08:00
doi: "10.1109/TPDS.2024.3399834"

# Schedule page publish date (NOT publication's date).
publishDate: 2024

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Transactions on Parallel and Distributed Systems（TPDS）"
publication_short: "TPDS 2024"

abstract: "Stream processing systems commonly work withauto-scaling to ensure resource efficiency and quality of service(QoS). Existing auto-scaling solutions lack accuracy in resource al-location because they rely on static QoS-resource models that fail toaccount for high workload variability and use indirect metrics withmuch distractive information. Moreover, different types of QoSmetrics present different characteristics and thus need individualauto-scaling methods. In this paper, we propose a versatile auto-scaling solution for operator-level parallelism configuration, called AuTraScale+, to meet the throughput, processing-time latency,and event-time latency targets. AuTraScale+ follows the Bayesianoptimization framework to make scaling decisions. First, it usesthe Gaussian process model to eliminate the negative influenceof uncertain factors on the performance model accuracy. Second,it leverages the expected improvement-based (EI-based) acquisi-tion function to search and recommend the optimal configurationquickly. Besides, to make a more accurate scaling decision when thenew model is not ready, AuTraScale+ proposes a transfer learningalgorithm to estimate the benefits of all configurations at a newrate based on existing models and then recommend the optimalone. We implement and evaluate AuTraScale+ on the Flink plat-form. The experimental results on three representative workloadsdemonstrate that compared with the state-of-the-art methods, Au-TraScale+ can reduce 66.6% and 36.7% resource consumption, re-spectively, in the scale-down and scale-up scenarios while achievingtheir throughput and processing-time latency targets. Comparedwith other methods of optimizing event-time latency, AuTraScale+saves 26.9% of resources on average."

# Summary. An optional shortened abstract.
summary: "In this paper, we propose a versatile auto-scaling solution for operator-level parallelism configuration, called AuTraScale+, to meet the throughput, processing-time latency,and event-time latency targets. AuTraScale+ follows the Bayesian optimization framework to make scaling decisions. First, it usesthe Gaussian process model to eliminate the negative influenceof uncertain factors on the performance model accuracy. Second,it leverages the expected improvement-based (EI-based) acquisition function to search and recommend the optimal configuration quickly. Besides, to make a more accurate scaling decision when the new model is not ready, AuTraScale+ proposes a transfer learningalgorithm to estimate the benefits of all configurations at a newrate based on existing models and then recommend the optimal one."

tags: [stream computing]
categories: [stream computing]
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
