---
layout: page
title: Artículos y noticias
permalink: /articulos-y-noticias/
---

<section class="section">
  <h2>Artículos</h2>
  <div class="post-grid">
    {% for post in site.posts %}
      {% include post-card.html post=post %}
    {% endfor %}
  </div>
</section>
