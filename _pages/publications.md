---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{https://scholar.google.com.hk/citations?hl=zh-CN&user=XXGhABIAAAAJ}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

- **Zeyu Wang**, Qitong Wang, Peng Wang, Themis Palpanas, and Wei Wang. *DumpyOS: A Data-Adaptive Multi-ary Index for Scalable Data Series Similarity Search*. VLDB Journal (under revision)

- **Zeyu Wang**, Zhenying He, Peng Wang, Yang Wang, and Wei Wang. *Static and Streaming Discovery of Maximal Linear Representation Between Time Series*. IEEE Transactions on Knowledge and Data Engineering (TKDE), vol. 36, no. 1, pp. 401-415, Jan. 2024. ([website](https://ieeexplore.ieee.org/abstract/document/10155259), [code](https://github.com/DSM-fudan/LR-miner))

- **Zeyu Wang**, Qitong Wang, Peng Wang, Themis Palpanas, and Wei Wang. *Dumpy: A Compact and Adaptive Index for Large Data Series Collections*. Proceedings of the ACM Management of Data (PACMMOD) Journal 1(1), 2023, presented at ACM SIG International conference on Management of Data / Principles of Database Systems (SIGMOD/PODS), Seattle, WA, USA, June 2023. ([PDF](https://helios2.mi.parisdescartes.fr/~themisp/publications/sigmod23-dumpy.pdf), [slides](https://helios2.mi.parisdescartes.fr/~themisp/publications/sigmod23-dumpy-slides.pdf), [video](https://files.atypon.com/acm/99f6febc21ad6c5a979f504caf188d9a), [code](https://github.com/DSM-fudan/Dumpy))

- **Zeyu Wang**, Peng Wang, Themis Palpanas, and Wei Wang. *Graph- and Tree-based Indexes for High-dimensional Vector Similarity Search: Analyses, Comparisons, and Future Directions*. IEEE Data Engineering Bulletin 47(3), Sep. 2023. ([PDF](http://sites.computer.org/debull/A23sept/p3.pdf))

- Hanbo Zhang, Peng Wang, Zicheng Fang, **Zeyu Wang**, and Wei Wang, *ELIS++: a shapelet learning approach for accurate and efficient time series classification*. World Wide Web 24, 511–539 March 2021. ([website](https://link.springer.com/article/10.1007/s11280-020-00856-1))
