---
title: "Git"
permalink: categories/Git

layout: archive
author_profile: true
sidebar_main: true
classes: wide
---

{% assign posts = site.categories.Blog %}
{% for post in posts %} {% include archive-single2.html type=page.entries_layout %} {% endfor %}