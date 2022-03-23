---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
<img style="float: right;" src="mentalhealth.jpg">
### 1. [The COVID-19 Pandemic and Mental Health Concerns on Twitter in the United States](https://spj.sciencemag.org/journals/hds/2022/9758408/)

Senqi Zhang*, Li Sun*, Daiwei Zhang, Pin Li, Yue Liu, Zidian Xie, Dongmei Li


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
