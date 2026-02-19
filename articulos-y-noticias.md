---
layout: page # Usa el layout "page" para verse igual que Inicio.
title: Artículos y noticias # Título de la página.
permalink: /articulos-y-noticias/ # URL fija.
---

## Artículos

{% for post in site.posts %}
  {% include post-card.html post=post %} <!-- Inserta una tarjeta por cada post. -->
{% endfor %}
