+++
title = "A Deep Policy Inference Q-Network for Multi-Agent Systems"
date = 2018-07-10T00:00:00+08:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["**Tzu-Yun Shann**", "Zhang-Wei Hong", "Shih-Yang Su", "Yi-Hsiang Chang", "Chun-Yi Lee"]

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
publication = "International Conference on Autonomous Agents and Multiagent Systems"
publication_short = "AAMAS"

# Abstract and optional shortened version.
abstract = "We present DPIQN, a deep policy inference Q-network that targets multi-agent systems composed of controllable agents, collaborators, and opponents that interact with each other. We focus on one challenging issue in such systems---modeling agents with varying strategies---and propose to employ ``policy features'' learned from raw observations (e.g., raw images) of collaborators and opponents by inferring their policies. DPIQN incorporates the learned policy features as a hidden vector into its own deep Q-network (DQN), such that it is able to predict better Q values for the controllable agents than the state-of-the-art deep reinforcement learning models. We further propose an enhanced version of DPIQN, called deep recurrent policy inference Q-network (DRPIQN), for handling partial observability. Both DPIQN and DRPIQN are trained by an adaptive training procedure, which adjusts the network's attention to learn the policy features and its own Q-values at different phases of the training process. We present a comprehensive analysis of DPIQN and DRPIQN, and highlight their effectiveness and generalizability in various multi-agent settings. Our models are evaluated in a classic soccer game involving both competitive and collaborative scenarios. Experimental results performed on 1 vs. 1 and 2 vs. 2 games show that DPIQN and DRPIQN demonstrate superior performance to the baseline DQN and deep recurrent Q-network (DRQN) models. We also explore scenarios in which collaborators or opponents dynamically change their policies, and show that DPIQN and DRPIQN do lead to better overall performance in terms of stability and mean scores."
abstract_short = "We proposed a new method based on deep reinforcement learning for modeling collaborators/opponents in multi-agent systems."

# Featured image thumbnail (optional)
image_preview = "dpiqn.png"

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#   E.g. `projects = ["deep-learning"]` references `content/project/deep-learning.md`.
projects = []

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []

# Links (optional).
url_pdf = "pdf/aamas-2018-dpiqn.pdf"
url_preprint = "https://arxiv.org/abs/1712.07893"
url_code = "https://github.com/williamd4112/infer-policy-feature"
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""
#url_bib = [{name = "Bibtex", url = "\{\{\< relref "dpiqn.md#bibtex" \>\}\}"}]

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

# Bibtex
```tex
@article{hong2018dpiqn,
  title={A Deep Policy Inference Q-Network for Multi-Agent Systems},
  author={Hong, Zhang-Wei and Su, Shih-Yang and Shann, Tzu-Yun and Chang, Yi-Hsiang and Lee, Chun-Yi},
  journal={arXiv preprint arXiv:1712.07893},
  year={2018}
}
```


