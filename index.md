---
title: Accueil
---
# Accueil

## À propos de moi
  * J'ai 20 ans
  * Je vis à Lannion
  * Je suis alternant en Licence Pro Développement Web et Mobile
  * Mon alternance se passe à Rennes, chez [CYIM](https://www.cyim.com/)

### Découvrez-en plus sur moi
Grâce à mon [site personnel officiel](https://mathieusteinmetz.fr), ou ma page [CV](cv.html)
## Mes articles
{% for post in site.posts %}
### [{{ post.title }}]({{ post.url }})
{{post.excerpt}}
---
{% endfor %}
