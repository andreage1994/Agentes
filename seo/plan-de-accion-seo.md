# Plan de acción SEO — prioridades (2026-10-07)

**Respuesta directa a la pregunta de Andrea** ("¿es actualizar la Home,
crear páginas nuevas, o en qué nos centramos?"): con los datos de hoy, la
prioridad es **arreglar y publicar lo que ya existe antes de crear nada
nuevo**. Solo hay un caso real de "falta crear una página" con dato que
lo sostenga (`/consultoria-gastronomica/`); casi todo lo demás es
contenido ya hecho sin publicar, o páginas ya construidas que no están
rindiendo por un problema concreto y arreglable — no por falta de
contenido nuevo.

Construido cruzando: `analisis-competencia.md`, `medicion-mensual.md`
(GA4 + Search Console + RankTank septiembre/octubre), `blog-web/estado.md`
y `pagina-web/estado.md`. Cada punto dice en qué dato real se apoya.

---

## Ola 1 — Arreglar lo que ya existe (la prioridad real, empieza aquí)

Nada de esto es crear contenido nuevo — es SEO técnico/on-page sobre
páginas que ya están construidas.

1. **Resolver la canibalización del Home.** "Consultoria hosteleria"
   (960/mes, la keyword de mayor volumen del Home) no rankea en ninguna
   página. "Asesoria hosteleria" sí rankea, pero vía la página de
   Barcelona, no vía el Home que se diseñó como "URL Pilar Única" para
   absorberla. Decisión a tomar: reoptimizar el Home para recuperar su
   keyword principal, o aceptar que las páginas locales
   (Madrid/Barcelona) son las que de verdad funcionan y redirigir el
   enlazado interno/autoridad hacia ellas en vez de pelear contra lo que
   ya funciona. — *Dato: RankTank, `medicion-mensual.md`.* Responsable:
   `seo-arquitectura-web`.
2. **Investigar por qué `/traspasos/` y `/marketing-gastronomico/` tienen
   cero impresiones**, pese a existir y recibir tráfico real (Traspasos
   tuvo 57 vistas en septiembre). No es un problema de posición, es que
   Google no las muestra ni una vez para sus keywords objetivo
   (1.600/mes y 700/mes respectivamente, las dos de mayor volumen de todo
   el research). Revisar indexación, Title/meta, contenido on-page. —
   *Dato: Search Console, `medicion-mensual.md`.* Responsable:
   `seo-arquitectura-web`.
3. **Relanzar las 5 keywords que fallaron el escaneo de RankTank**
   (incluida una variante cercana a un término pilar del Home) y
   **confirmar/añadir las keywords de traspasos** a la lista de RankTank
   si de verdad faltan (pendiente de que Andrea confirme). — Responsable:
   quien tenga el Sheet abierto, sin coste de agente.
4. **Decidir la URL correcta de Marketing gastronómico** antes de
   construir en Elementor: `/marketing-gastronomico/` (como dice el
   brief SEO) vs. `/marketing-gastronomico-restaurantes/` (como dice
   `BRIEF.md` del proyecto web) — dos documentos del propio proyecto se
   contradicen, hay que resolverlo antes del siguiente punto. — *Dato:
   `pagina-web/estado.md`.*

## Ola 2 — Publicar lo que ya está hecho

Contenido ya producido y pagado en tiempo de equipo, solo falta que
salga a la web.

5. **Publicar los 5 artículos de blog con redacción final** (Licencias,
   Ayudas de proveedores, Estrella Galicia, Mahou, Food cost) — ya
   programado para la semana del 13, pendiente solo de la última
   revisión de `blog-revision-seo-calidad`. Varios conectan directo con
   keywords informacionales hoy sin rankear ("como calcular food cost",
   "licencias para abrir un restaurante") — es la vía más rápida para
   mover esas posiciones. — *Dato: `blog-web/estado.md`.*
6. **Aprobar y construir en Elementor las 2 páginas de servicio ya
   listas** (Abrir un bar o restaurante, Marketing gastronómico) —
   pendientes solo de revisión de Andrea/Sergio, una vez resuelto el
   punto 4. — *Dato: `pagina-web/estado.md`.*
7. **Cerrar la revisión de los 2 artículos que volvieron a borrador**
   (Diseño de carta, APPCC) tras los cambios de fondo que pediste —
   necesitan pasar otra vez por `blog-revision-seo-calidad` antes de
   publicar junto a los otros 5.

## Ola 3 — Lo único que sí falta crear de cero

8. **Crear `/consultoria-gastronomica/`.** Es la única página del silo
   Core que no existe todavía, con 500 búsquedas/mes de keyword objetivo
   — ahora mismo no hay nada que pueda rankear para ese término porque
   la página no existe, no es un problema de optimización. — *Dato:
   `investigacion-heredada/roadmap-y-keyword-research.md`,
   `medicion-mensual.md` (confirma 0 impresiones).*
9. **Diferenciar el ángulo del servicio 360°** antes de escribir o
   retocar esa página — Ansón+Bonet ya usa el mismo término de categoría
   en prensa, hace falta anclarlo al BAR Method y al negocio
   independiente/familiar antes de competir por la palabra sin más. —
   *Dato: `analisis-competencia.md`.*
10. **Reforzar las sub-landings de Traspasos** (Madrid, Barcelona ya
    existen según la arquitectura heredada) — es el gap de negocio más
    claro frente a la competencia (ningún competidor revisado lo cubre)
    y la keyword de mayor volumen de toda la hoja, pero hoy no rankea.
    Se solapa con el punto 2 (arreglar la página existente) antes de
    pensar en sub-landings nuevas por ciudad.

## Ola 4 — Estructural, a medio plazo

No urgente esta semana, pero sin esto el techo de crecimiento es bajo:

11. **SEO local** (Google Business Profile, citas en Madrid/Barcelona) —
    terreno más abierto frente a Ansón+Bonet (posicionamiento más
    nacional/internacional). Sin responsable humano asignado todavía.
12. **Autoridad de dominio / backlinks** — evaluar la táctica de notas de
    prensa sindicadas (modelo SMQuatro, detectada en el análisis de
    competencia) con Sergio por el canal de PR que corresponda.
13. **Auditoría técnica a fondo** (Core Web Vitals, estructura de URLs,
    enlazado interno) — nunca se ha hecho, la de Rocket22 fue solo un
    chequeo general.
14. **El evento de conversión de leads en GA4 sigue sin configurar**
    (0 leads registrados en septiembre, probablemente por falta de
    tracking, no de leads reales) — no es una acción de posicionamiento
    pero sin esto nunca vais a poder saber si lo de arriba está
    funcionando de verdad. Ya señalado en `medicion-mensual.md`, lo
    repito aquí porque condiciona si todo este plan se puede medir.

---

## Resumen de una línea por ola

1. Arreglar lo que ya existe y no rinde (Home, Traspasos, Marketing
   gastronómico, RankTank).
2. Publicar lo que ya está escrito (blog + 2 páginas).
3. Crear lo único que de verdad falta (`/consultoria-gastronomica/` +
   ángulo del 360°).
4. Construir la base estructural (local, autoridad, auditoría técnica,
   medición de leads).
