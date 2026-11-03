# Guía rápida

De cero a tus primeros comprobantes en seis pasos. El menú de la izquierda tiene todas las
pantallas.

## 1. Da de alta a tu cliente

**Clientes** → agregar. Basta con el **nombre** y el **RFC**. Si el RFC ya existe, Affluence te
avisa antes de duplicarlo.

## 2. Carga su e.firma

En el cliente, carga el `.cer`, el `.key` y escribe la contraseña de la llave. Affluence comprueba
que la contraseña abre la llave y que la llave corresponde al certificado, y la guarda **cifrada**
en tu equipo. Sin e.firma no se pueden descargar sus comprobantes.

## 3. Descarga del SAT

**Descargas** → elige el cliente, emitidos, recibidos o ambos, y el periodo. Puedes pedir varios
años de una vez: Affluence revisa el portal del SAT **día por día**.

- Si el SAT falla, Affluence reintenta solo.
- Si aun así falta algo, la descarga dice **"quedó incompleta"** y nombra los días y cuántos XML
  faltan. Vuelve a pedir el mismo periodo más tarde: lo que ya está no se baja dos veces.
- Si dice "terminada" sin avisos, se revisaron todos los días del periodo.

## 4. Busca y revisa

**CFDI** → busca por folio fiscal, RFC o nombre (también con **Ctrl+F** desde cualquier pantalla).
Haz clic en un comprobante para ver su detalle: estatus en el SAT, alertas de la lista 69-B
(EFOS), conceptos, impuestos y pagos. Abajo están **Abrir el XML** y **Abrir el PDF**.

## 5. Revisa la vigencia y los hallazgos

- **Validación** muestra los hallazgos de las reglas fiscales (EFOS, PPD sin complemento de pago,
  cancelados, etc.).
- El estatus en el SAT (vigente o cancelado) se consulta solo; también puedes pedirlo desde la
  búsqueda.

## 6. Saca tus archivos

- **Reportes**: los libros de Excel. Al terminar, el botón **Abrir la carpeta** te lleva a ellos.
- **Operaciones**: PDF masivo y expediente en ZIP del periodo, también con **Abrir la carpeta**.

## Para no olvidar

- **Programa** descargas, reportes y expedientes para que se hagan solos (en cada operación,
  opción de programar).
- **Respaldos**: Affluence respalda todos los días. Revísalos en Configuración → Almacenamiento.
- ¿Algo raro? Mira [cómo reportarlo](COMO-REPORTAR.md).
