# Performance Labs Blog

Blog en Jekyll listo para GitHub Pages y preparado para un flujo editorial con agente:

1. **Investigar** fuentes permitidas.
2. **Generar** borradores originales en `content_queue/borradores/`.
3. **Revisar y aprobar** el borrador.
4. **Publicar** moviéndolo a `_posts/`.
5. **Hacer push** para que GitHub Pages lo despliegue.

## Estructura clave

- `_posts/`: artículos publicados.
- `content_queue/borradores/`: borradores generados por el agente.
- `content_queue/aprobados/`: historial interno de piezas aprobadas.
- `scripts/crear_borrador.py`: crea un borrador desde un JSON.
- `scripts/aprobar_y_publicar.py`: valida, mueve a `_posts/` y deja copia en aprobados.
- `templates/post_template.md`: plantilla editorial base.

## Regla editorial

El agente **no debe copiar y pegar** texto de terceros. Debe producir contenido original, citando o enlazando fuentes como referencia editorial.
