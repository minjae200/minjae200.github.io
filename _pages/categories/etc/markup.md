---
title: "Markup Language"
layout: archive
permalink: categories/markup
author_profile: true
custom_sidebar: true
---

{% assign posts = site.categories.Markup %}
{% for post in posts %} {% include archive-single2.html type=page.entries_layout %} {% endfor %}