---
title: "Post"
layout: archive
permalink: /post
author_profile: true
sidebar:
    nav: "sidebar-category"
---


{% assign posts = site.categories.post %}
{% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}