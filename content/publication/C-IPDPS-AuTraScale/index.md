---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "AuTraScale: An Automated and Transfer Learning Solution for Streaming System Auto-Scaling"
authors: 
- admin 
- Zheng Wenli
- Li Chao 
- Shen Yao
- Guo Minyi
date: 2021-09-13T17:00:38+08:00
doi: "10.1109/IPDPS49936.2021.00100"

# Schedule page publish date (NOT publication's date).
publishDate: 2021

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "2021 IEEE International Parallel and Distributed Processing Symposium"
publication_short: "IPDPS 2021"

abstract: "The complexity and variability of streaming data have brought a great challenge to the elasticity of the data processing systems. Streaming systems, such as Flink and Storm, need to adapt to the changes of workload with auto-scaling to meet the QoS requirements while saving resources. However, the accuracy of classical models (such as a queueing model) for QoS prediction decreases with the increase of the complexity and variability of streaming data and the resource interference. On the other hand, the indirect metrics used to optimize QoS may not accurately guide resource adjustment. Those problems can easily lead to waste of resources or QoS violation in practice. To solve the above problems, we propose AuTraScale, an automated and transfer learning auto-scaling solution, to determine the appropriate parallelism and resource allocation that meet the latency and throughput targets. AuTraScale uses Bayesian optimization to adapt to the complex relationship between resources and QoS, minimizing the impact of resource interference on the prediction accuracy, and a new metric that measures the performance of operators for accurate optimization. Even when the input data rate changes, it can quickly adjust the parallelism of each operator in response, with a transfer learning algorithm. We have implemented and evaluated AuTraScale on a Flink platform. The experimental results show that, compared with the state-of-the-art method like DRS and DS2, AuTraScale can reduce 66.6% and 36.7% resource consumption respectively in the scale-down and scale-up scenarios while ensuring QoS requirements, and save 13.5% resource on average when the input data rate changes."

# Summary. An optional shortened abstract.
summary: "In this paper, we propose AuTraScale, an automated and transfer learning auto-scaling solution, to determine the appropriate parallelism and resource allocation that meet the latency and throughput targets. AuTraScale uses Bayesian optimization to adapt to the complex relationship between resources and QoS, minimizing the impact of resource interference on the prediction accuracy, and a new metric that measures the performance of operators for accurate optimization. Even when the input data rate changes, it can quickly adjust the parallelism of each operator in response, with a transfer learning algorithm."

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
  preview_only: true

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
