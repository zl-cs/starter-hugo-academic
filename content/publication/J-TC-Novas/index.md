---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Novas: Tackling Online Dynamic Video Analytics with Service Adaptation at Mobile Edge Servers"
authors: 
- admin 
- Hongzi Zhu
- Fei Wen
- Yunzhe Li
- Mingjin Zhang
- Jiannong Cao
- Minyi Guo
#date: 2021-09-13T17:00:38+08:00
doi: "10.1109/TC.2024.3416675"

# Schedule page publish date (NOT publication's date).
publishDate: 2024

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Transactions on Computers （TC）"
publication_short: "TC 2024"

abstract: "Video analytics at mobile edge servers offers signif-icant  benefits like  reduced response  time  and enhanced  privacy.However,  guaranteeing  various  quality-of-service  (QoS)  require-ments of dynamic video analysis requests on heterogeneous edgedevices remains challenging. In this paper, we propose a scalableonline video analytics scheme, called Novas, which automaticallymakes  precise  service  configuration  adjustments  upon  constantvideo  content  changes.  Specifically,  Novas  leverages  the  filteredconfidence sum and a two-window t-test to online detect accuracyfluctuations  without  ground  truth  information.  In  such  cases, Novas   efficiently   estimates   the   performance   of   all   potentialservice  configurations  through  a  singular  value  decomposition(SVD)-based  collaborative  filtering  method.  Finally,  given  theNP-hardness   of   the   optimal   scheduling   problem,   a   heuristicscheduling   strategy   that   maximizes   the   minimum   remainingresources is devised to schedule the most suitable configurationsto  servers  for  execution.  We  evaluate  the  effectiveness  of  Novasthrough extensive hybrid experiments conducted on a dedicatedtestbed.   Results   show   that   Novas   can   achieve   a   substantialover  27×improvement  in  satisfying  the  accuracy  requirementscompared  with  existing  methods  adopting  fixed  configurations,while ensuring latency requirements. Moreover, Novas improvesthe  goodput  of  the  system  by  an  average  of  37.86%  comparedto  existing  state-of-the-art  scheduling  solutions."

# Summary. An optional shortened abstract.
summary: "In this paper, we propose a scalableonline video analytics scheme, called Novas, which automaticallymakes  precise  service  configuration  adjustments  upon  constantvideo  content  changes.  Specifically,  Novas  leverages  the  filteredconfidence sum and a two-window t-test to online detect accuracyfluctuations  without  ground  truth  information.  In  such  cases, Novas   efficiently   estimates   the   performance   of   all   potentialservice  configurations  through  a  singular  value  decomposition(SVD)-based  collaborative  filtering  method.  Finally,  given  theNP-hardness   of   the   optimal   scheduling   problem,   a   heuristicscheduling   strategy   that   maximizes   the   minimum   remainingresources is devised to schedule the most suitable configurationsto  servers  for  execution."

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
