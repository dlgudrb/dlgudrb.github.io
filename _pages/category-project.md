---
title: "Projects"
layout: archive
permalink: /project
author_profile: true
---


{% assign posts = site.categories.project %}
{% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}
