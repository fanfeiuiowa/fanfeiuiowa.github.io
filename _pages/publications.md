---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

## Jornal Papers
1. [Study of Droplet Diffusion in Hydrothermal-Assisted Transient Jet Fusion of Ceramics](https://asmedigitalcollection.asme.org/manufacturingscience/article-abstract/143/5/051001/1086995/Study-of-Droplet-Diffusion-in-Hydrothermal?redirectedFrom=fulltext)
Fan Fei, Li He, Levi Kirby, Xuan Song. *Journal of Manufacturing Science and Engineering* 143 (5), 051001, 2021
{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
