# Historial de cambios

Lo nuevo de cada versión de Affluence, de la más reciente a la más antigua.

## 0.2.7 · 16 de noviembre de 2026

### Nuevo
- **Constancia de situación fiscal y opinión de cumplimiento:** en Descargas, la pestaña
  "Documentos del SAT" baja los dos documentos de tus clientes con su e.firma, guarda el historial
  y te dice si la opinión salió positiva o negativa. También se puede programar.
- **Navega entre comprobantes relacionados:** desde el detalle de una factura abres sus complementos
  de pago, notas de crédito o sustituciones, pasas de uno a otro con "Anterior" y "Siguiente" y
  vuelves con "Regresar". También con Alt + flecha izquierda y derecha.
- **Copia los folios fiscales relacionados con un clic,** todos juntos o uno por uno.
- **El recibo de nómina en pantalla:** periodo, días pagados, percepciones, deducciones, otros
  pagos, horas extra, incapacidades e impuestos retenidos, con cada clave traducida.
- **Impuestos de los pagos:** el detalle de un complemento de pago muestra sus totales y los
  impuestos trasladados y retenidos de cada pago.
- **Más datos de tus comprobantes:** residencia fiscal y registro tributario del receptor
  extranjero, números de pedimento y operaciones a cuenta de terceros. Lo que ya tenías descargado
  se completa solo al actualizar.
- **Factura global identificada** en el detalle, con su periodicidad, meses y año.
- **Exportar la e.firma de un cliente:** quien administra puede entregarle a su cliente la e.firma
  guardada en Affluence, después de confirmar su contraseña.
- **Pedimentos en el reporte por concepto:** una columna nueva, antes de la clave de producto.

### Mejoras
- **Reportes de Excel con las claves traducidas:** moneda, forma y método de pago, tipo de
  relación, objeto de impuesto y los datos de nómina salen con su clave y su descripción del
  catálogo del SAT.
- **El detalle muestra primero lo importante:** conceptos, impuestos y desgloses a la vista; los
  comprobantes relacionados salen cerrados y se abren con "Mostrar".
- **Respaldos verificados más a la vista:** el panel muestra cinco respaldos sin desplazarte.
- **Programaciones más claras:** cada una dice de quién es, y eliges cada cuántos días se vuelve a
  consultar la vigencia (de 1 a 30).
- Tablas del detalle con todas sus columnas y menos memoria al instalar los catálogos del SAT.

### Correcciones
- En los reportes de nómina, el estado ahora sale con su nombre y no con el país.

## 0.2.6 · 15 de noviembre de 2026

### Nuevo

- **Eliminar un cliente y entregarle lo suyo.** Antes de eliminar, exportas su expediente completo desde el mismo diálogo. Ya no hay que esperar el plazo de conservación: confirmas que entregaste la información, escribes el RFC y listo.
- **Consultar el estado ante el SAT de todos tus clientes a la vez**, desde la búsqueda general, con avance y botón para cancelar.
- **Modo de una sola persona.** Si trabajas solo, ya no ves usuarios, roles ni permisos. Si después compartes el equipo, enciendes "Varios usuarios en este equipo" en Configuración, Avanzado.
- **Resumen de descargas más claro.** Cada cliente muestra cuántos comprobantes son nuevos, cuántos ya tenías y cuántos están cancelados, con el desglose de emitidos y recibidos.
- **Programaciones de tu equipo.** Cada persona crea las suyas, y quien administra o gerencia puede verlas y ajustarlas cuando varias personas comparten el equipo.
- **Cada descarga actualiza el estado ante el SAT de todo el periodo.** Al terminar, Affluence vuelve a preguntar al SAT por los comprobantes nuevos y por los que ya tenías de ese periodo, y te dice cuántos siguen vigentes, cuántos están cancelados y cuántos cambiaron.
- **Marcar un hallazgo como revisado.** En Validación, los hallazgos que ya atendiste dejan de aparecer; con "Ver revisados" los vuelves a mostrar.

### Mejoras

- **Tablas que no recortan lo importante.** RFC, fechas, montos, conteos y estado se ven completos en Clientes, CFDI, Certificados, Usuarios, Validación, Folios repetidos, Bitácora, historial de descargas y Respaldos. Si la ventana es angosta, la tabla se desplaza hacia los lados.
- **La consulta que pides a mano siempre pregunta al SAT.** El botón "Consultar estado ante el SAT" ya no se salta comprobantes consultados hace poco.
- **Iconos del menú más grandes y claros**, ficha del cliente sin textos cortados e historial de respaldos completo.
- **"Acerca de Affluence" ahora sí habla de Affluence:** versión, qué hace y dónde se quedan tus datos.

