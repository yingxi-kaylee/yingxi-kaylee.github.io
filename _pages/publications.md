---
layout: archive
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

* [eSCAN: Scan Regulatory Regions for Aggregate Association Testing using Whole Genome Sequencing Data](https://academic.oup.com/bib/article-abstract/23/1/bbab497/6457165?redirectedFrom=fulltext)

  **Yingxi Yang**, Yuchen Yang, Le Huang, Jai G. Broome, Adolfo Correa, Alexander Reiner, NHLBI Trans-Omics for Precision Medicine (TOPMed) Consortium, Laura M. Raffield, Yun Li
  
  *Briefings in Bioinformatics, December 2021*
  
* [iSMNN: batch effect correction for single-cell RNA-seq data via iterative supervised mutual nearest neighbor refinement](https://pubmed.ncbi.nlm.nih.gov/33839756/)

  Yuchen Yang, Gang Li, Yifang Xie, Li Wang, Taylor M. Lagler, **Yingxi Yang**, Jiandong Liu, Li Qian, Yun Li
  
  *Briefings in Bioinformatics, April 2021*

