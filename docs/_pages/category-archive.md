---
title: "Posts by Category"
layout: categories
permalink: /categories/
author_profile: true
---


{% assign posts = site.categories.diraty %}
{% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}
