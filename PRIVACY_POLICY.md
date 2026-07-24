# Política de privacidad — Kanji Unlock

_Última actualización: 24 de julio de 2026_

Kanji Unlock es una aplicación de repaso de kanji que funciona por completo en
tu dispositivo.

## Datos que recopilamos
La aplicación **no recopila datos de forma automática**: no incluye analíticas,
publicidad ni SDKs de terceros, y no solicita cuenta ni inicio de sesión. No hay
ningún envío de información en segundo plano.

La **única** vez que la app transmite información por Internet es cuando **tú
decides enviar un reporte** de un problema desde un reto (el botón de la
bandera). En ese caso se envía solo lo necesario para corregir el contenido:

- el kanji y el tipo de reto reportado,
- la categoría y el mensaje que escribes,
- la versión de la app, el modelo del dispositivo y la versión de Android.

El reporte se envía al desarrollador (a través de un servicio de Google Apps
Script) con el único fin de arreglar errores en los datos de kanji. No se
recopila nada más, y nunca se envía nada sin que tú lo pidas. Si prefieres no
transmitir nada, puedes enviar el mismo reporte por tu propia app de correo.

## Datos que se guardan en tu dispositivo
Tu progreso de estudio y tus preferencias se guardan localmente en el
almacenamiento privado de la app. Esta información nunca sale del dispositivo y
se elimina si desinstalas la aplicación.

## Permisos y su motivo
- **Acceso a Internet** (`INTERNET`): únicamente para enviar un reporte cuando
  tú lo pides desde un reto. No se usa para nada más.
- **Mostrar sobre otras apps** (`SYSTEM_ALERT_WINDOW`): para dibujar el reto de
  kanji encima de la pantalla al desbloquear.
- **Servicio en primer plano** (`FOREGROUND_SERVICE`, `..._SPECIAL_USE`): para
  detectar el desbloqueo y mostrar el reto.
- **Notificaciones** (`POST_NOTIFICATIONS`): solo la notificación permanente que
  Android exige mientras el servicio está activo.
- **Iniciar al arrancar** (`RECEIVE_BOOT_COMPLETED`): para reactivar el servicio
  tras reiniciar el teléfono.
- **Wake lock** (`WAKE_LOCK`): para presentar el reto de forma fiable al
  desbloquear.

Salvo el envío de reportes que tú inicias (descrito arriba), ninguno de estos
permisos se usa para recolectar ni transmitir información.

## Niños
La app no está dirigida a menores de 13 años y no recopila datos de nadie.

## Cambios
Si esta política cambia, se actualizará la fecha del encabezado.

## Contacto
alejoxbg@gmail.com
