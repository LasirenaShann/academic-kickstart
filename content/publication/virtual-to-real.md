+++
title = "Virtual to Real: Learning to Control in Visual Semantic Segmentation"
date = 2018-04-10T00:04:55+08:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Zhang-Wei Hong", "Yu-Ming Chen", "Hsuan-Kung Yang", "Shih-Yang Su", "**Tzu-Yun Shann**", "Yi-Hsiang Chang", "Brian Hsi-Lin Ho", "Chih-Chieh Tu", "Tzu-Ching Hsiao", "Hsin-Wei Hsiao", "Sih-Pin Lai", "Yueh-Chuan Chang", "Chun-Yi Lee"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["1"]

# Publication name and optional abbreviated version.
publication = "International Joint Conference on Artificial Intelligence"
publication_short = "IJCAI"

# Abstract and optional shortened version.
abstract = "Collecting training data from the physical world is usually time-consuming and even dangerous for fragile robots, and thus, recent advances in robot learning advocate the use of simulators as the training platform. Unfortunately, the reality gap between synthetic and real visual data prohibits direct migration of the models trained in virtual worlds to the real world. This paper proposes a modular architecture for tackling the virtual-to-real problem. The proposed architecture separates the learning model into a perception module and a control policy module, and uses semantic image segmentation as the meta representation for relating these two modules.  The perception module translates the perceived RGB image to semantic image segmentation.  The control policy module is implemented as a deep reinforcement learning agent, which performs actions based on the translated image segmentation. Our architecture is evaluated in an obstacle avoidance task and a target following task.  Experimental results show that our architecture significantly outperforms all of the baseline methods in both virtual and real environments, and demonstrates a faster learning curve than them.  We also present a detailed analysis for a variety of variant configurations, and validate the transferability of our modular architecture."
abstract_short = "This paper proposes a modular architecture for tackling the virtual-to-real problem. The proposed architecture separates the learning model into a perception module and a control policy module, and uses semantic image segmentation as the meta representation for relating these two modules to bridge the gap between synthetic and real visual data."

# Featured image thumbnail (optional)
image_preview = "ijcai.png"

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#   E.g. `projects = ["deep-learning"]` references `content/project/deep-learning.md`.
projects = []

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["Reinforcement Learning", "Computer Vision", "Robotics", "Segmentation", "Sim-to-Real"]

# Links (optional).
url_pdf = "pdf/ijcai-2018-virtual.pdf"
url_preprint = "https://arxiv.org/abs/1802.00285"
url_code = ""
url_dataset = ""
url_project = ""
url_slides = ""
url_video = "https://goo.gl/gdqcB8"
url_poster = ""
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Does this page contain LaTeX math? (true/false)
math = false

# Does this page require source code highlighting? (true/false)
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = ""
caption = ""

+++

## Bibtex
```tex
@inproceedings{hong2018virtual,
  title={Virtual to Real: Learning to Control in Visual Semantic Segmentation},
  author={Hong, Zhang-Wei and Chen, Yu-Min and Yang, Hsuan-Kung and Su, Shih-Yang and Shann, Tzu-Yun and Chang, Yi-Hsiang and Ho, Brian Hsi-Lin and Tu, Chih-Chieh and Lai, Sih-Pin and Chang, Yueh-Chuan and Lee, Chun-Yi},
  booktitle={Proc. Int. Joint Conf. Artificial Intelligence (IJCAI)},
  month={Jul.},
  year={2018}
}
```