- **Descargas más tranquilas con el SAT.** Affluence reparte un número limitado de conexiones entre todos tus clientes y baja el ritmo solo cuando el SAT se satura, para que tus descargas terminen sin que tengas que vigilarlas.
- **Menos distracciones mientras descargas.** La selección de clientes queda bloqueada con la nota "Descarga en curso", y el aviso de periodos largos aparece solo cuando la descarga ya lleva más de 20 minutos.
- **El aviso de que terminó la descarga se queda hasta que lo cierres.** Ya no se pierde si te levantaste un momento.
- **Más rapidez al consultar.** Más pantallas leen tu información sin esperar a que termine otra tarea, así que la búsqueda, el detalle y las listas responden con más soltura aunque haya una importación en marcha.
- **Actualizaciones con más respaldo.** El programa verifica las actualizaciones con una segunda llave de reserva, para que las versiones futuras lleguen aunque cambie la llave principal.
- **Guías de la Ayuda al día.** Nuevas secciones sobre qué hacer cuando el SAT se satura, cómo eliminar un cliente y cómo trabajar solo o en equipo.
- **Importar XML dice "ya existentes"** en lugar de "ya estaban", para nombrar mejor lo que ya tenías.

### Correcciones

- **Las ventanas "Acerca de" y "Licencias de terceros" ya no reaparecen** al cambiar de sección.
- **La consulta de vigencia por periodo incluye el último día** del rango.

- **Permisos más estrictos.** Se cerraron varios huecos para que cada persona vea y haga solo lo que le corresponde: un gerente ya no conserva alcance sobre clientes que se le quitaron, y las tareas visibles dependen de lo que cada quien puede hacer.
- **Sesión y bóveda más seguras.** Al cambiar tu contraseña, tus otras sesiones se cierran de verdad, y la e.firma solo se abre cuando la bóveda lo permite.
- **El alcance del gerente ya no crece solo** al asignar clientes a otras personas.
- **Un error en una lectura ya no detiene todo el programa.**

## 0.2.5 · 14 de noviembre de 2026

### Nuevo
- **Mantener sesión iniciada:** marca la casilla al entrar, elige 15, 20, 30 o 60 días y Affluence
  abre directo en ese equipo. Tu contraseña nunca se guarda; al cerrar sesión o cambiarla, el equipo
  te la vuelve a pedir.
- **Buscador en todos tus clientes:** la caja de la barra superior busca folio fiscal, RFC o nombre
  en todos los clientes que puedes ver. En CFDI eliges entre "Cliente activo" y "Todos".
- **Nombre y carpetas del expediente a tu gusto:** tú decides con qué datos se nombra cada XML y su
  PDF, y cómo se ordenan las carpetas (año, mes, emitidos o recibidos).
- **Descargas con avance por cliente:** cada cliente muestra su estado durante la descarga y el
  resumen final dice cuántos se completaron y cuántos quedaron pendientes por el SAT.
- **Reintentar pendientes:** vuelve a descargar solo los clientes y periodos que el SAT no entregó.
- **Almacenamiento por categoría** en Configuración: cuánto ocupan catálogos, descargas, PDF y
  reportes, y acceso directo a la carpeta "Mis archivos".

### Mejoras
- **Descargas más rápidas y firmes:** el doble de bajadas a la vez. Si el SAT rechaza el acceso de un
  cliente, la descarga sigue con los demás y ese cliente queda pendiente en lugar de perderse.
- El expediente incluye siempre su resumen, genera los PDF que falten y clasifica cada comprobante
  por su vigencia real.
- Los avisos dicen el RFC y el nombre del cliente, y su botón "Ver" abre el resultado.
- Las tarjetas e indicadores de Inicio llevan a su pantalla.
- Ayudas (i) en todas las pantallas, fechas con un solo formato y controles con el mismo estilo.
- Affluence limpia sola sus archivos internos viejos; tus XML, PDF y reportes no se tocan.

### Correcciones
- El expediente ya encuentra los PDF generados antes.
- Al borrar un cliente también se borran sus archivos exportados.

## 0.2.4 · 13 de noviembre de 2026

### Nuevo
- **Alta de cliente desde la e.firma:** al dar de alta un cliente, Affluence toma el RFC y el nombre
  del certificado y guarda la e.firma en el mismo paso.
- **PDF desde la pantalla CFDI:** botón PDF en cada renglón y "Generar PDF de seleccionados", por
  renglones marcados o por todos los resultados del filtro.
