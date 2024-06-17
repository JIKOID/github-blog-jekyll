---
title: "프로그래밍 언어 - Python"
layout: archive
permalink: /categories/programming/python/
author_profile: true
sidebar_category: true
---

{% assign posts = site.categories.python %}
{% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}