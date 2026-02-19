---
layout: page # Misma estética que Inicio.
title: Artículos y noticias # Título.
permalink: /articulos-y-noticias/ # URL.
---

<section class="section">
  <h2>Artículos</h2>
  <div class="post-grid">
    {% for post in site.posts %}
      {% include post-card.html post=post %}
    {% endfor %}
  </div>
</section>
