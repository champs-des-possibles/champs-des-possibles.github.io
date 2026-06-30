---
layout: home
title: Liste de ressources pertinentes
---
# Évènements à venir
{% for post in site.posts %}
- <span class="post-date">{{ post.date | date: "%Y-%m-%d" }}</span> <a href="{{ post.url }}">{{ post.title }}</a>
{% endfor %}


