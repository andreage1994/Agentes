# Análisis — Ventas por franja horaria vs. personal (Plaza República Dominicana)

**Pedido por Andrea, 2026-10-19:** cruzar las ventas reales por franja
horaria con los horarios de personal ya documentados en 6.d (Staffing) de
`Estrategia-y-Modelo-Operativo-Lady-Madrid.md`, para ver si los recursos
de personal se están usando bien. Fuente de ventas:
`fuentes/Ventas_por_Centro_de_Venta_y_Periodos_de_Servicio_01-19oct2026.pdf`
(informe del TPV, 01/10/2026 – 19/10/2026).

**Confirmación de local:** el informe no indica qué local es, pero los 3
centros de venta que usa (Llevar / Barra / Terraza) y la distribución de
mesas coinciden exactamente con la configuración de Plaza República
Dominicana ya documentada en 6.d (10 mesas interior + 2 taburetes de
barra + 6 mesas de terraza, 44 plazas) — no con Parquesur, de la que solo
tenemos staffing y no detalle operativo. Doy por hecho que este informe
es de Plaza República Dominicana; indícame si no es así.

## Dato real del informe (franja a franja)

| Franja | Operaciones | Ventas | Llevar | Barra | Terraza |
|---|---|---|---|---|---|
| 7-8 | 27 | 130,30 € | 79,30 € | 38,50 € | 12,50 € |
| 8-9 | 198 | 1.436,30 € | 543,10 € | 672,80 € | 220,40 € |
| 9-10 | 220 | 1.745,40 € | 573,80 € | 797,40 € | 374,20 € |
| 10-11 | 231 | 2.466,20 € | 520,80 € | 1.327,50 € | 617,90 € |
| 11-12 | 247 | 2.498,30 € | 358,70 € | 1.185,50 € | 954,10 € |
| 12-13 | 230 | 2.886,55 € | 378,70 € | 1.405,05 € | 1.102,80 € |
| 13-14 | 129 | 1.556,50 € | 159,90 € | 493,15 € | 903,45 € |
| 14-15 | 127 | 1.247,50 € | 261,10 € | 462,35 € | 524,05 € |
| 15-16 | 100 | 822,30 € | 339,50 € | 154,40 € | 328,40 € |
| 16-17 | 143 | 1.076,15 € | 368,15 € | 318,00 € | 390,00 € |
| 17-18 | 158 | 1.172,00 € | 278,75 € | 446,35 € | 446,90 € |

**Importante — el informe parece estar cortado.** El gráfico de barras de
la propia página incluye categorías "18-19" y "Resto" (ordenadas por
volumen, no cronológicamente), pero la tabla numérica no las recoge — se
corta justo en 17-18. Esto es significativo porque el horario real
documentado en 6.d llega hasta las 20:30h (L-J) o incluso más tarde según
la captura de Google todavía sin confirmar (9:30-21:30h), y 6.d ya señala
un **pico real de clientes entre las 16:00 y las 19:00h**. Con los datos
que tengo no puedo confirmar ni descartar ese pico — necesito el tramo de
17-18h en adelante para terminar este análisis con rigor. Te lo marco
como pendiente más abajo.

**Otra limitación real:** el periodo (01-19 oct, 19 días) mezcla días
entre semana y fines de semana en una sola cifra por franja. 6.d dice que
el patrón de personal es distinto entre semana (apertura en solitario →
+1 a media mañana → relevo a primera hora de la tarde → solitario hasta
el cierre) y fin de semana (4 personas por la mañana, que es la franja
más intensa de toda la semana). Sin desglose por tipo de día, una franja
"12-13" puede estar reflejando sobre todo sábados/domingos con cuatro
personas, o entre semana con dos — y la lectura correcta de "¿están bien
usados los recursos?" cambia según cuál sea. Lo dejo también como
pendiente.

## Lo que sí se puede leer con lo que tenemos

**El pico real de facturación es 10h-13h, no el mediodía clásico de
sobremesa.** Esas tres franjas (2.466,20 € + 2.498,30 € + 2.886,55 €) son
el 46% de toda la facturación visible en el informe (7h-18h), en solo 3
de las 11 franjas. Esto encaja con la lógica de 6.d: en fin de semana,
precisamente esta franja es donde se concentran las 4 personas del
equipo (franja de más intensidad de toda la semana); entre semana, es
también cuando ya están las dos personas de la mañana trabajando juntas,
justo antes del relevo de primera hora de la tarde. **Conclusión
provisional: el refuerzo de personal ya está puesto donde está el pico
real de facturación** — no parece haber un desajuste aquí, aunque el
cruce exacto necesitaría el desglose por tipo de día para confirmarlo del
todo.

**La franja más floja (15-16h) coincide con el tramo donde, entre semana,
solo hay una persona.** 100 operaciones, 822,30 € — la cifra más baja de
toda la tabla, tanto en operaciones como en importe. Esto es coherente
con la plantilla ajustada de 6.d: el momento de menos actividad real es
también el momento de menos cobertura. Otro punto a favor de que el
patrón actual sí responde a la demanda real, al menos en las horas que
cubre este informe.

**Llevar (para llevar) es más fuerte muy temprano (8h-10h) y decae
después.** Coherente con un patrón de café/desayuno de paso rápido —
necesita velocidad de despacho más que servicio de mesa, lo que encaja
con que el arranque L-J sea en solitario: el perfil de demanda temprana
pide menos "servicio de mesa" y más "despacho rápido en barra/mostrador".

**Terraza crece de forma sostenida hasta su pico en 12-13h (1.102,80 €) y
vuelve a subir ligeramente en 16-17h/17-18h.** Esto es justo la zona que
6.d y 3.c ya señalan como la que "tiende a quedarse sin cobertura en los
momentos de más afluencia" cuando la polivalencia tiene que repartirse
entre barra, sala y terraza. El dato real no contradice esa alerta ya
escrita — la sostiene. Si el tramo 18-19h en adelante confirma que la
terraza sigue fuerte (algo muy probable, dado el pico de tarde-noche ya
documentado), este sería el punto más claro donde sí merece la pena
revisar si el refuerzo de la segunda persona de tarde fin de semana llega
a tiempo o tarde.

## Lo que necesito de tu lado para cerrar este análisis

1. **El informe completo**, con las franjas desde 18-19h hasta el cierre
   real (20:30h o más tarde, según se resuelva la discrepancia de
   horario que sigue abierta en 6.d) — el export actual se corta en
   17-18h aunque el propio gráfico muestra que hay más datos ("18-19",
   "Resto").
2. **El mismo informe desglosado por tipo de día** (entre semana /
   viernes-festivos / fin de semana), si el TPV lo permite — sin eso,
   cualquier conclusión sobre si el personal está "bien usado" en una
   franja concreta se queda en probable, no en confirmado, porque 6.d ya
   documenta que la plantilla cambia radicalmente entre tipos de día.
3. Con esos dos datos, cierro si la franja 16:00-19:00h (el pico que ya
   documentamos) está realmente bien cubierta por el refuerzo de la
   segunda persona de tarde-fin de semana, o si hace falta ajustar cuándo
   entra.
