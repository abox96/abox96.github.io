---
title: "markdown"
layout: archive
permalink: /CategoryA
---


{% assign posts = site.categories.CategroyA %}
{% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}
