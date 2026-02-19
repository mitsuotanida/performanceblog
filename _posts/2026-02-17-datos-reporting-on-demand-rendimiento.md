---
layout: post # Layout de post.
title: "Datos y reporting on demand: cómo subir el rendimiento sin entrenar más (entrenando mejor)" # Título.
date: 2026-02-19 # Fecha.
categories: [Datos, Rendimiento] # Categorías.
tags: [athlete monitoring, dashboards, carga, RPE, decisiones, Power BI] # Tags.
excerpt: "Lo que no medís, lo inventás. Un sistema simple de datos (bien hecho) te ayuda a ajustar carga, recuperar mejor y competir más estable. Guía + MVP." # Resumen.
---

El dato no te hace mejor por sí solo.  
Pero un **dato bien usado** te evita entrenar a ciegas.

Esto es “reporting on demand”: tener la info lista cuando hay que decidir.

<!--more-->

## 1) La promesa real de los datos (sin chamuyo)
Un sistema de datos bien armado te ayuda a:
- ajustar carga antes de llegar a fatiga crónica,
- detectar semanas “peligrosas”,
- y sostener consistencia (la verdadera madre del progreso).

En literatura de monitoreo de carga y fatiga se repite la misma idea: el valor está en el **proceso de decisión**, no en juntar métricas por deporte. :contentReference[oaicite:5]{index=5}

## 2) Qué medir (MVP inteligente)
### Capa A: interno (cómo lo vivís)
- sRPE (esfuerzo percibido) 1–10
- duración de sesión
- sueño (horas + calidad subjetiva)
- dolor/fatiga 1–5

### Capa B: externo (qué hiciste)
- distancia/tiempo/ritmo
- volumen total
- intensidad (zonas, si tenés)
- fuerza: series/reps/carga

### Capa C: resultado (lo que importa)
- tests simples (saltos, tiempos, repeticiones)
- performance en entrenamiento clave
- competencia (si aplica)

## 3) Métricas que sí sirven para decidir
- **Carga semanal** (sRPE x minutos)  
- **Tendencia 4 semanas** (sube/ baja)  
- **Readiness** (sueño + estrés + energía)  
- **Alertas** (3 días seguidos mal = ajustar)

(La clave: pocas métricas, bien definidas, y revisadas siempre igual.)

## 4) Reporting on demand: el loop de decisión
1) Captura (Form / App)  
2) Almacenamiento (Sheet/DB)  
3) Modelo (tablas limpias)  
4) Dashboard (Power BI)  
5) Decisión (reunión / revisión semanal)  
6) Acción (ajuste de carga)  
7) Seguimiento (¿funcionó?)

Si no existe el paso 5–6, tu dashboard es solo decoración.

## 5) Errores típicos (y cómo evitarlos)
- **Demasiados KPIs**: nadie decide con 40 gráficos.
- **Mala calidad de datos**: si entra basura, sale basura.
- **No hay ritual**: sin revisión semanal, el sistema se muere.

## 6) MVP (ultra práctico) para vos
**Semana 1**
- Google Form (o una mini app) para sRPE, sueño, estrés, duración.
- Google Sheet/Excel como base.

**Semana 2**
- Power BI: 1 página con:
  - Carga semanal
  - Tendencia 4 semanas
  - Estado (semáforo)
  - Notas del atleta/coach

**Semana 3**
- Reglas:
  - si 3 días seguidos sueño malo + fatiga alta → bajar intensidad
  - si carga sube muy abrupto → ajustar volumen

## Cierre
Los datos no reemplazan al entrenador ni al atleta.  
Pero te dan una ventaja enorme: **decidir con evidencia y no con intuición cansada**.

---

### Lecturas recomendadas
- Revisiones sobre monitoreo de carga, fatiga y uso de tecnología wearable en deporte: Frontiers in Sports and Active Living.
---
