# Parámetros de filtro — Digital Spotting

Dados por Andrea (2026-09-28). Definen qué locales de Barcelona o Madrid
tiene sentido investigar como potencial cliente, y cómo leer sus reseñas
para saber qué tipo de conversación abrir.

Los cuatro filtros se aplican en orden: los tres primeros deciden **si**
un local es candidato; el cuarto decide **de qué le hablaríamos**.

## Filtro 1 — Antigüedad

- **< 2 años:** ideal.
- **< 3 años:** todavía interesante.
- **Cambio de concepto o nueva propiedad:** el local "vuelve a entrar" al
  filtro, aunque el local en sí sea más antiguo — un concepto relanzado
  cuenta como nuevo.

## Filtro 2 — Rating (nota media)

- **3,5–4,2:** prioridad. Es el rango donde más suele haber margen de
  mejora real y visible.
- **4,2–4,5:** revisar si existe un patrón concreto en las reseñas antes de
  descartarlo o priorizarlo — una nota alta no descarta que haya una
  oportunidad puntual clara.
- **< 3,5:** normalmente demasiado roto para el tipo de conversación que
  busca "Notas desde la Barra", salvo que haya una oportunidad muy evidente
  y concreta.

## Filtro 3 — Nº de reseñas

- **50–500:** muy interesante.
- **500–2.000:** interesante.
- **> 2.000:** solo si hay un patrón muy claro y repetido — con tanto
  volumen, hace falta que la señal sea inequívoca, no anecdótica.

## Filtro 4 — Tipo de oportunidad

Se obtiene leyendo el contenido real de las reseñas (no solo la nota) y
viendo en qué categoría se concentran las menciones. Cada categoría es una
pista de por dónde empezar la conversación — nunca una acusación, un patrón
a observar.

| Categoría | Palabras/señales a buscar en las reseñas |
|---|---|
| **SERVICE** | lento, camareros, atención, desorganizado, tardaron, cuenta (tardó en llegar), reserva, servicio |
| **EXPERIENCE** | ambiente, música, ruido, mesas, espacio, decoración |
| **CONCEPT** | no entiendo (el concepto/la carta), caro, carta (confusa), esperaba (algo distinto), decepción, diferente (a lo anunciado), poco (ración/valor), precio (percepción) |
| **FOOD** | carta (ejecución de platos), cantidad, calidad/precio, platos, frío, presentación |

**Nota de uso:** un mismo local puede tener señales en más de una
categoría — se anota la categoría dominante (la que más se repite en
reseñas recientes), y las secundarias si son relevantes. "Carta" y
"precio" pueden aparecer tanto en CONCEPT como en FOOD según si la queja es
sobre la propuesta en general (concepto) o sobre la ejecución concreta de
un plato (comida) — hay que leer el contexto de la reseña, no solo la
palabra suelta.

## Cómo se usa esto en la cascada del equipo

1. `potential-spotting-research` aplica los filtros 1-3 para descartar
   candidatos y el filtro 4 para etiquetar cada superviviente con su tipo
   de oportunidad dominante, citando las reseñas concretas que lo
   sostienen (nunca una categoría sin evidencia real).
2. `potential-spotting-estrategia` decide, con esa lista ya filtrada, a
   quién merece la pena contactar primero y qué ángulo tiene sentido para
   el documento "Notas desde la Barra" de cada uno.
3. `potential-spotting-redaccion` escribe el documento y el email a partir
   de esa decisión.
