---
layout: default
title: Home
---

# Welcome to My Personal Website

Hello! I'm Michelle, passionate about risk management. Click [About Me](https://michelleziqi.github.io/about%20me/) to get more details.

Below are some of my projects.

{% for post in site.posts %}
  <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
  <p>{{ post.excerpt }}</p>
{% endfor %}

