---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
## 2025 
- Dinc F., Blanco M., Klindt D., Acosta F., Jiang Y., Ebrahimi S., Shai A., Tanaka H., Yuan P., Schnitzer M., Miolane N., Latent computing by biological neural networks: A dynamical systems framework, *arxiv*. 2025. [paper](https://arxiv.org/pdf/2502.14337)

- Dinc F., Cirakman E., Jiang Y., Yuksekgonul M., Schnitzer M., Tanaka H., A ghost mechanism: An analytical model of abrupt learning, *arxiv*. 2025. [paper](https://arxiv.org/pdf/2501.02378)

## 2024
- **Jiang Y.**\*, Akengin H.\*, Aslihak M.\*,  Miranda C., Pozo M., Hernandez O., Inan H., Dinc F., Schnitzer M., ActSort: An Active-learning Accelerated Cell Sorting Algorithm for Large-Scale Calcium Imaging, In *Advances in Neural Information Processing Systems*. 2024. [paper](https://papers.nips.cc/paper_files/paper/2024/hash/90080022263cddafddd4a0726f1fb186-Abstract-Conference.html) [slides]()

- **Jiang Y.**\*, Sheng K.\*, Woo S., Shikano Y., Zhao Y., Zhang C., Linderman S., Schnitzer M., sa-SVAE: a Shared and Aligned Structured Variational Autoencoder for Extracting Behaviorally Relevant and Preserved Neural Dynamics Across Animals, In *NeurIPS 2024 Workshop on Symmetry and Geometry in Neural Representations*. 2024.

- Haputhanthri U., Storan L., **Jiang Y.**, Shai A., Akengin H., Schnitzer M., Dinc F., Tanaka H., Why do recurrent neural networks suddenly learn? Bifurcation mechanisms in neuro-inspired short-term memory tasks, In *ICML 2024 Workshop on Mechanistic Interpretability*. 2024. [paper](https://openreview.net/pdf?id=njmXdqzHJq)

## 2023
- Sun J., **Jiang Y.**, Qiu J., Nobel P., Kochenderfer M., Schwager M., Conformal Prediction for Uncertainty-Aware Planning with Diffusion Dynamic Model, In *Advances in Neural Information Processing Systems*. 2023. [paper](https://proceedings.neurips.cc/paper_files/paper/2023/file/fe318a2b6c699808019a456b706cd845-Paper-Conference.pdf)

<div style='display: none'>
{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
</div>