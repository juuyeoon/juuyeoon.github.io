---
title: "Conference"
layout: archive
permalink: /conf
author_profile: true
types: posts
sidebar:
  nav: "docs"
---

{% assign posts = site.categories['conf']%}
{% for post in posts %}
  {% include archive-single.html type=page.entries_layout %}
{% endfor %}
