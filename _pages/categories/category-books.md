---
title: "Books"
layout: archive
permalink: /books
author_profile: true
types: posts
sidebar:
  nav: "docs"
---

{% assign posts = site.categories['books']%}
{% for post in posts %}
  {% include archive-single.html type=page.entries_layout %}
{% endfor %}
