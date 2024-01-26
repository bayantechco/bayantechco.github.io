---
layout: page
title: Nos Formations
permalink: /training/
---

{% assign pages = site.trainings | where_exp: 'page', 'page.title' %}
{% for page in pages %}
title: {{page.title}}
{% endfor %}