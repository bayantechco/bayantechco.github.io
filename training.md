---
layout: page
title: Nos Formations
permalink: /training/
---

<div class="posts">
  {% for training in site.trainings %}
    <article class="post">

      <h1><a href="{{ site.baseurl }}{{ training.url }}">{{ training.title }}</a></h1>
      <a href="{{ site.baseurl }}{{ training.url }}" class="read-more">Read More</a>
    </article>
{% endfor %}
</div>