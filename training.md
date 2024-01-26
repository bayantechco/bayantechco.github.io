---
layout: page
title: Nos Formations
permalink: /training/
---

{% for page in site.trainings %}
    title: {{page.title}}
{% endfor %}