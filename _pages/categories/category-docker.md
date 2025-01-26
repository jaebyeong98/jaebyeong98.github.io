---
title: "DOCKER"
layout: archive
permalink: categories/docker
author_profile: true
types: posts
---

{% assign posts = site.categories['Docker']%}
{% for post in posts %}
  {% include archive-single.html type=page.entries_layout %}
{% endfor %}