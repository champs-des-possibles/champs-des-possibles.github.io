---
layout: home
title: Évènements à venir
---

# Évenements à venir
{% assign sorted_posts = site.posts | sort: "date" %}
{% for post in sorted_posts %}
- <span class="post-date">{{ post.date_display }}</span> <a href="{{ post.url }}">{{ post.title }}</a>
{% endfor %}


