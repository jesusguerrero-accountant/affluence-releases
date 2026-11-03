# Historial de cambios

Lo nuevo de cada versión de Affluence, de la más reciente a la más antigua.

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
