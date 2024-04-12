---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

## 2023
- Sun J., **Jiang Y.**, Qiu J., Nobel P., Kochenderfer M., Schwager M., Conformal Prediction for Uncertainty-Aware Planning with Diffusion Dynamic Model, In *Advances in Neural Information Processing Systems*. 2023.

- Akengin H.\*, Aslihak M.\*, **Jiang Y.**\*, Miranda C., Pozo M., Hernandez O., Inan H., Dinc F., Schnitzer M., ActSort: An Active-learning Accelerated Cell Sorting Algorithm for Large-Scale Calcium Imaging, In *Advances in Neural Information Processing Systems Workshop on Adaptive Experimental Design and Active Learning in the Real World*. 2023.

<div style='display: none'>
{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
</div>