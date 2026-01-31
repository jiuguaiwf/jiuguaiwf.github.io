---
layout: archive
permalink: /publications/
author_profile: true
redirect_from:
  - /resume
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

Publications
====

- *A Paper about Corrective Inference for 3D Molecular Diffusion Generation.*  
  **F.Wan**, W.Gao, J.Qu, Y.Liu.  
  *Under Review*, ICML 2026.

- *A Paper on Uncertainty in Diffusion-Based 3D Molecular Generation.*  
  **F.Wan**, J.Qu, Y.Liu.  
  *Under Review*, KDD 2026.

- *Can Data-Driven Dynamics Reveal Hidden Physics? There Is a Need for Interpretable Neural Operators.*  
  W.Gao, J.Luo, **F.Wan**, R.Xu, X.Liu, H.Xing, Y.Liu.  
  *In Submission.*
