---
layout: single
title: Recent Posts
permalink: /blog/
classes: wide
author: Ashley Farrar
author_profile: true
---
{% for post in site.posts limit:3 %}
{% endfor %}
