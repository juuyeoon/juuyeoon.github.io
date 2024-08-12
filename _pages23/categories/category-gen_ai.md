---
title: "Generative AI"
layout: archive
permalink: /gen_ai
author_profile: true
types: posts
sidebar:
  nav: "docs"
---

{% assign posts = site.categories.gen_ai%}
{% for post in posts %}
  {% include archive-single.html type=page.entries_layout %}
{% endfor %}
