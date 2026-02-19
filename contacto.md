---
layout: page
title: Contacto
permalink: /contacto/
---

<p class="lead">
  Escribime y te respondo. Si querés publicar en Performance Labs, elegí “Quiero publicar un artículo”.
</p>

<div class="contact-card">
  <!-- contact-card = una “tarjeta” que envuelve el formulario para que se vea prolijo. -->

  <form class="contact-form" action="https://formspree.io/f/maqddeed" method="POST">
    <!-- contact-form = la clase que vamos a estilizar para que todo quede en columna. -->
    <div class="field">
      <label for="nombre">Nombre</label>
      <input id="nombre" type="text" name="nombre" required />
    </div> <!-- field = bloque de un campo (label + input). -->
    <div class="field">
      <label for="telefono">Teléfono</label>
      <input id="telefono" type="tel" name="telefono" />
    </div> <!-- field = bloque de un campo. -->
    <div class="field">
      <label for="email">Email</label>
      <input id="email" type="email" name="email" required />
    </div> <!-- field = bloque de un campo. -->
    <div class="field">
      <label for="motivo">Motivo</label>
      <select id="motivo" name="motivo" required>
        <option value="" disabled selected>Elegí una opción</option>
        <option value="publicar">Quiero publicar un artículo</option>
        <option value="asesoria">Quiero asesoría/consultoría</option>
        <option value="otro">Otro</option>
      </select>
    </div> <!-- field = bloque de un campo. -->
    <div class="field">
      <label for="mensaje">Mensaje</label>
      <textarea id="mensaje" name="mensaje" rows="6" required></textarea>
    </div> <!-- field = bloque de un campo. -->
    <input type="text" name="_gotcha" class="hp" />
    <!-- hp = “trampa” anti-spam; humanos no la ven, bots a veces la llenan. -->
    <input type="hidden" name="_subject" value="Nuevo contacto en Performance Labs" />
    <!-- _subject = el asunto del mail que te llega. -->
    <input type="hidden" name="_next" value="/performanceblog/gracias/" />
    <!-- _next = a dónde redirige cuando envían el formulario. -->
    <div class="actions">
      <button class="btn btn-primary" type="submit">Enviar</button>
    </div> <!-- actions = bloque para ubicar el botón bien. -->

  </form>
</div>
