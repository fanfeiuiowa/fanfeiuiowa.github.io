---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

## Jornal Papers
1. [Study of Droplet Diffusion in Hydrothermal-Assisted Transient Jet Fusion of Ceramics](https://asmedigitalcollection.asme.org/manufacturingscience/article-abstract/143/5/051001/1086995/Study-of-Droplet-Diffusion-in-Hydrothermal?redirectedFrom=fulltext)<br/>
**Fan Fei**, Li He, Levi Kirby, Xuan Song. *Journal of Manufacturing Science and Engineering*, 2021.
2. [Cephalopod‐Inspired Stretchable Self‐Morphing Skin Via Embedded Printing and Twisted Spiral Artificial Muscles](https://onlinelibrary.wiley.com/doi/abs/10.1002/adfm.202105528)<br/>
**Fan Fei**, Parth Kotak, Li He, Xiaofeng Li, Cyan Vanderhoef, Caterina Lamuta, Xuan Song. *Advanced Functional Materials*, 2021.
3. [Rat Calvarial Bone Regeneration by 3d-Printed Β-Tricalcium Phosphate Incorporating Microrna-200c](https://pubs.acs.org/doi/abs/10.1021/acsbiomaterials.0c01756)<br/>
Matthew T. Remy, Adil Akkouch, Li He, Steven Eliason, Mason E. Sweat, Tadkamol Krongbaramee, **Fan Fei**, Fang Qian, Brad A. Amendt, Xuan Song, and Liu Hong. *ACS biomaterials science & engineering*, 2021
4. [Hydrothermal-Assisted Transient Binder Jetting of Ceramics for Achieving High Green Density](https://link.springer.com/article/10.1007/s11837-019-03962-2)<br/>
**Fan Fei**, Li He, Baizhuang Zhou, Ziyang Xu, Xuan Song. *JOM*, 2020.
5. [Support-free ceramic stereolithography of complex overhanging structures based on an elasto-viscoplastic suspension feedstock](https://pubs.acs.org/doi/abs/10.1021/acsami.9b04205)<br/>
Li He, **Fan Fei**, Wenbo Wang, and Xuan Song. *ACS applied materials & interfaces*, 2019.

## Conference Proceedings
1. [Hydrothermal Assisted Transient Jet Fusion of Ceramics: A Test Case Using Bentonite Clay](https://www.sciencedirect.com/science/article/pii/S2351978920315687)<br/>
Levi Kirby, **Fan Fei**, Chao Wang, Xuan Song. *Procedia Manufacturing*, 2020.
2. [Layerless Additive Manufacturing of Metal Alloy Lattices Using Immiscible-Interface Assisted Direct Metal Drawing](https://www.sciencedirect.com/science/article/pii/S2351978919308340)<br/>
Li He, **Fan Fei**, Wenbo Wang, and Xuan Song. *Procedia Manufacturing*, 2019.
3. [Predicting manufactured shapes of a projection micro-stereolithography process via convolutional encoder-decoder networks](https://asmedigitalcollection.asme.org/IDETC-CIE/proceedings-abstract/IDETC-CIE2018/V01BT02A033/273569)<br/>
Yusen He, **Fan Fei**, Wenbo Wang, Xuan Song, Zhiyu Sun, Stephen Baek. *International Design Engineering Technical Conferences and Computers and Information in Engineering Conference*, 2018.

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
