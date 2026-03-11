---
layout: home
title: Urgence Environementale et ESR
---

## Objectifs 🌱

Le collectif est dédié aux reflexions et actions liés à l'urgence environnementale dans le contexte des établissement d'enseignement supérieur et de recherche de Champs-sur-Marne.


## Prochain RDV

Pas encore planifié!

## News

{% for post in site.posts %}
- <span class="post-date">{{ post.date | date: "%Y-%m-%d" }}</span> <a href="{{ post.url }}">{{ post.title }}</a>
{% endfor %}











