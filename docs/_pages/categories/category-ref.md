---
title: "ref"
layout: archive
permalink: /ref
author_profile: true
---


{% assign posts = site.categories.ref %}
{% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}
