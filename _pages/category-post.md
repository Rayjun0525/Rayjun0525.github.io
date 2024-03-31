---
title: "TEST01"
layout: archive
permalink: /post
sidebar:
  nav: "sidebar-navigation"
---

{% assign posts = site.categories.post %}
{% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}