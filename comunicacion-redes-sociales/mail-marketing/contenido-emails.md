# Contenido de los emails — listo para pegar en la plantilla

Copy real, tal como está redactado en `MAILMARKETING X TBNB.xlsx` (Drive,
carpeta "5. Marketing"). Cada ficha de abajo se corresponde 1:1 con las zonas
editables (`mc:edit`) de `plantilla-flujo-automatizacion.html` o
`plantilla-newsletter.html`.

**Exclusión confirmada por Andrea (2026-09-17):** el flujo **POST-VENTA /
Onboarding cliente** (3 emails: bienvenida como cliente, "Sergio es tu
contacto", check-in día 15 — filas 25-27 de la hoja, marcadas en rojo /
"INTERNO" en el excel original) **no se incluye** en esta tanda de plantillas.
Si en el futuro se retoma, son emails internos (van a clientes ya firmados,
no a leads) y probablemente no necesiten el mismo diseño de captación —
mejor decidirlo aparte cuando llegue el momento.

**Dos placeholders pendientes de resolver antes de activar en Mailchimp:**
- `[interés seleccionado]` (email TOFU #1) → sustituir por un merge tag real
  ligado al campo de interés del formulario de suscripción (ej. `*|INTERES|*`),
  una vez ese campo exista en la lista de Mailchimp.
- `[Nombre, Negocio]` (email BOFU #2, testimonio) → falta el testimonio real
  con nombre y negocio del cliente que lo dio. No enviar con el placeholder
  tal cual — o se rellena con un testimonio real y su permiso, o se quita esa
  línea del email.

Color de acento por etapa (ver comentario en cada plantilla HTML):
TOFU `#33B086` · MOFU `#009FE3` · BOFU `#E94A4B` · REACTIVACIÓN `#F3A038` ·
CAMPAÑA `#A890C3`.

---

## TOFU · Bienvenida / Nutrición (5 emails)

### 1 — Inmediato (welcome email)

- **Eyebrow:** TOFU · BIENVENIDA
- **Asunto / titular:** Bienvenido/a a The Bar N' Bar
- **Preview text:** Menos teoría, más barra. Aquí tienes lo primero.
- **Cuerpo:**

Gracias por sumarte, de verdad. Aquí no hay humo. Si buscabas un consultor de
traje que te hable de sinergias, te has equivocado de sitio. Llevamos años
con las manos en la masa: aperturas que salen bien, otras que casi se
tuercen y las salvamos a tiempo, cartas que había que replantear desde cero,
equipos que había que reconstruir. Lo que te vamos a contar sale de ahí — de
la barra, la cocina y la sala — no de un libro.

Nos has dicho que lo tuyo es `[interés seleccionado]`. Así que en los
próximos días te vamos a mandar justo eso: lo que hemos aprendido a pie de
negocio, sin relleno.

Lo siguiente te llega en unos días. Mientras tanto, ya sabes: estamos a un
mensaje de distancia.

- **CTA:** ninguno (borrar bloque CTA de la plantilla).

---

### 2 — Día 3 (educativo, ramifica por interés marcado — 7 variantes, mismo slot)

Mailchimp: usar segmentación/condicional por el tag de interés del
suscriptor para enviar la variante correspondiente.

**Variante APERTURA**
- **Eyebrow:** TOFU · APERTURA
- **Asunto:** Se abre con el corazón, se sobrevive con la cabeza
- **Preview text:** La ilusión no es el problema. Que mande sola, sí.
- **Cuerpo:**

Vamos al grano: la mayoría de los que abren un restaurante lo hacen desde la
ilusión del concepto. Casi nadie lo hace desde la viabilidad del negocio. Y
ojo, la ilusión no es el problema, de hecho, sin ella no se abre nada. El
problema es cuando la ilusión decide sola, sin que nadie le pregunte a los
números.

Se nota rápido: el local se elige porque "tiene un encanto especial", no
porque el alquiler cuadre con lo que puede facturar. La carta se diseña
porque "esto es lo que yo quiero cocinar", no porque el coste y la
producción sean sostenibles. La decoración se piensa antes que el punto de
equilibrio.

Nada de esto está mal por sí solo. Lo que falla es el orden: primero el
sueño, después, si acaso, la calculadora.

Esto es lo que sí funciona: dejar que la ilusión elija el qué, y que la
viabilidad decida el cómo. El concepto que te emociona puede seguir siendo
el mismo, solo que aterrizado en un local que puedes pagar, con una carta
que puedes producir, y unos números que has mirado antes de firmar nada.

No venimos a apagar la ilusión. Venimos a que siga viva después del primer
año.

- **CTA:** ninguno.

**Variante RENTABILIDAD**
- **Eyebrow:** TOFU · RENTABILIDAD
- **Asunto:** El número que deberías tener siempre a mano
- **Preview text:** Si no sabes cuánto necesitas vender, no sabes si vas bien o mal.
- **Cuerpo:**

Hay una pregunta que todo negocio debería tener respondida en todo momento,
no solo el día de la apertura: ¿cuánto tengo que facturar al mes para no
perder dinero? No aproximado. No "más o menos". El número real, actualizado.

Y esa pregunta, para responderla bien, se rompe en varias más pequeñas:
¿Cuántos clientes necesito al mes? ¿Con qué ticket medio? ¿Cuántos servicios
puedo hacer al día? ¿Qué ocupación necesito para llegar a esa cifra?
¿Cuántas veces puedo rotar cada mesa? ¿Cuánto necesito vender por hora
abierta?

Sin estas respuestas, cualquier "vamos bien" o "vamos mal" es una sensación,
no un dato. Y un negocio no se puede pilotar por sensaciones, ni el primer
mes, ni cinco años después.

Lo que sí funciona: calcular este número una vez, y revisarlo como
referencia fija, cada mes, cada temporada, cada vez que suban los costes o
cambie el equipo. No es un ejercicio que se hace una vez y se archiva. Es un
número vivo.

- **CTA:** ninguno.

**Variante OPERACIONES**
- **Eyebrow:** TOFU · OPERACIONES
- **Asunto:** El caos no espera a que crezcas
- **Preview text:** Un negocio pequeño sin procesos sufre igual, solo que no se nota tanto.
- **Cuerpo:**

El caos operativo no es cosa de negocios grandes. Un local pequeño sin
procesos ni organización clara lo sufre exactamente igual, solo que con poco
volumen se disimula mejor. El día que hay más gente, más pedidos o un
imprevisto, todo lo que "funcionaba de milagro" deja de funcionar.

No hace falta un sistema complicado para arrancar. Hace falta que cada tarea
tenga un responsable claro y un cómo, por escrito, aunque sea sencillo, no
solo quién lo hace, sino cómo se hace: cómo se limpia, cómo se cierra la
caja, cuáles son los pasos del servicio, quién es responsable de cada mesa y
quién se encarga de llevarla.

Si tuviéramos que empezar hoy, haríamos esto: escribir cómo se hace cada
proceso clave del día a día, apertura, cierre, pedidos, proceso de servicio,
antes de que dependa de que "Fulano se acuerde de todo".

- **CTA:** ninguno.

**Variante EQUIPO**
- **Eyebrow:** TOFU · EQUIPO
- **Asunto:** Por qué se te va la gente (y no es por el sueldo)
- **Preview text:** Un equipo sin sistema se quema. Y eso se nota en el servicio.
- **Cuerpo:**

Un equipo sin sistema ni procesos claros no aguanta. Y no es solo cuestión
de sueldo, casi siempre son varias cosas a la vez, todas pequeñas, todas
acumulándose:

Organización: horarios, roles y responsabilidades poco claros, trabajando a
base de apagar fuegos en vez de saber qué toca a quién.

Condiciones: jornadas que se alargan, descansos que no se respetan, turnos
que no dejan conciliar nada fuera del trabajo.

Desarrollo: la persona no ve hacia dónde puede crecer ni qué está
aprendiendo, solo repite el mismo turno, mes tras mes.

Cultura: no hay sensación de pertenencia, ni reconocimiento, ni un propósito
compartido más allá de cumplir el turno y fichar la salida.

Junta estas cuatro cosas y no hace falta que baje el sueldo para que alguien
se vaya. Y cuando la gente rota constantemente, se nota en el servicio, y el
servicio se nota en la reputación.

La rotación en hostelería no es "cosa del sector". Es, casi siempre, síntoma
de una organización que no está bien montada por dentro.

Lo que sí funciona: procesos claros, condiciones dignas, un camino de
desarrollo aunque sea sencillo, y un equipo que sabe qué se espera de él sin
tener que adivinarlo cada turno.

- **CTA:** ninguno.

**Variante CONCEPTO**
- **Eyebrow:** TOFU · CONCEPTO
- **Asunto:** Un concepto puede gustar y aun así fracasar
- **Preview text:** Que guste no significa que funcione. Son cosas distintas.
- **Cuerpo:**

Se puede crear un concepto que gusta, pero que no necesariamente funciona.
Son cosas distintas. Por eso, antes de construir nada, conviene hacerse
cuatro preguntas:

¿Lo quiere el cliente? No "¿me gusta a mí?", sino: ¿hay una demanda real
para esto en el mercado donde vas a abrir?

¿Se puede operar? La idea tiene que funcionar también en el día a día:
¿podemos producir y servir esta propuesta de forma consistente, servicio
tras servicio?

¿Puede ser rentable? Puedes tener algo que gusta muchísimo y que además es
operativamente viable, pero que pierde dinero.

¿Puede crecer? Si depende de un chef concreto, 25 ingredientes especiales y
una elaboración de 45 minutos, puede que tengas un restaurante. Pero no
necesariamente un modelo de negocio escalable.

Un concepto fuerte no es un logo bonito ni un nombre ingenioso. Es que estas
cuatro preguntas tengan respuesta antes de abrir la puerta, no después.

¿Tienes una idea de restaurante y quieres saber si realmente puede
funcionar? Hablemos antes de construirlo.

- **CTA:** frase de cierre a modo de invitación (no botón grande — ponerla como
  texto/enlace dentro del cuerpo, no como botón CTA de la plantilla).

**Variante GASTRONOMÍA**
- **Eyebrow:** TOFU · GASTRONOMÍA
- **Asunto:** La mejor carta no es la que más te gusta a ti
- **Preview text:** Margen, producción y demanda real. Ese es el equilibrio.
- **Cuerpo:**

La mejor carta no es la que más gusta al chef. Es la que consigue equilibrar
tres cosas: margen, capacidad de producción y lo que el cliente realmente
quiere pedir. Un plato espectacular que nadie pide, que deja poco margen o
que tarda 25 minutos en salir en hora punta no está ayudando al negocio, por
bueno que esté.

Muchas cartas nacen de la pasión del cocinero y terminan pagando el precio
en la cuenta de resultados.

Lo que sí funciona: revisar la carta con datos reales de ventas, no solo con
criterio culinario. Lo que se vende, lo que deja margen y lo que se puede
producir bien son tres preguntas distintas. Y las tres tienen que funcionar
a la vez.

¿Tu carta está diseñada para gustar o para funcionar? Pongamos tus platos a
prueba.

- **CTA:** frase de cierre como enlace dentro del cuerpo, igual que la variante anterior.

**Variante CRECIMIENTO**
- **Eyebrow:** TOFU · CRECIMIENTO
- **Asunto:** Crecer también puede romper lo que ya funcionaba
- **Preview text:** No es cuestión de más locales. Es cuestión de si aguanta lo que ya tienes.
- **Cuerpo:**

Crecer parece la parte buena. Y lo es, pero también es donde muchos negocios
que iban bien empiezan a hacer aguas, porque crecer no es "hacer lo mismo,
pero más". Es poner a prueba todo lo que hasta ahora funcionaba por poco
margen de error.

Esto es lo que solemos ver cuando un negocio empieza a crecer sin haberlo
preparado: la operación se convierte en el cuello de botella (lo que
funcionaba con un volumen determinado se atasca en cuanto hay más pedidos,
más mesas o más presión); el equipo no escala al mismo ritmo (contratar
gente no es lo mismo que tener un equipo formado); el producto no está
diseñado para volumen (una carta o un proceso pensado para 30 cubiertos no
siempre aguanta bien 100); el negocio depende demasiado de personas clave; y
el modelo financiero no está preparado para crecer (más volumen no siempre
significa más margen).

Nada de esto se ve hasta que ya está pasando. Por eso conviene mirarlo antes
de acelerar, no después de que algo se rompa.

- **CTA:** ninguno.

---

### 3 — Día 7 (segundo round educativo, mismas 7 variantes de interés)

**Variante APERTURA**
- **Eyebrow:** TOFU · APERTURA
- **Asunto:** El dinero que necesitas después de abrir, no para abrir
- **Preview text:** El primer mes casi nunca sale como en el papel.
- **Cuerpo:**

Casi todo el mundo calcula cuánto necesita para abrir: obra, mobiliario,
maquinaria, el primer pedido de género. Muy poca gente calcula cuánto
necesita para aguantar después de abrir.

Los primeros meses casi nunca salen como en el papel. La clientela tarda en
llegar, el boca a boca no es inmediato, hay que ajustar la carta sobre la
marcha, algún proveedor falla justo cuando más falta hace. Todo eso cuesta
dinero, y si no hay colchón para cubrirlo, el negocio puede fracasar aunque
el concepto sea bueno, simplemente porque se quedó sin aire antes de
despegar.

Esto es lo que sí funciona: calcular no solo la inversión inicial, sino
también el capital para sobrevivir 3-6 meses sin depender de que todo salga
perfecto desde el primer día.

¿Ya tienes calculado tu colchón real, o solo la inversión inicial?

- **CTA:** ninguno (pregunta de cierre, no botón).

**Variante RENTABILIDAD**
- **Eyebrow:** TOFU · RENTABILIDAD
- **Asunto:** El dinero se escapa antes de que lo veas en la cuenta
- **Preview text:** Mermas, desperdicio y proveedores que suben sin avisar.
- **Cuerpo:**

Saber cuánto necesitas facturar es el primer paso. El segundo, el que casi
nadie revisa con la misma disciplina, es saber por dónde se está escapando
el margen todos los días, en silencio.

Los sitios más habituales: mermas que se dan por normales sin medirlas,
desperdicio que nadie apunta porque "siempre ha sido así", y proveedores que
suben precios poco a poco sin que nadie compare la última factura con la de
hace seis meses.

Nada de esto aparece de golpe. Se acumula, mes a mes, hasta que el margen
que debería haber, no está.

Lo que sí funciona: revisar mermas y facturas de proveedores con la misma
frecuencia que revisas las ventas. No es el dato más vistoso, pero es donde
de verdad se juega la rentabilidad.

¿Cuándo fue la última vez que comparaste una factura de proveedor con la de
hace seis meses?

- **CTA:** ninguno.

**Variante OPERACIONES**
- **Eyebrow:** TOFU · OPERACIONES
- **Asunto:** Todos están trabajando. Entonces, ¿por qué se pierden ventas?
- **Preview text:** Cuando todos hacen de todo, muchas veces nadie es responsable de nada.
- **Cuerpo:**

Un servicio no debería depender de quién está trabajando ese día. Pero en
muchos restaurantes ocurre algo parecido: todos hacen de todo. Uno toma la
mesa, otro lleva platos, otro recoge, otro cobra. Parece que todo el mundo
está ocupado. Y, sin embargo, hay una mesa esperando para pedir otra ronda.
Nadie se acerca.

No porque el equipo no quiera vender. Porque nadie tiene definido que ese
momento es suyo.

Un buen servicio necesita algo más que gente trabajando: necesita roles
claros, una secuencia de servicio y un método común de trabajo. Quién hace
qué. Cuándo. Cómo. Y, sobre todo, qué tiene que pasar después. Porque una
segunda ronda que nadie ofrece no es solo un fallo de servicio. Es una venta
que no ocurre.

La operativa no debería depender de la intuición de cada camarero. Debería
existir un sistema que haga que el buen servicio sea repetible, medible y
rentable.

¿Cuántas ventas se están perdiendo en tu servicio sin que nadie las esté
viendo?

- **CTA:** **DESCUBRE DÓNDE ESTÁS PERDIENDO VENTAS →** (este sí lleva botón
  real en la plantilla).

**Variante EQUIPO**
- **Eyebrow:** TOFU · EQUIPO
- **Asunto:** El primer mes decide si alguien se queda
- **Preview text:** Contratar bien no sirve de nada si luego cada uno aprende a su manera.
- **Cuerpo:**

Puedes tener un gran concepto, una forma de trabajar muy definida y un
equipo con mucho potencial. Pero si nadie se encarga de transmitirlo, cada
persona acaba trabajando bajo su propio criterio: uno sirve de una manera,
otro organiza su partida de otra, cada uno trata al cliente como aprendió en
su restaurante anterior. Y así, sin que nadie lo decida, el concepto empieza
a disolverse en la operativa del día a día.

Formar a un equipo no es solo enseñarle a hacer su trabajo. Es explicarle
cómo funciona la casa, qué se espera de él y por qué se hacen las cosas de
una determinada manera — y eso empieza desde el primer día. Porque si una
persona llega y escucha "ponte el delantal y ya irás viendo, si tienes
dudas, pregunta", lo que aprende no es tu forma de trabajar. Aprende a
sobrevivir por su cuenta.

Un buen onboarding le da las herramientas para entender el negocio antes de
tener que improvisarlo: quién hace qué, cómo funciona el servicio, qué
estándares hay, y quién le va a acompañar durante sus primeras semanas.

Formar bien no solo ayuda a que alguien se quede. Ayuda a que todo el equipo
trabaje bajo el mismo sistema — y cuando eso pasa, el concepto deja de estar
solo en un papel y empieza a notarse en cada servicio.

¿Tu equipo sabe cómo quieres que funcione tu restaurante, o simplemente
sabe cómo trabajar?

- **CTA:** ninguno.

**Variante CONCEPTO**
- **Eyebrow:** TOFU · CONCEPTO
- **Asunto:** Cuando el concepto se pierde sin que nadie se dé cuenta
- **Preview text:** Un cambio pequeño hoy, otro mañana. Y un día ya no es lo mismo.
- **Cuerpo:**

Los conceptos no suelen desaparecer de un día para otro. Cambias un poco la
carta. Añades una tendencia que funciona en otros sitios. Modificas el
servicio para agilizarlo. Incorporas algo nuevo porque un cliente lo pidió.
Cada decisión, por separado, tiene sentido. El problema aparece cuando nadie
se pregunta si todas esas decisiones siguen construyendo el mismo
restaurante.

Y entonces, un día, el restaurante ya no se parece a aquello que lo hacía
especial. No hubo una gran decisión de cambiar el concepto. Se fue
diluyendo.

Por eso, mantener un concepto no significa dejarlo exactamente igual para
siempre. Significa saber qué es esencial y qué puede evolucionar. Antes de
incorporar algo nuevo, hay una pregunta que conviene hacerse: ¿esto mejora
lo que somos o simplemente sigue lo que está funcionando fuera?

Porque evolucionar un concepto es sano. Perderlo por el camino, no.

¿Cuánto se parece tu restaurante de hoy al que imaginaste cuando lo abriste?

- **CTA:** ninguno.

**Variante GASTRONOMÍA**
- **Eyebrow:** TOFU · GASTRONOMÍA
- **Asunto:** No todos los platos de tu carta hacen el mismo trabajo
- **Preview text:** Hay platos estrella, platos reclamo y platos de relleno. Confundirlos sale caro.
- **Cuerpo:**

No todos los platos de una carta cumplen la misma función. Hay platos
estrella (los que dejan buen margen y se piden mucho), platos reclamo (los
que atraen aunque dejen menos margen, porque generan la visita) y platos de
relleno (los que están ahí "por si acaso", sin aportar mucho a ninguna de
las dos cosas).

El problema es cuando se tratan todos igual: se les da el mismo espacio en
la carta, el mismo esfuerzo de producción, la misma atención, sin saber cuál
es cuál.

Lo que sí funciona: clasificar cada plato según su función real, y decidir
con esos datos qué potenciar, qué mantener tal cual, y qué quitar sin miedo.

¿Sabrías decir ahora mismo cuáles son tus platos estrella y cuáles solo
relleno?

- **CTA:** ninguno.

**Variante CRECIMIENTO**
- **Eyebrow:** TOFU · CRECIMIENTO
- **Asunto:** Crecer no siempre significa un local más
- **Preview text:** A veces está en sacar más de lo que ya tienes.
- **Cuerpo:**

Crecer no siempre significa abrir otro local. Muchas veces está en sacar más
de lo que ya tienes: mejorar el margen, aumentar el volumen con el mismo
espacio, optimizar lo que ya funciona, antes de multiplicar por dos algo que
todavía no está resuelto.

Abrir un segundo local no arregla lo que cojea en el primero. Lo duplica,
con el doble de complejidad y la mitad de atención por sitio.

Lo que sí funciona: exprimir el negocio actual — ocupación, ticket medio,
margen — antes de pensar en un local más. El crecimiento real casi siempre
empieza puertas adentro.

Antes de pensar en un local más, ¿qué le queda por dar al que ya tienes?

- **CTA:** ninguno.

---

### 4 — Día 12 (reforzar autoridad, un único email, no ramifica)

- **Eyebrow:** TOFU · AUTORIDAD
- **Asunto:** Tu restaurante no compite solo por la comida
- **Preview text:** Cada vez elegimos más lugares que dicen algo de quiénes somos.
- **Cuerpo:**

Hay una pregunta que cada vez importa más cuando alguien decide dónde ir:
"¿Esto es para mí?" No hablamos solo de si la comida está buena. Buscamos
lugares que encajen con nuestra forma de vivir, nuestros gustos y nuestra
manera de relacionarnos. El café donde trabajamos. El bar donde nos
encontramos con nuestra gente. El restaurante al que llevamos a alguien
porque sabemos que le va a encantar. El sitio del que sentimos que formamos
parte.

Y esto cambia algo importante para los restaurantes: ya no basta con tener
una buena propuesta. Hay que tener una identidad. Porque cuando un concepto
representa algo, el cliente no solo consume lo que vendes. Se identifica con
ello.

Lo vemos en cada proyecto: el que arrasa no es siempre el que mejor cocina,
es el que la gente siente suyo. Pero crear identidad no significa llenar el
local de frases, neones o una estética reconocible. Significa tener claro:
quién eres, para quién eres, qué defiendes, qué experiencia quieres crear, y
por qué alguien debería querer formar parte de ella.

Ahí es donde un restaurante deja de ser simplemente un lugar donde comer y
empieza a convertirse en un lugar al que quieres volver.

La pregunta que nos hacemos cuando desarrollamos un concepto no es solo
"¿qué vamos a vender?". Es "¿qué lugar queremos ocupar en la vida de nuestro
cliente?".

- **CTA:** ninguno.

---

### 5 — Día 18 (introduce caso de éxito → sube a MOFU, 6 variantes por interés)

**Variante APERTURA — Rascal**
- **Eyebrow:** TOFU · CASO RASCAL
- **Asunto:** Una buena idea no es suficiente para abrir un restaurante
- **Preview text:** Rascal empezó con una idea. El reto era convertirla en algo que pudiera funcionar de verdad.
- **Cuerpo:**

Cuando empezamos a trabajar en Rascal, había una idea clara detrás: hacer
las cosas de otra manera. Pero tener una buena idea es solo el principio.
Había que conseguir que esa idea se convirtiera en un concepto reconocible,
en una propuesta gastronómica, en una experiencia y, sobre todo, en un
negocio capaz de funcionar en el día a día.

Porque abrir un restaurante significa conectar muchas piezas: concepto +
cliente + producto + operación + equipo + números. Si una de ellas no
encaja, el resto acaba pagando las consecuencias.

Por eso, antes de pensar únicamente en cómo iba a verse Rascal, trabajamos
en cómo tenía que funcionar. Desde lo que quería representar hasta cómo
debía sentirse el cliente cuando entrara, qué iba a encontrar en la carta y
cómo todo ello se traduciría en la operación.

Porque para nosotros, desarrollar un concepto no es hacer que una idea
parezca buena. Es conseguir que pueda convertirse en un negocio real.

- **CTA:** ninguno.

**Variante RENTABILIDAD — Lady Madrid**
- **Eyebrow:** TOFU · CASO LADY MADRID
- **Asunto:** No necesitaban vender más. Necesitaban funcionar mejor.
- **Preview text:** En Lady Madrid, el problema no se solucionaba simplemente trayendo más clientes.
- **Cuerpo:**

Cuando llegamos a Lady Madrid, el objetivo no era simplemente conseguir más
ventas. Había que entender qué estaba pasando realmente dentro del negocio.
Porque aumentar la facturación no sirve de mucho si cada euro adicional
genera también más costes, más complejidad y más problemas.

Trabajamos sobre diferentes piezas del negocio para entender dónde estaba el
potencial real: operación, propuesta, experiencia y rentabilidad.

El resultado: +100.000 € de facturación en 6 meses. +45.000 € de
rentabilidad neta.

Pero lo más importante no fue vender más. Fue conseguir que más de lo que ya
se estaba haciendo terminara convirtiéndose en resultado. Porque un
restaurante no es rentable cuando factura mucho. Es rentable cuando sabe
convertir su volumen en margen.

- **CTA:** ninguno.

**Variante CONCEPTO — Rasa**
- **Eyebrow:** TOFU · CASO RASA
- **Asunto:** Un concepto no se construye con un logo
- **Preview text:** Se construye en cada decisión que toma el restaurante.
- **Cuerpo:**

Rasa no necesitaba simplemente una identidad bonita. Necesitaba que su
identidad se pudiera vivir. Por eso, el concepto no se quedó en el nombre,
la estética o la narrativa. Lo llevamos a cada punto de contacto con el
cliente: la carta, el producto, el servicio, los rituales, la experiencia y
la forma de relacionarse con el restaurante.

Porque si el concepto dice una cosa y la carta dice otra, el servicio otra y
la experiencia otra, el cliente no recibe una identidad. Recibe piezas
sueltas.

El reto era conseguir que todo hablara el mismo idioma. Que cuando alguien
entrara en Rasa, pudiera entender quién era el restaurante sin que nadie
tuviera que explicárselo.

Eso es lo que buscamos cuando desarrollamos un concepto: que la identidad no
solo se vea. Que se sienta.

- **CTA:** ninguno.

**Variante GASTRONOMÍA — Gambit**
- **Eyebrow:** TOFU · CASO GAMBIT
- **Asunto:** La gastronomía también diseña la experiencia
- **Preview text:** En Gambit, la carta tenía que hacer algo más que alimentar al cliente.
- **Cuerpo:**

Cuando desarrollas un concepto, la gastronomía no puede ir por un lado y la
experiencia por otro. En Gambit, el reto no era simplemente crear una carta
que encajara con el universo del ajedrez. Era conseguir que la oferta
ayudara a construir la experiencia y a generar diferentes momentos de
consumo.

¿Qué pide alguien que viene a jugar una partida? ¿Qué quiere consumir quien
viene a tomar algo? ¿Y quien se queda a comer? ¿Y quien quiere alargar la
experiencia? Cada momento necesita una propuesta diferente.

Por eso, la carta no se diseña únicamente pensando en qué queremos servir,
sino también en: cuándo se consume, con quién, durante cuánto tiempo y qué
experiencia queremos generar.

Así, la gastronomía deja de ser simplemente una lista de platos y empieza a
trabajar junto al concepto: crea momentos, genera consumo y hace que el
cliente pueda vivir el espacio de distintas maneras.

Porque una buena propuesta gastronómica no solo responde a "¿qué vamos a
comer?". También responde a "¿qué podemos hacer aquí y cuánto tiempo
queremos quedarnos?". Y cuando gastronomía, concepto y experiencia están
alineados, una carta puede convertirse en una herramienta para hacer crecer
el negocio.

- **CTA:** ninguno.

**Variante EQUIPO — Chandrio**
- **Eyebrow:** TOFU · CASO CHANDRIO
- **Asunto:** Más gente no siempre significa mejor servicio
- **Preview text:** En Chandrio, el reto no era tener más personas. Era conseguir que todas trabajaran como un equipo.
- **Cuerpo:**

Chandrio es un proyecto complejo: 6 bares, 4 food trucks y diferentes
equipos, horarios y dinámicas de trabajo. Con esa estructura, añadir más
personas no necesariamente soluciona el problema. Si nadie sabe exactamente
quién decide, quién supervisa, quién se encarga de cada espacio o cómo debe
funcionar el servicio, más personas pueden significar simplemente más
complejidad.

Por eso, uno de los retos era poner estructura donde antes había muchas
piezas funcionando a la vez. Definir responsabilidades. Ordenar la
operación. Crear sistemas de trabajo. Establecer estándares. Y conseguir que
la hospitalidad no dependiera de quién estuviera trabajando ese día.

Porque un equipo no funciona cuando todos hacen de todo. Funciona cuando
todos saben qué tienen que hacer y entienden cómo su trabajo forma parte del
conjunto.

- **CTA:** ninguno.

**Variante CRECIMIENTO — franja horaria (sin nombre de cliente en la hoja)**
- **Eyebrow:** TOFU · CASO CRECIMIENTO
- **Asunto:** Querían crecer. No necesitaban abrir otro local.
- **Preview text:** A veces la oportunidad está en algo que ya tienes y todavía no estás aprovechando.
- **Cuerpo:**

Cuando un restaurante quiere crecer, la primera idea suele ser: "abramos
otro local." Pero antes de multiplicar un negocio, conviene preguntarse
cuánto potencial queda todavía dentro del que ya existe.

En este caso, detectamos una oportunidad en algo que estaba delante de
todos: una franja horaria que el restaurante todavía no estaba
aprovechando.

El reto no era simplemente abrir más horas. Había que entender: ¿qué
cliente podíamos atraer? ¿qué propuesta tenía sentido en ese momento del
día? ¿qué producto necesitábamos? ¿qué equipo hacía falta? ¿y podía
funcionar económicamente?

Convertir una franja vacía en una nueva ocasión de consumo significaba
crecer sin añadir un nuevo local. Porque crecer no siempre significa hacer
más grande el negocio. A veces significa sacar más partido a lo que ya
tienes.

- **CTA:** ninguno.

---

## MOFU · Consideración (3 emails)

### 1 — Día 1 (caso segmentado por tipo de negocio)

**Variante Cafetería/Bar — Brunch and the City**
- **Eyebrow:** MOFU · CAFETERÍA / BAR
- **Asunto:** Cuando lo urgente no te deja ver lo importante
- **Preview text:** Henry nos llamó después de abrir. No antes.
- **Cuerpo:**

Brunch and the City ya estaba abierto cuando Henry nos llamó. El local
funcionaba, pero el día a día se había llenado de fricciones: gestión de
personal sin criterio claro, protocolos que no existían, formación que se
hacía sobre la marcha, cero estandarización.

Es el patrón más común que vemos: el negocio abre, empieza a funcionar, y el
caos del día a día se va comiendo el tiempo para pararse a organizarlo.

Nos metimos dentro, literal: evaluamos la operación desde el puesto de
kitchen porter para ver los puntos críticos de verdad, no desde un
despacho. A partir de ahí montamos un checklist operativo de principio a
fin, dimos dirección al equipo con formación real, ordenamos la parte
financiera con reuniones periódicas de resultados, y dejamos toda la
documentación legal en regla.

El resultado no fue una revolución de un día. Fue una base sólida para que
Brunch and the City pudiera seguir creciendo sin que cada semana fuera
apagar un incendio distinto.

Si te suena parecido a tu día a día, sigue leyendo — lo que viene te va a
interesar.

- **CTA:** ninguno (invitación a seguir leyendo, no botón).

**Variante Restaurante — Rasa**
- **Eyebrow:** MOFU · RESTAURANTE
- **Asunto:** Un concepto potente no se sostiene solo con buena comida
- **Preview text:** RASA necesitaba algo más que una carta espectacular.
- **Cuerpo:**

RASA quería ser un cocktail lounge gastronómico indio contemporáneo — sin
caer en los tópicos de siempre. Ese es un reto concreto: si simplificas
demasiado un concepto cultural, pierde verdad; si lo complicas demasiado,
deja de conectar. El equilibrio no aparece solo.

Trabajamos el proyecto desde cero: desarrollo de la oferta gastronómica y de
coctelería con narrativa propia, diseño de los flujos operativos,
adaptación del espacio, y algo que muchos negocios se saltan — la cultura
interna. Procesos de cocina y sala, protocolos, manuales, y una filosofía de
hospitalidad que el equipo entendiera de verdad, no solo de memoria.

Porque puedes tener una carta brillante y una barra impecable, pero si el
cliente no se siente bien dentro del espacio, todo lo demás pierde fuerza.

El resultado fue un proyecto donde gastronomía, coctelería, diseño y cultura
de equipo funcionan como una misma narrativa — coherente de principio a fin,
no una suma de piezas sueltas.

Si tu negocio también busca esa coherencia entre lo que es y lo que
transmite, sigue leyendo.

- **CTA:** ninguno.

**Variante Otros — Mantener Barcelona**
- **Eyebrow:** MOFU · OTROS NEGOCIOS
- **Asunto:** Cien decisiones distintas, un mismo sitio al que empujar
- **Preview text:** Chris y Daniel llegaron con una visión y un local vacío.
- **Cuerpo:**

Cuando Chris y Daniel nos llamaron, Mantener Barcelona todavía no existía.
Tenían una visión clara — cocina latina contemporánea conectada con
Barcelona — y un local vacío lleno de posibilidades y de problemas por
resolver.

Empezamos antes incluso de entrar al espacio: evaluamos si el local tenía
sentido de verdad para el negocio que querían montar, y negociamos el
alquiler y traspaso desde ahí. Porque en hostelería, muchas veces el
problema empieza antes de abrir — cuando se elige un espacio que no encaja
con la operación ni con los números.

Después vino la parte más caótica: obra, industriales, interiorismo,
branding, proveedores, todo a la vez. Nuestro trabajo fue ordenar ese
proceso y mantenerlo alineado con la visión original — sin perder de vista
que el negocio tenía que funcionar de verdad, no solo verse bien en un
render.

Diseñamos la lógica operativa antes de abrir la puerta — flujos de sala,
operativa de barra, organización de cocina — y acompañamos también la
construcción del equipo que iba a sostener el proyecto el primer día de
servicio real.

El resultado: un negocio completamente estructurado desde las primeras
decisiones hasta la apertura, con cien decisiones distintas empujando hacia
el mismo sitio.

Si estás en un momento parecido — con más preguntas que respuestas — sigue
leyendo.

- **CTA:** ninguno.

---

### 2 — Día 5 (Can Miserias)

- **Eyebrow:** MOFU · CASO CAN MISERIAS
- **Asunto:** Un local cerrado no es un negocio acabado
- **Preview text:** Menos humo, más realidad. Así lo hicimos con Can Miserias.
- **Cuerpo:**

Fonda Can Miserias era un local histórico del centro de Barcelona que
llevaba años cerrado, sin estructura ni dirección clara. El reto no era solo
volver a abrir la puerta — era recuperar la esencia de la fonda catalana
tradicional sin caer en la nostalgia vacía, ni en el típico "concepto
mediterráneo" que ya hemos visto mil veces.

Ahí había una línea muy fina: pasarse de moderno y perder autenticidad, o
quedarse en lo tradicional y no conectar con la ciudad de hoy. Encontrar ese
equilibrio fue el primer trabajo.

Pero el concepto era solo la mitad. La otra mitad — la que parece menos
vistosa pero es donde se gana o se pierde un restaurante — fue construir
toda la estructura interna desde cero: flujos de trabajo, protocolos de
cocina y sala, escandallos, estructura de equipo, sistemas de seguimiento.
Porque una buena idea sin operación acaba durando menos que una caña
caliente en agosto.

El resultado: un local cerrado y sin dirección se convirtió en un
restaurante con identidad propia, estructura real y una propuesta que sí
conecta con Barcelona.

Es exactamente como entendemos la hostelería: menos humo, más realidad.
Menos postureo gastronómico, más sitios que funcionan, conectan y tienen
algo que decir.

- **CTA:** ninguno.

---

### 3 — Día 9 (CTA suave — agenda de diagnóstico)

- **Eyebrow:** MOFU · HABLEMOS
- **Asunto:** ¿Hablamos 15 minutos de tu negocio?
- **Preview text:** Sin powerpoints. Sin pitch. Solo mirar tu caso de verdad.
- **Cuerpo:**

Llevas unos días viendo cómo trabajamos: Brunch and the City, RASA,
Mantener, Can Miserias. Proyectos distintos, mismo enfoque — menos humo, más
realidad.

Si algo de esto te ha sonado parecido a lo que te pasa a ti, no hace falta
que sigas leyendo casos. Hablemos directamente del tuyo.

Te proponemos 30 minutos, gratis, sin compromiso. No es una llamada
comercial disfrazada de diagnóstico — es justo lo contrario: miramos tu
negocio, te decimos lo que vemos, y si tiene sentido seguir, seguimos. Si
no, también te lo decimos.

Puede que no sea el momento, y está bien. Pero si llevas tiempo dándole
vueltas a algo — un local que no cuadra, un equipo que se te va, una carta
que no sabes si funciona — esta es la conversación que te falta tener.

- **CTA:** **Agenda tu llamada de diagnóstico gratuita**

---

## BOFU · Conversión (2 emails)

### 1 — Día 1 (propuesta de valor + prueba social)

- **Eyebrow:** BOFU · TRABAJEMOS JUNTOS
- **Asunto:** Esto es lo que te llevas si trabajas con nosotros
- **Preview text:** Orden, claridad y un plan real. Nada más, nada menos.
- **Cuerpo:**

Si has llegado hasta aquí, probablemente ya tienes algo dándote vueltas en
la cabeza: un negocio que no rinde lo que debería, una apertura que no sabes
por dónde coger, un equipo que no aguanta, una carta que no sabes si
funciona.

Esto es lo que te llevas cuando trabajas con nosotros: orden donde hay
caos, números reales donde había intuición, y un plan concreto — no un
informe de 40 páginas que se queda en un cajón.

No lo decimos de oídas. Lo hemos hecho con negocios muy distintos entre sí:
una cafetería que necesitaba estructura después de abrir, un concepto
gastronómico que había que construir desde cero, un local histórico que
llevaba años cerrado, un restaurante que necesitaba escandallos y
organización real desde el primer día. Contextos distintos, mismo enfoque:
menos humo, más realidad.

Si esto te suena a lo que necesitas, el siguiente paso es simple: 15
minutos, gratis, sin compromiso. Miramos tu negocio, te decimos lo que
vemos, y decides tú si seguimos.

- **CTA:** **Agenda tu llamada de diagnóstico gratuita**

---

### 2 — Día 4 (urgencia + testimonio)

- **Eyebrow:** BOFU · SIN PRISA FALSA
- **Asunto:** Cada mes que pasa, el problema sigue costando
- **Preview text:** No te vamos a meter prisa falsa. Pero el tiempo sí cuesta dinero.
- **Cuerpo:**

No te vamos a decir que esto es una oferta limitada ni que quedan "últimas
plazas" — eso no es lo nuestro. Pero sí hay algo real: cada mes que un
negocio sigue con el mismo caos operativo, el mismo descontrol de costes o
el mismo equipo quemándose, ese problema no se queda quieto. Sigue costando
dinero, gente y reputación mientras se pospone la decisión de mirarlo de
frente.

No hace falta que lo digamos solo nosotros:

> "La experiencia y trayectoria de Sergio en el sector hostelero son
> evidentes. Su creatividad y pasión por los proyectos gastronómicos le
> distinguen. Junto a Andrea, forman un equipo único, profesional e
> increíblemente apasionado." — **`[Nombre, Negocio]`** ⚠️ *pendiente: falta
> el testimonio real con nombre y negocio, o su permiso — no enviar con el
> placeholder tal cual.*

Si llevas semanas dándole vueltas a dar el paso, esta es la señal:
escríbenos y hablamos 15 minutos, sin compromiso. Y si al final decides que
no es el momento, seguimos aquí cuando lo sea.

- **CTA:** **Agenda tu llamada de diagnóstico gratuita**

---

## REACTIVACIÓN (2 emails)

### 1 — Inmediato (lead frío 60-90 días / ex cliente)

- **Eyebrow:** REACTIVACIÓN · CASO RECIENTE
- **Asunto:** +100.000€ en 6 meses, sin abrir un local nuevo
- **Preview text:** La oportunidad ya estaba ahí. Solo había que verla.
- **Cuerpo:**

Un restaurante de alta gama en Madrid funcionaba bien — pero no durante todo
el día. Al mirar los números, algo quedó muy claro: las horas de luz eran
mucho más rentables que las de noche. Con la ubicación y la terraza que
tenían, la pregunta no era cómo atraer más clientes. Era cómo aprovechar
mejor un espacio que ya tenía potencial para facturar mucho más.

La respuesta apareció al analizar lo que faltaba: no había una propuesta de
desayunos abierta al cliente externo, a pesar de tener ubicación, marca y
capacidad de sobra para captar esa demanda.

No hizo falta reforma ni gran inversión. Trabajamos sobre lo que ya existía:
ajustamos horarios, reorganizamos la operación y desarrollamos una oferta de
desayunos coherente con el posicionamiento del restaurante — porque llenar
mesas está bien, pero si no encaja con la marca, la diluye.

El resultado: una franja horaria infrautilizada se convirtió en una nueva
fuente de ingresos, con más de 100.000€ de facturación adicional en medio
año.

A veces el crecimiento no está en abrir otro local. Está en mirar lo que ya
tienes y ver lo que llevaba tiempo delante de tus ojos.

- **CTA:** ninguno.

---

### 2 — Día 7 (CTA de baja intención)

- **Eyebrow:** REACTIVACIÓN · ¿SEGUIMOS?
- **Asunto:** ¿Seguimos por aquí?
- **Preview text:** Sin rollos. Solo queremos saber si esto te sigue interesando.
- **Cuerpo:**

Hace tiempo que no sabemos de ti, y no pasa nada — no todo el mundo está en
el mismo momento. Pero antes de seguir mandándote cosas, preferimos
preguntar directamente: ¿te sigue interesando esto?

Si la respuesta es sí, no hace falta que hagas nada complicado — solo `haz
clic aquí` y seguimos como hasta ahora.

Si ahora mismo no es tu momento, también lo entendemos perfectamente. Puedes
darte de baja cuando quieras, sin explicaciones ni preguntas incómodas. Y si
más adelante te vuelve a interesar, aquí seguimos — con las manos en la
masa, como siempre.

- **CTA:** enlace de texto discreto **"haz clic aquí"** dentro del párrafo —
  no usar el botón grande de la plantilla, este email es intencionadamente de
  bajo compromiso.

---

## CAMPAÑA · Newsletter mensual (plantilla + ejemplo del mes)

Usar `plantilla-newsletter.html`. Ejemplo real ya redactado (sirve de
referencia de tono y estructura para los meses siguientes):

- **Asunto:** Lo que nos ha hecho pensar este mes
- **Preview text:** Honest Greens, tradición desde cero, y por qué a veces el dueño es el problema.
- **Intro:** Este mes hemos estado dándole vueltas a varias cosas. Aquí van
  las tres que más nos han hecho pensar — y una novedad que queremos
  compartir contigo.

**Historia 1**
- **Título:** Lo que decides NO hacer también es estrategia
- **Cuerpo:** Honest Greens podría añadir más platos, más categorías, más de
  todo. Y decide no hacerlo. Analizamos por qué ese "no" es tan importante
  como cualquier "sí" para el posicionamiento de un negocio.
- **Enlace:** Leer más →

**Historia 2**
- **Título:** ¿Puede un restaurante nuevo tener tradición desde el primer día?
- **Cuerpo:** No hace falta 50 años de historia. Hace falta algo que el
  cliente recuerde, repita y espere. Te contamos cómo se empieza a construir
  eso desde cero.
- **Enlace:** Leer más →

**Historia 3**
- **Título:** Si tu restaurante te necesita para funcionar, todavía no tienes un negocio
- **Cuerpo:** Una pregunta incómoda: si desaparecieras un mes, ¿qué dejaría
  de funcionar? La respuesta dice mucho sobre la estructura real de tu
  negocio.
- **Enlace:** Leer más →

**Novedad del mes**
- **Título:** La novedad del mes: Lady Madrid
- **Cuerpo:** Lady ya tenía las piezas — espacio con personalidad, comunidad,
  propuesta con potencial. Lo que faltaba era que esas piezas trabajaran
  juntas. Después de un año de acompañamiento, las ventas llegaron a
  duplicarse. Pero lo que más nos importa no fue esa cifra — fue que Lady
  pasó de funcionar desde la improvisación a funcionar desde el criterio.
- **Enlace:** Ver el caso completo →

**Cierre:** ¿Tu restaurante tiene las piezas pero todavía no funcionan
juntas? Hablemos.

*(Para los próximos meses: mismo esqueleto de 3 historias + 1 novedad,
reciclando contenido ya publicado en Instagram/LinkedIn ese mes, según marca
el calendario interno del excel.)*
