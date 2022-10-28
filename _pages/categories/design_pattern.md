---
title: "디자인 패턴 (with C++)"
layout: archive
permalink: categories/design_pattern
author_profile: true
custom_sidebar: true
---

<!-- 공백이 포함되어 있는 카테고리 이름의 경우 site.categories.['a b c'] 이런식으로! -->

{% assign posts = site.categories.['Design Pattern'] %}
{% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}