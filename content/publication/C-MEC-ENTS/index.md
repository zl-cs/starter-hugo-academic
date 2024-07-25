---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "ENTS: An Edge-native Task Scheduling System for Collaborative Edge Computing"
authors: 
- Mingjin Zhang 
- Jiannong Cao
- Lei Yang 
- admin
- Yuvraj Sahni
- Shan Jiang
date: 2022-09-13T17:00:38+08:00
doi: "10.1109/SEC54971.2022.00019"

# Schedule page publish date (NOT publication's date).
publishDate: 2021

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "2022 IEEE/ACM 7th Symposium on Edge Computing (SEC)"
publication_short: "SEC 2022"

abstract: "Collaborative edge computing (CEC) is an emerging paradigm enabling sharing of the coupled data, computation, and networking resources among heterogeneous geo-distributed edge nodes. Recently, there has been a trend to orchestrate and schedule containerized application workloads in CEC, while Kubernetes has become the de-facto standard broadly adopted by the industry and academia. However, Kubernetes is not preferable for CEC because its design is not dedicated to edge computing and neglects the unique features of edge nativeness. More specifically, Kubernetes primarily ensures resource provision of workloads while neglecting the performance requirements of edge-native applications, such as throughput and latency. Furthermore, Kubernetes neglects the inner dependencies of edge-native applications and fails to consider data locality and networking resources, leading to inferior performance. In this work, we design and develop ENTS, the first edge-native task scheduling system, to manage the distributed edge resources and facilitate efficient task scheduling to optimize the performance of edge-native applications. ENTS extends Kubernetes with the unique ability to collaboratively schedule computation and networking resources by comprehensively considering job profile and resource status. We showcase the superior efficacy of ENTS with a case study on data streaming applications. We mathematically formulate a joint task allocation and flow scheduling problem that maximizes the job throughput. We design two novel online scheduling algorithms to optimally decide the task allocation, bandwidth allocation, and flow routing policies. The extensive experiments on a real-world edge video analytics application show that ENTS achieves 43% -220% higher average job throughput compared with the state-of-the-art."

# Summary. An optional shortened abstract.
summary: "In this work, we design and develop ENTS, the first edge-native task scheduling system, to manage the distributed edge resources and facilitate efficient task scheduling to optimize the performance of edge-native applications. ENTS extends Kubernetes with the unique ability to collaboratively schedule computation and networking resources by comprehensively considering job profile and resource status."

tags: [edge computing]
categories: [edge computing]
featured: false

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
