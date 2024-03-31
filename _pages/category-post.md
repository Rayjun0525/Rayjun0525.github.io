---
title: "TEST01"
layout: archive
permalink: /post
author_profile: true
---

{% assign posts = site.categories.post %}
{% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}