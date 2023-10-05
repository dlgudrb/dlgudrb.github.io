---
title: "📌 References"
layout: archive
permalink: categories/ref
author_profile: true
sidebar-category:
  nav: "sidebar-category"
---


{% assign posts = site.categories.ref %}
{% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}
