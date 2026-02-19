---
layout: page
title: Contacto
permalink: /contacto/
---

<p class="lead">Escribime y te respondo. Si querés publicar en Performance Labs, elegí “Quiero publicar un artículo”.</p>

<form
  class="contact-form"
  action="https://formspree.io/f/maqddeed"
  method="POST"
>
  <!-- action = la dirección a la que mandamos el formulario (Formspree). -->

  <label>
    Nombre
    <input type="text" name="nombre" required />
    <!-- name="nombre" es la etiqueta que verá Formspree en el mail. -->
  </label>

  <label>
    Teléfono
    <input type="tel" name="telefono" />
  </label>

  <label>
    Email
    <input type="email" name="email" required />
  </label>

  <label>
    Motivo
    <select name="motivo" required>
      <option value="" disabled selected>Elegí una opción</option>
      <option value="publicar">Quiero publicar un artículo</option>
      <option value="asesoria">Quiero asesoría/consultoría</option>
      <option value="otro">Otro</option>
    </select>
    <!-- Esto te permite filtrar rápido cuando te llega el mail. -->
  </label>

  <label>
    Mensaje
    <textarea name="mensaje" rows="6" required></textarea>
  </label>

  <!-- Anti-spam simple (honeypot): si un bot lo llena, lo podés ignorar -->
  <input type="text" name="_gotcha" style="display:none" />

  <!-- Personaliza el asunto del mail que te llega -->
  <input type="hidden" name="_subject" value="Nuevo contacto en Performance Labs" />

  <!-- A dónde redirigir después de enviar -->
  <input type="hidden" name="_next" value="/performanceblog/gracias/" />
  <!-- OJO: tu sitio está en /performanceblog/, por eso lo ponemos así. -->

  <button class="btn btn-primary" type="submit">Enviar</button>
</form>
