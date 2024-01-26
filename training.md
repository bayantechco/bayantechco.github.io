---
layout: page
title: Nos Formations
permalink: /training/
---

{% assign folder1 = site.pages | where_exp: "item" , "item.path contains 'training'"%}
{% for item in folder1 %}
{{item.title}}
{% endfor %}