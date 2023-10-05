---
title: "🚀 Projects"
layout: archive
permalink: categories/project
author_profile: true
sidebar:
  nav: "sidebar-category"
---


{% assign posts = site.categories.project %}
{% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% include page__meta.html type=include.type %} {% endfor %}
