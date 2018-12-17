---
title: Accueil
---
# Accueil

## À propos de moi
  * J'ai 20 ans
  * Je vis à Lannion
  * Je suis alternant en Licence Pro Développement Web et Mobile
  * Mon alternance se passe à Rennes, chez [CYIM](https://www.cyim.com/)

## Mes articles
  {% for post in site.posts %}
  * {{ post.title }}[{{ post.title }}]({{ post.url }})
  {% endfor %}
