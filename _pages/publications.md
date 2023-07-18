---
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

# Publications
(*=equal contribution)
## Journals
- **Jiacheng Lin**, Lijun Wu, Jinhua Zhu, Xiaobo Liang, Yingce Xia, Shufang Xie, Tao Qin and Tie-Yan Liu, R<sup>2</sup>-DDI: Relation-aware Feature Refinement for Drug-Drug Interaction Prediction, Briefings in Bioinformatics.[[PDF]](https://academic.oup.com/bib/advance-article/doi/10.1093/bib/bbac576/6961471?utm_source=authortollfreelink&utm_campaign=bib&utm_medium=email&guestAccessKey=189b0995-bc41-40fc-b625-bf34b44ff21e&login=true)[[CODE]](https://github.com/linjc16/R2-DDI)
- **Jiacheng Lin**, Jialin Zhu, Huangang Wang and Tao Zhang, Learning to branch with Tree-aware Branching Transformers, Knowledge-Based Systems, Volume 252, 2022, 109455, ISSN 0950-7051. [[PDF]](https://www.sciencedirect.com/science/article/pii/S0950705122007298)[[CODE]](https://github.com/linjc16/TBranT)
## Conferences
- **Jiacheng Lin**∗, Hanwen Xu∗, Addie Woicik, Jianzhu Ma and Sheng Wang, Pisces: A cross-modal contrastive learning approach to synergistic drug combination prediction, RECOMB, 2023. [[PDF]](https://www.biorxiv.org/content/10.1101/2022.11.21.517439v1)[[CODE]](https://github.com/linjc16/Pisces)
