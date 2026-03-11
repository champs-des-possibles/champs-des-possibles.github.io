---
layout: home
title: Urgence Environementale et ESR
---

## Objectifs 🌱

Le collectif est dédié aux reflexions et actions liés à l'urgence environnementale dans le contexte des établissement d'enseignement supérieur et de recherche de Champs-sur-Marne.


## Links

- [Ressources](ressources)


# Posts

{% for post in site.posts %}
- {{ post.date | date: "%Y-%m-%d" }}  {{ post.title }}
{% endfor %}







