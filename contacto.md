---
layout: page
title: Contacto
permalink: /contacto/
---

<p class="lead">
  Si dirigís o coordinás un centro deportivo y querés ordenar tus datos, mejorar tu reportería o transformar contenido técnico en una herramienta comercial, escribime por acá.
</p>

<div class="contact-card">
  <form class="contact-form" action="https://formspree.io/f/maqddeed" method="POST">
    <div class="field">
      <label for="nombre">Nombre</label>
      <input id="nombre" type="text" name="nombre" required />
    </div>
    <div class="field">
      <label for="centro">Centro deportivo / academia</label>
      <input id="centro" type="text" name="centro" />
    </div>
    <div class="field">
      <label for="telefono">Teléfono</label>
      <input id="telefono" type="tel" name="telefono" />
    </div>
    <div class="field">
      <label for="email">Email</label>
      <input id="email" type="email" name="email" required />
    </div>
    <div class="field">
      <label for="motivo">Motivo</label>
      <select id="motivo" name="motivo" required>
        <option value="" disabled selected>Elegí una opción</option>
        <option value="diagnostico">Quiero un diagnóstico inicial</option>
        <option value="dashboard">Quiero reportería / dashboard</option>
        <option value="gamificacion">Quiero ideas de gamificación y seguimiento</option>
        <option value="contenido">Quiero apoyo para contenido técnico-comercial</option>
        <option value="otro">Otro</option>
      </select>
    </div>
    <div class="field">
      <label for="mensaje">Cuéntame brevemente tu problema</label>
      <textarea id="mensaje" name="mensaje" rows="6" required></textarea>
    </div>
    <input type="text" name="_gotcha" class="hp" />
    <input type="hidden" name="_subject" value="Nuevo prospecto en Performance Labs" />
    <input type="hidden" name="_next" value="/performanceblog/gracias/" />
    <div class="actions">
      <button class="btn btn-primary" type="submit">Solicitar contacto</button>
    </div>
  </form>
</div>
