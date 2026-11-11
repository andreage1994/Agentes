# Curación real del blog (sobre el texto publicado)

Esta carpeta sustituye a los borradores `articulos/curacion-*.md`. Esos se
escribieron sin leer el texto publicado y **no deben pegarse en la web**
(ver `../estado.md`, entrada del 2026-11-04). Aquí cada artículo se cura
**sobre el texto que hoy está en la web**, siguiendo el punto 5 del manual de
Andrea (`../manual-tono-y-reescritura-blog.md`).

La lista y el orden salen de la "Lista de curación" del documento *Nuestro
blog, explicado fácil* y de `../../canibalizacion-blog-2026-11-06.md`.

## Cómo está organizado cada archivo

1. **Ficha SEO:** URL (no se toca nunca), title, meta description y H1, cómo
   están hoy y la propuesta.
2. **Qué ha cambiado y por qué.**
3. **Pendiente de confirmar:** lo que tienen que decidir Andrea o Sergio
   antes de publicar.
4. **Texto curado,** listo para pegar en WordPress.

La carpeta `original/` guarda una copia del texto publicado tal y como
estaba al curarlo, por si hay que comparar o volver atrás.

**Nada se publica sin la aprobación de Andrea o Sergio.**

**Estructura obligatoria** (punto 3 del manual): introducción de 4-6 líneas,
concepto principal, desarrollo, perspectiva TBNB, conclusión corta y CTA
suave. Cada archivo incluye una tabla que dice dónde está cada parte.

## Seguimiento

| Archivo | Artículo | Trabajo | Estado |
|---|---|---|---|
| `01-rentabilidad.md` | Cómo calcular la rentabilidad de un negocio de hostelería | Curación | 🟡 Pendiente de revisión |
| `02-cinco-tipos-negocio.md` | Los 5 tipos de negocios de hostelería más rentables | Curación | 🟡 Pendiente de revisión |
| `03-guia-abrir-bar.md` | Guía completa para abrir un bar | Curación | 🟡 Pendiente de revisión |
| `04-punto-equilibrio.md` | Punto de equilibrio en restauración | Curación | 🟡 Pendiente de revisión |
| `05-vender-restaurante.md` | Lo que debes saber antes de vender un restaurante (absorbe "Cómo vender o comprar tu negocio con éxito") | Curación | 🟡 Pendiente de revisión |
| `06-regla-50-30-20.md` | Qué es la regla 50/30/20 en la hostelería | Curación ligera | 🟡 Pendiente de revisión |
| `07-vender-cafe-especialidad.md` | Cómo vender café de especialidad (absorbe "La transición al café de especialidad") | Curación | 🟡 Pendiente de revisión |
| `08-horario-ininterrumpido.md` | Horario ininterrumpido en el restaurante (absorbe la copia "trampa-horario…") | Curación ligera | 🟡 Pendiente de revisión |
| `09-reducir-gastos.md` | Cómo reducir los gastos de un bar | Curación ligera | 🟡 Pendiente de revisión |
| `10-fin-monodosis.md` | El fin de las monodosis en restaurantes (absorbe "Por qué quitan las monodosis") | Curación | 🟡 Corrección legal validada por Andrea |
| `11-crecer-tu-bar.md` | Cómo hacer crecer tu bar | Curación | 🟡 Pendiente de revisión |
| `12-errores-abrir-restaurante.md` | Errores comunes al abrir un restaurante (absorbe su copia `-2`) | Curación | 🟡 Pendiente de revisión |
| — | (EN) The 5 most profitable hospitality businesses | Curación | ⏸ Primero hay que juntar sus 16 copias |
| — | (EN) Transitioning to specialty coffee (-3) | Curación | ⏸ Primero hay que juntar sus 5 copias |

## Redirecciones que hay que poner al publicar

Cuando se publique el artículo curado, la URL que absorbe debe redirigir a
él con un 301 (Rank Math → Redirections):

| De | A |
|---|---|
| `/como-vender-o-comprar-tu-negocio-con-exito/` | `/lo-que-debes-saber-antes-de-vender-un-restaurante/` |
| `/la-transicion-al-cafe-de-especialidad-con-the-bar-n-bar/` | `/como-vender-cafe-de-especialidad/` |
| `/trampa-horario-ininterrumpido-restaurante/` | `/horario-ininterrumpido-restaurante/` |
| `/por-que-quitan-los-monodosis-en-los-bares/` | `/fin-monodosis-restaurantes/` |
| `/errores-comunes-al-abrir-un-restaurante-2/` | `/errores-comunes-al-abrir-un-restaurante/` |

## Fallos encontrados en los artículos publicados (arreglar ya, aunque no se publique la curación)

- **Lo que debes saber antes de vender un restaurante:** los 4 enlaces
  internos llevan a una búsqueda de Google (`google.com/search?q=…`), no a
  nuestros artículos.
- **Punto de equilibrio:** se ve en la web el texto "consultoría
  online(https://www.thebarnbarconsulting.com/)", un enlace mal pegado.
- **Cómo vender café de especialidad:** la página tiene tres H1.
- **Regla 50/30/20:** la tabla se ve como texto suelto separado por
  tabuladores.
- **Fin de las monodosis:** dice que la prohibición de las monodosis de
  plástico en sala entra en vigor el 12 de agosto de 2026. **Es el 1 de enero
  de 2030** (Reglamento (UE) 2025/40, art. 25 y anexo V). Es el fallo más
  urgente: es un dato legal y ya ha pasado la fecha que da el artículo.
- **Errores comunes al abrir un restaurante:** sus 9 enlaces internos llevan
  a búsquedas de Google.
- **Cómo hacer crecer tu bar:** 2 enlaces a búsquedas de Google, 10 H1 y
  promete una "primera auditoría gratuita" sin confirmar.
- **Horario ininterrumpido:** se ven en la web dos enlaces mal pegados
  ("como(https://…)" y "un análisis de(https://…)"). Además, el mismo texto
  está publicado en dos URLs.
- **Cómo reducir los gastos de un bar:** un enlace a una búsqueda de Google
  y la meta description cortada a media frase.

## Avisos que afectan a todo el blog

Andrea y Sergio suben ellos mismos los artículos, así que pueden hacer los
dos cambios sin esperar a Eleyuve:

- **Plantilla de title de Rank Math:** hoy todos los titles empiezan por
  "The Bar N Bar - ". Eso gasta espacio y aleja la palabra clave del
  principio. Cómo cambiarlo: WordPress → Rank Math → Títulos y metas →
  Entradas → Plantilla de título único → `%title% %sep% %sitename%`. Así
  queda, por ejemplo, "Cómo abrir un bar… - The Bar N Bar". Si una entrada
  tiene un title propio en su caja de Rank Math, ese manda sobre la
  plantilla.
- **"Entrebares" sale como H1** en todos los artículos, por la cabecera de la
  plantilla del blog. Así cada artículo tiene dos H1. Cómo cambiarlo:
  Plantillas → Theme Builder → Entrada individual → editar con Elementor →
  pulsar el título "Entrebares" → en "Etiqueta HTML", cambiar H1 por H2 o
  "p" → Actualizar. Si no aparece en Theme Builder, la plantilla la
  gestiona Eleyuve y hay que pedírselo.