- Filtro **Todos, Emitidos o Recibidos** en CFDI.
- **Detalle del comprobante ordenado como la factura:** emisor y receptor lado a lado, claves con su
  descripción, conceptos siempre a la vista y botón Copiar en el folio fiscal y los RFC. Una factura
  a crédito lleva a sus complementos de pago, y el complemento a las facturas que paga.
- **Primeros pasos** en Inicio y pantalla **Ayuda** con guías y "Buscar actualizaciones".
- **Historial de reportes y expedientes**, con "Abrir archivo" y "Abrir carpeta".
- Gráfica de comprobantes por mes en Inicio.
- Cambio de la llave de la bóveda desde Configuración.

### Mejoras
- **Descargas más rápidas:** el listado del SAT se pide por mes completo en lugar de día por día.
  La sesión del SAT se reutiliza 10 minutos por cliente. Si un XML falla, se reintenta solo ese.
  Si el SAT se satura, la descarga hace una pausa y continúa.
- La barra de descarga dice en qué paso va ("Paso 1 de 3") y avanza por comprobante. Avisa cuando
  está reintentando con el SAT.
- Nombres de pantallas, reglas y avisos en lenguaje claro. Las reglas salen ordenadas por gravedad.
- Las tarjetas de Inicio llevan a su pantalla.
- Pantallas ajustadas para ventanas pequeñas: filtros y tablas ya no se cortan.
- Al cambiar tu contraseña se cierran las demás sesiones abiertas con tu usuario.
- Un gerente solo puede archivar sus clientes y los de sus auxiliares.
- Si un PDF por grupo, un expediente o una vista previa sale recortado por su tamaño, ahora lo avisa.

### Correcciones
- El selector desplegable no cambiaba de opción al elegirla.
- El IVA por concepto salía mal en algunos comprobantes.
- La descarga masiva fallaba con archivos de más de 10 MB.
- El respaldo fallaba con bases de más de 4 GB.
- Los catálogos solo se aceptan de los servidores del SAT.

## 0.2.3 · 3 de noviembre de 2026

### Nuevo
- El selector de cliente de la barra superior abre una lista para cambiar de cliente ahí mismo,
  con buscador cuando hay más de 8 clientes y la opción "Ver todos los clientes".
- Al cerrar la ventana, Affluence se queda en la bandeja de Windows, junto al reloj. Desde su
  ícono puedes volver a abrirlo, "Salir de Affluence" (las descargas y tareas programadas siguen)
  o "Salir y detener el servicio".

### Correcciones
- Elegir un cliente en la pantalla Clientes no lo dejaba como cliente activo.
- Validación se quedaba con el primer cliente aunque eligieras otro.
- En periodos largos, si el SAT rechazaba la conexión al iniciar sesión, se perdía un tramo entero
  de años. Ahora el inicio de sesión se reintenta antes de darlo por perdido.
- Al detener la verificación de vigencia ya no se pierde la respuesta que el SAT acababa de dar.

## 0.2.2 · 3 de noviembre de 2026

### Nuevo
- Todas las descargas van por el portal del SAT con la e.firma, para cualquier periodo, incluso
  varios años de una vez. El servicio de descarga masiva del SAT ya no se usa: tardaba días y sus
  solicitudes caducaban.

### Mejoras
- **Una descarga nunca parece completa si falta algo.** Si el SAT no deja revisar algún día o algún
  XML no baja después de 3 intentos, la descarga dice "quedó incompleta" con las fechas exactas y
  cuántos XML faltan. Lo que sí bajó queda guardado.
- Si no se pudo bajar nada por una sola causa (sin internet, conexión segura bloqueada, SAT sin
  responder), el aviso nombra esa causa y su código de soporte.
- La revisión del portal reintenta sola cada día que falla y sigue con los demás.
- La verificación de vigencia en el SAT es hasta 6 veces más rápida (4 consultas a la vez) y
  reintenta sola antes de marcar un comprobante como "sin respuesta".
- Pantallas, diálogos y letras más nítidos en Windows.

### Correcciones
- En "Cambiar mi contraseña" el texto del pie empujaba fuera los botones Cancelar y Cambiar
  contraseña.

## 0.2.1 · 3 de noviembre de 2026

### Nuevo
- Actualización automática: Affluence avisa cuando hay una versión nueva y, al aceptar, hace un
  respaldo, instala y se vuelve a abrir. Cada actualización va firmada y se comprueba antes de
  instalarse.

### Mejoras
- Los respaldos viejos se limpian solos: se conservan los de los últimos 7 días, 4 semanas y 6
  meses, nunca menos de 2 verificados.
- Si al restaurar un respaldo falta algún archivo, se ve en Configuración.
- Los XML se guardan exactamente como los entrega el SAT, byte por byte.

## 0.2.0

Primera versión de la beta.
