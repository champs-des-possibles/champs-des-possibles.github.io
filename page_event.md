---
layout: home
title: Évènements à venir
---
# Évènements à venir
{% for post in site.posts %}
- <span class="post-date">{{ post.date | date: "%d %B %Y" }}</span> <a href="{{ post.url }}">{{ post.title }}</a>
{% endfor %}


