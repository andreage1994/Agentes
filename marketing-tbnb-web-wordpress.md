# Marketing TBNB — Web / WordPress (Angel Vicedo, freelancer)

**Qué es:** el mantenimiento técnico y la puesta al día de la web de TBNB
(WordPress + WooCommerce + Elementor Pro + WPML + ACF Pro), llevado por
**Angel Vicedo** ([angelvicedo.com](https://www.angelvicedo.com/)),
freelancer externo. No es uno de los 7 canales de
`comunicacion-redes-sociales/` ni el SEO de contenido de `seo/` — es la
capa técnica/infraestructura sobre la que viven ambos. Mismo patrón de
seguimiento que `marketing-tbnb-sem-google-ads.md` (gestor externo,
minutas, pendientes nuestros).

**Encargado por Sergio**, primeros pasos pedidos (2026-10-27):
1. Arreglar accesos lentos de WordPress/Elementor.
2. Auditar los 26 plugins activos.
3. Resolver los 3 sistemas de cookies distintos y desactualizados.
4. Investigar plugin por plugin qué se usa y qué no.
5. Optimizar los 30-40 archivos de estilos que carga cada página.
6. Opinión sobre OPcache desactivado en el servidor.
7. Publicar 2 páginas HTML ya hechas (Marketing, Consultoría) bajo el
   apartado bar method.
8. Recomendación sobre cómo subir varias entradas de blog ya preparadas.

## Primera respuesta de Angel (2026-10-27)

Resumen de lo que dice: optimizó base de datos (limpieza de opciones
huérfanas de Yoast/Jetpack/Site Kit, transients), desactivó plugins
innecesarios, reseteó reglas de reescritura, y diagnosticó a fondo el
backend. Queda pendiente, según él: actualizar el resto de plugins,
reconectar "el plugin de cookies" (da error de autenticación), y
silenciar warnings del plugin multidioma (WPML).

Su diagnóstico técnico: OPcache deshabilitado, sin object cache
(Redis/Memcached), 773 opciones autoload (~500 KB por petición), MySQL
compartido con cola de I/O, memory_limit 768M sin margen real, hosting
compartido con CPU/memoria repartidas con otros clientes. Conclusión:
"hemos llegado al suelo que marca el hosting", y propone clonar la web
completa a su propio servidor para que la comparemos sin compromiso.

## Comprobación punto por punto

### 1. Accesos lentos de WordPress/Elementor

Lo que ha hecho (limpieza de BD, plugins desactivados, reset de
reescritura) es un primer paso razonable y barato — no soluciona nada
por sí solo si el cuello de botella real es el hosting, pero tampoco
sobra hacerlo antes de decidir nada más caro. **Falta un dato
concreto:** ¿cuánto ha bajado el tiempo de carga del panel, en
segundos, antes/después de hoy? Sin esa cifra no podemos saber si el
problema está resuelto en un 10% o en un 80% antes de hablar de mover
hosting.

### 2. Los 26 plugins activos

Angel dice "plugins innecesarios desactivados" pero no da ni el número
final ni la lista. **Esto sigue abierto** — es justo lo que pedimos en
el punto 4 original (investigar plugin por plugin). Hay que pedirle el
listado concreto: cuántos quedan activos, cuáles son, y para qué sirve
cada uno — no basta con "ya se ha limpiado".

### 3. Los 3 sistemas de cookies — el punto más delicado de los 8

Angel solo menciona **"el plugin de cookies"**, en singular, con error
de autenticación. No confirma si los otros 2 se han desinstalado o
siguen ahí desactivados (que no es lo mismo que fuera). **Esto no es
solo un tema de rendimiento, es de cumplimiento (RGPD/LOPD):** tres
sistemas de consentimiento de cookies desactualizados funcionando a la
vez puede significar que ninguno esté registrando el consentimiento
real del usuario de forma válida. Antes de dar esto por resuelto,
necesitamos que confirme explícitamente: cuál de los tres se queda,
que los otros dos estén **desinstalados** (no solo desactivados), y que
el que se queda esté actualizado y funcionando de verdad — no solo
"reconectado".

### 4. Investigar plugin por plugin

No entregado todavía como documento. Pedirlo como entregable concreto,
no como tarea genérica ya hecha "de pasada" durante la limpieza de hoy.

### 5. Los 30-40 archivos de estilos por página

**No aparece ni mencionado en su respuesta.** Hay que insistir en este
punto explícitamente en la siguiente comunicación — no se ha dado por
perdido, simplemente no lo ha tocado todavía.

### 6. OPcache — "dime qué opinas de esto"

Verificado por nuestra parte: lo que describe Angel (OPcache
desactivado, sin object cache, demasiadas opciones autoload, hosting
compartido con recursos repartidos) son problemas reales y conocidos de
rendimiento en WordPress — no se lo está inventando ni es una táctica
de miedo genérica, el diagnóstico en sí es técnicamente razonable.

**Pero la conclusión que saca ("hemos llegado al suelo del hosting, lo
mejor es clonar la web a mi servidor") se salta un paso mucho más
simple y barato que casi siempre existe antes de llegar a esa
conclusión:** en la inmensa mayoría de hostings compartidos con cPanel,
**OPcache se activa con un clic desde "Select PHP Version" / "PHP
Selector"**, sin tocar nada más y sin migrar de servidor — es
literalmente una casilla. Antes de aceptar cualquier cambio de
servidor, pedimos esto primero:

1. Que confirme si nuestro hosting actual tiene panel cPanel (o
   equivalente) con selector de PHP, y si OPcache aparece ahí como
   opción.
2. Si existe esa opción, que la active y nos dé el antes/después real
   (tiempo de carga del panel, de la web pública).
3. Que pregunte directamente al soporte de nuestro hosting actual si
   ofrecen object cache (Redis/Memcached) como add-on, antes de asumir
   que no se puede tener sin cambiar de proveedor.

**Sobre la propuesta de clonar la web a su propio servidor:** aquí hay
que separar lo técnico de lo de negocio. Técnicamente, un servidor
dimensionado a medida sí resolvería los síntomas que describe. Pero
mover la web de producción (con WooCommerce, es decir, con datos de
clientes y pedidos reales) al servidor personal de un freelancer tiene
riesgos que no aparecen en su propuesta y que nos tocan a nosotros
decidir, no a él proponerlos como algo neutro:

- **Punto único de fallo:** toda la web (y los datos de clientes vía
  WooCommerce) dependería de una sola persona y una sola máquina, sin
  el respaldo de un proveedor de hosting con infraestructura y soporte
  real.
- **Sin SLA ni garantías contractuales claras** sobre backups, tiempo
  de respuesta ante caída, o qué pasa si Angel deja de poder prestar el
  servicio.
- **Responsabilidad de protección de datos:** con WooCommerce hay datos
  personales de clientes — alojarlos en un servidor personal sin saber
  qué medidas de seguridad tiene exactamente complica la
  responsabilidad RGPD que es nuestra, no suya.
- **Reputación de IP compartida** con otros clientes suyos en el mismo
  servidor, si así lo monta.

Esto no significa decir que no — significa que, si la alternativa real
acaba siendo cambiar de hosting, la comparación correcta no es "la web
actual vs. el servidor de Angel", sino **"la web actual vs. un hosting
gestionado de WordPress de un proveedor reconocido"** (Kinsta,
SiteGround, WP Engine o similar) que ya ofrece OPcache, Redis, backups
y soporte — sin que dependamos de la infraestructura personal de un
colaborador puntual. Vale la pena pedirle a Angel presupuesto/tiempo
de migración a ese tipo de proveedor como alternativa a comparar, antes
de decidir nada sobre el clon.

### 7. Añadir las 2 páginas HTML (Marketing, Consultoría) al apartado bar method

**Importante, antes de pedirle a Angel que las suba:** estas dos
páginas (`seo/pagina-web/paginas/marketing-gastronomico.html` y
`abrir-restaurante-bar.html`) están marcadas en nuestro propio
`seo/pagina-web/estado.md` como **"🟢 Lista para Elementor — pendiente
de aprobación de Andrea/Sergio"**, no como aprobadas. Además, el propio
documento señala un punto sin cerrar: hay una URL distinta para la
misma página en dos sitios del proyecto
(`/marketing-gastronomico/` vs. `/marketing-gastronomico-restaurantes/`)
que hay que decidir antes de construirla, y varias URLs internas
(`/consultoria-gastronomica/`, `/consultoria-hosteleria-barcelona/`,
etc.) que hay que verificar contra el sitio en vivo antes de publicar.

**Y hay un antecedente real que confirma por qué esto importa:**
`diagnostico-traspasos-marketing-gastronomico.md` ya detectó que
`/marketing-gastronomico/` salió como "unknown to Google" en Search
Console, precisamente por no tener enlaces internos apuntándola — una
página huérfana. Saúl (el SEO externo anterior) ya lo señaló
explícitamente: **al publicar, hay que enlazar estas páginas desde
Home/Servicios en el mismo paso**, no como tarea aparte después.

**Recomendación:** antes de pedirle a Angel que "las suba", nosotros
(Andrea/Sergio) tenemos que cerrar primero cuál es la URL correcta y
aprobar formalmente las dos páginas. Y cuando se le pida a Angel que
las publique, hay que pedirle explícitamente que **añada también el
enlazado interno desde las páginas existentes relevantes** en el mismo
encargo — si no, se repite exactamente el mismo error ya diagnosticado.

### 8. Blog — subir directamente a WordPress, ¿es la mejor opción?

Sí: subir las entradas directamente en WordPress es lo correcto, no
hace falta ningún paso intermedio — es el método estándar y el que
menos riesgo de errores de formato introduce. En esto el consejo que
le han dado a Sergio es acertado.

**Lo que si hay que vigilar al subirlas** (y que puede pedírsele a
Angel como parte del encargo):
- Que se respeten el **title, meta description y estructura de
  encabezados (H1/H2)** ya definidos en cada artículo — están
  redactados y revisados en `seo/blog-web/articulos/` (7 artículos
  listos: licencias, ayudas para montar un bar, food cost, diseño de
  carta, APPCC, Estrella Galicia, Mahou).
- Que, igual que en el punto 7, se añada el **enlazado interno** desde
  cada artículo hacia la página de servicio relacionada (y viceversa
  donde tenga sentido) — mismo motivo: que Google los indexe bien desde
  el primer día, no como tarea aparte.

**Una decisión que sigue abierta desde antes y que hay que cerrar antes
de pedirle a Angel que suba nada:** Andrea ya había decidido publicar
los artículos todos juntos en una semana concreta, pero Saúl recomendó
en su momento publicarlos en goteo (uno cada semana o dos) para no
saturar de golpe. Esta decisión sigue sin cerrar (ver
`seo/recap-saul-2026-10-07.md`, punto 03) — conviene fijarla ahora,
porque determina si le pedimos a Angel que suba los 7 de golpe o que
programe la publicación escalonada.

## Pendiente de TBNB (añadido a `TAREAS.md`)

- [ ] Decidir cuál es la URL correcta de la página de marketing
  (`/marketing-gastronomico/` vs. `/marketing-gastronomico-restaurantes/`)
  antes de aprobar las páginas del punto 7.
- [ ] Aprobar formalmente (Andrea/Sergio) las 2 páginas HTML antes de
  pedirle a Angel que las publique.
- [ ] Decidir cadencia de publicación del blog (los 7 juntos vs. en
  goteo semanal/quincenal) antes de encargarle la subida a Angel.
- [ ] Pedirle a Angel: número y listado final de plugins activos,
  confirmación de que solo queda 1 sistema de cookies (y los otros 2
  desinstalados, no solo desactivados), y el punto de los 30-40
  archivos de estilos (no respondido todavía).
- [ ] Pedirle a Angel que compruebe si OPcache se puede activar en el
  hosting actual desde cPanel/PHP Selector, con cifras de antes/después,
  antes de valorar cualquier cambio de servidor.
- [ ] Si tras eso sigue haciendo falta cambiar de hosting, pedir
  también presupuesto de migración a un hosting gestionado de
  WordPress reconocido (no solo la opción del servidor personal de
  Angel), para comparar con criterio.

## Borrador de respuesta a Angel (pendiente de revisión de Sergio)

> Hola Angel,
>
> Gracias por el resumen, vamos punto por punto:
>
> **Plugins y cookies:** antes de seguir, necesitamos el listado final
> de plugins que han quedado activos (y para qué sirve cada uno), y
> confirmación de que de los 3 sistemas de cookies solo queda 1 activo
> — con los otros 2 desinstalados, no solo desactivados. Nos preocupa
> el tema de cumplimiento, no solo de rendimiento.
>
> **Archivos de estilos (30-40 por página):** no lo veo mencionado en
> tu resumen — ¿lo dejamos para la siguiente fase o ya tienes algo
> visto?
>
> **OPcache:** antes de valorar cualquier cambio de servidor, ¿puedes
> comprobar si nuestro hosting actual tiene panel cPanel con selector
> de PHP, y si desde ahí se puede activar OPcache directamente? Si es
> posible, actívalo y pásanos el antes/después real de tiempos de
> carga. Si de verdad no hay forma de tenerlo sin cambiar de
> proveedor, nos gustaría comparar tu propuesta de clon con un
> presupuesto de migración a un hosting gestionado de WordPress
> (tipo Kinsta/SiteGround/WP Engine), para decidir con las dos opciones
> sobre la mesa.
>
> **Páginas nuevas y blog:** vamos a confirmar un par de cosas
> internamente esta semana (una URL y la cadencia de publicación del
> blog) antes de pedirte que las subas — te escribimos en cuanto lo
> tengamos cerrado. Cuando llegue el momento, además de subirlas, nos
> hace falta que añadas el enlazado interno desde las páginas/artículos
> relacionados en el mismo encargo, no como tarea aparte.
>
> Un saludo,
> Sergio
