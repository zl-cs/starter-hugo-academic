---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Anole: Adapting Diverse Compressed Models for Cross-scene Prediction on Mobile Devices"
authors: 
- Yunzhe Li
- Hongzi Zhu 
- Zhuohong Deng
- Yunlong Cheng
- admin
- Shan Chang
- Minyi Guo
#date: 2021-09-13T17:00:38+08:00
#doi: "10.1109/IPDPS49936.2021.00100"

# Schedule page publish date (NOT publication's date).
publishDate: 2024

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "44th IEEE International Conference on Distributed Computing Systems (ICDCS)"
publication_short: "ICDCS 2024"

abstract: "Emerging  Artificial  Intelligence  of  Things  (AIoT)applications  desire  online  prediction  using  deep  neural  network(DNN) models on mobile devices. However, due to the movementof devices,unfamiliartest samples constantly appear, significantlyaffecting   the   prediction   accuracy   of   a   pre-trained   DNN.   Inaddition,   unstable   network   connection   calls   for   local   modelinference. In this paper, we propose a light-weight scheme, calledAnole,  to  cope  with  the  local  DNN  model  inference  on  mobiledevices.  The  core  idea  of  Anole  is  to  first  establish  an  armyof  compact  DNN  models,  and  then  adaptively  select  the  modelfitting the current test sample best for online inference. The keyis  to  automatically  identifymodel-friendlyscenes  for  trainingscene-specific  DNN  models.  To  this  end,  we  design  a  weakly-supervised scene representation learning algorithm by combiningboth human heuristics and feature similarity in separating scenes.Moreover, we further train a model classifier to predict the best-fit scene-specific DNN model for each test sample. We implementAnole on different types of mobile devices and conduct extensivetrace-driven  and  real-world  experiments  based  on  unmannedaerial   vehicles   (UAVs).   The   results   demonstrate   that   Anoleoutwits  the  method  of  using  a  versatile  large  DNN  in  terms  ofprediction accuracy (4.5% higher), response time (33.1% faster)and  power  consumption  (45.1%  lower)."

# Summary. An optional shortened abstract.
summary: "To  automatically  identify model-friendly scenes  for  training scene-specific  DNN  models,  we  design  a  weakly-supervised scene representation learning algorithm by combining both human heuristics and feature similarity in separating scenes. Moreover, we further train a model classifier to predict the best-fit scene-specific DNN model for each test sample."

tags: [edge AI]
categories: [edge AI]
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
