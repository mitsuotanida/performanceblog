---
layout: page
title: Contacto
permalink: /contacto/
---

<p class="lead">Escribime y te respondo. Si querés, también podés proponer tema para un artículo.</p>

<form class="form" action="https://formspree.io/f/TU_ID" method="POST">
  <div class="field">
    <label for="name">Nombre</label>
    <input id="name" name="name" type="text" required />
  </div>

  <div class="field">
    <label for="phone">Teléfono</label>
    <input id="phone" name="phone" type="tel" />
  </div>

  <div class="field">
    <label for="email">Mail</label>
    <input id="email" name="email" type="email" required />
  </div>

  <div class="field full">
    <label for="message">Mensaje</label>
    <textarea id="message" name="message" required></textarea>
  </div>

  <div class="field full">
    <button class="btn btn-primary" type="submit">Enviar</button>
  </div>
</form>
