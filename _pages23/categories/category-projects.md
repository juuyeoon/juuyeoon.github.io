---
title: "Projects"
layout: archive
permalink: categories/projects
author_profile: true
types: posts
sidebar:
  nav: "docs"
---

{% assign posts = site.categories['projects']%}
{% for post in posts %}
  {% include archive-single.html type=page.entries_layout %}
{% endfor %}
