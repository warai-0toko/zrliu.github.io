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

## Preprints


<b>[Mitigating Gender Bias in Captioning Systems](https://arxiv.org/abs/2006.08315)</b><br>Ruixiang Tang, Mengnan Du, Yuening Li, <b>Zirui Liu</b> and Xia Hu.
