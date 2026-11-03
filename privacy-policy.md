# Política de privacidad de Fit Metrics

**Versión 3** · **Última actualización:** 3 de noviembre de 2026

## Introducción

**Misticode** creó la app **Fit Metrics** como una app gratuita con fines comerciales. **Misticode** presta este SERVICIO y está pensado para usarse tal como está.

Esta página informa a los visitantes sobre nuestras políticas de recopilación, uso y divulgación de Información Personal si deciden usar nuestro Servicio.

Si eliges usar nuestro Servicio, aceptas la recopilación y el uso de información según esta política. La Información Personal que recopilamos se usa para prestar y mejorar el Servicio. No usaremos ni compartiremos tu información con nadie, salvo como se describe en esta Política de privacidad.

## Información que recopilamos y cómo la usamos

Para que tengas una mejor experiencia al usar nuestro Servicio, podemos pedirte cierta información que te identifica personalmente. La información que pedimos la conservamos y la usamos como se describe en esta política de privacidad.

### 1. Información personal
Para crear tu cuenta y administrar tu perfil, podemos recopilar:
* Nombre
* Correo electrónico
* Foto de perfil (opcional). Si agregas una, se guarda en nuestros servidores y se muestra en tu perfil y al equipo de los centros donde tienes una membresía.

### 2. Datos físicos y de salud
Para calcular métricas de entrenamiento precisas (como Calorías y TRIMP), podemos pedirte:
* Edad o fecha de nacimiento
* Género
* Peso
* Altura
* Frecuencia cardíaca en reposo y máxima, y nivel de actividad
* **Datos de frecuencia cardíaca:** recopilamos en tiempo real los datos de frecuencia cardíaca de los dispositivos conectados durante tus sesiones de entrenamiento. **Estos datos se usan exclusivamente para mostrar tu rendimiento y calcular la intensidad del entrenamiento.** No vendemos tus datos de salud a terceros ni los usamos con fines publicitarios.
* **Historial de entrenamiento:** las sesiones que registras, sus resúmenes y los récords personales que ingresas (tus pesos máximos).

### 3. Ficha de salud (opcional)
Puedes completar una ficha de salud en tu perfil. Puede contener:
* Condiciones médicas y alergias
* Historial de lesiones
* El nombre y el teléfono de un contacto de emergencia

Esta información se guarda solo si das tu consentimiento explícito en la app. Solo la ven los coaches de los centros donde tienes una membresía vigente (activa o congelada), para cuidar tu seguridad durante el entrenamiento. No la usamos para publicidad y no la vendemos.

Puedes borrarla en cualquier momento vaciando los campos en tu perfil o eliminando tu cuenta. El registro de tu consentimiento se borra junto con los datos. Asegúrate de que tu contacto de emergencia esté de acuerdo en aparecer en ella.

### 4. Membresía en un centro y reservas
Si te unes a un centro que usa Fit Metrics, guardamos la información necesaria para administrar tu membresía en él:
* Tu membresía, tu plan y los créditos que te quedan
* Las clases que reservas y cancelas
* Los registros de pago que tu centro ingresa para tu plan. La app no procesa pagos ni guarda datos de tarjetas.
* Tu aceptación del acuerdo del centro
* Notas privadas que el equipo del centro puede llevar sobre ti

Cuando te unes a una clase en vivo con un monitor de frecuencia cardíaca, tu nombre y tus datos de frecuencia cardíaca en vivo se muestran en la pantalla del centro para que tú y tu coach puedan seguir el entrenamiento.

### 5. Permisos del dispositivo
La app necesita permisos específicos para funcionar correctamente:
* **Bluetooth:** para buscar y conectar monitores de frecuencia cardíaca externos.
* **Cámara:** para escanear el código QR de tu clase, tomar una foto de fondo para los entrenamientos que compartes y, si administras un centro, fotografiar su logo.
* **Fotos/Galería:** para que elijas tu foto de perfil, el fondo de los entrenamientos que compartes o el logo de tu centro, y para guardar o compartir las imágenes de resumen de entrenamiento que genera la app.
* **Ubicación:** en algunas versiones de Android, el permiso de ubicación es técnicamente necesario para buscar dispositivos Bluetooth Low Energy. No rastreamos, no guardamos ni compartimos tu historial de ubicación física.
* **Notificaciones:** para mostrar en tu teléfono los avisos de tu plan (ver la sección 6) y, en Android, la notificación «Entrenamiento en curso» mientras registras una sesión de entrenamiento. Es opcional: sin este permiso no registramos ningún token de notificaciones, y los mensajes igual aparecen en el inicio de la app.

### 6. Mensajes de tu centro y notificaciones
Los centros donde tienes una membresía pueden enviarte estos mensajes en la app:
* **Avisos de tu plan:** 3 días antes de que venza tu plan, el día en que vence y 3 días después, si no lo renovaste.
* **Saludo de cumpleaños:** el día de tu cumpleaños, en el inicio de la app.

Los textos los escribe el equipo de tu centro, o son los predeterminados de Fit Metrics. Para armar cada mensaje usamos tu nombre, el nombre del centro y de tu plan, la fecha en que vence tu plan y el día y el mes de tu fecha de nacimiento. El texto queda fijo al crear el mensaje.

Guardamos en nuestros servidores cada mensaje que recibes: su texto, el centro que lo envía, el plan y la fecha de término a los que se refiere, el día en que se creó, si lo cerraste, si se canceló (por ejemplo, porque renovaste tu plan) y si se envió su notificación. El equipo de tu centro escribe los textos, pero no ve a quién se envió cada mensaje ni si lo cerraste. Si eres parte del equipo de un centro, guardamos quién editó por última vez cada mensaje del centro y cuándo.

#### Notificaciones push
Si tu teléfono permite las notificaciones de Fit Metrics, los avisos de tu plan también te llegan como notificación:
* Para enviarlas usamos Firebase Cloud Messaging (FCM), un servicio de Google. Tu teléfono obtiene de FCM un token de notificaciones: un identificador de esta instalación de la app, que no contiene tu nombre ni tu correo. Lo guardamos en nuestros servidores con tu cuenta, el tipo de teléfono (iPhone o Android) y las fechas en que se registró.
* Solo registramos el token si tu teléfono permite las notificaciones de Fit Metrics. Si aún no las permite, en iPhone y en Android 13 o posterior la app te pide permiso; si ya están permitidas (por ejemplo, porque las activaste en los ajustes del teléfono), registramos el token sin preguntarte. En versiones anteriores de Android vienen permitidas, salvo que las desactives en los ajustes del teléfono. Sin ese permiso no guardamos ningún token, y los mensajes igual aparecen en el inicio de la app.
* Al abrir la app, tu teléfono puede obtener un token de FCM (y, en iPhone, uno de Apple) aunque no permitas las notificaciones: esos tokens no se envían a nuestros servidores y no los usamos.
* Para entregar cada notificación, enviamos su título y su texto (que pueden incluir tu nombre, el nombre de tu centro y de tu plan y la fecha en que vence) a Firebase Cloud Messaging. En iPhone, FCM la entrega a través del servicio de notificaciones push de Apple (Apple Push Notification service, APNs). La notificación también lleva el tipo de mensaje e identificadores internos del mensaje y del centro, que la app usa para abrir el inicio.
* Nuestros registros técnicos de los envíos no guardan el token, el texto del mensaje ni tu nombre.

#### Cómo dejar de recibirlos
* **«Avisos de tu plan»:** viene encendido. Apágalo en **Notificaciones**, en el menú lateral de la app, y dejarán de llegarte las notificaciones de tu plan. El cambio rige de inmediato. Las tarjetas de tu plan siguen apareciendo en el inicio de la app.
* **Ajustes del teléfono:** si desactivas ahí las notificaciones de Fit Metrics, el teléfono deja de mostrarlas y la app borra el token la próxima vez que la abras.
* **«Cerrar mensaje»:** cierra una tarjeta del inicio. Esa tarjeta no vuelve a aparecer en ninguno de tus teléfonos.
* **Cerrar sesión** en un teléfono borra su token, y ese teléfono deja de recibir tus notificaciones.
* **Eliminar tu cuenta** borra tus mensajes, tus tokens y tus preferencias de notificaciones (ver «Conservación y eliminación de datos»).

#### Cuánto tiempo los guardamos
* **Token de notificaciones:** hasta que cierres sesión en ese teléfono, desactives las notificaciones (se borra la próxima vez que abras la app) o elimines tu cuenta. También lo borramos cuando FCM, al enviarte un mensaje, nos indica que ya no es válido (por ejemplo, porque desinstalaste la app).
* **Mensajes:** mientras tengas tu cuenta. Se borran al eliminarla.
* **Preferencia «Avisos de tu plan»:** guardamos solo tu última elección, con su fecha y la versión del texto que viste, mientras tengas tu cuenta.
* **Registro de quién editó cada mensaje:** si eres parte del equipo de un centro, se conserva hasta que alguien vuelva a editar ese mensaje, también después de eliminar tu cuenta.

## Quién puede ver tu información

* **Tú**, en la app.
* **El equipo de los centros donde tienes una membresía:** tu nombre, correo electrónico, foto de perfil, cumpleaños, membresía y reservas.
* **Los coaches de esos centros:** tu ficha de salud, solo mientras tu membresía esté vigente.
* **Las personas presentes en el centro durante una clase en vivo:** tu nombre y tus datos de frecuencia cardíaca en vivo en la pantalla del centro.
* **Google y, en iPhone, Apple:** el título y el texto de cada notificación que te enviamos, para entregarla en tu teléfono (sección 6).
* **Misticode**, para operar, mantener y dar soporte al Servicio.

No vendemos tu información personal y no usamos tus datos de salud para publicidad.

## Servicios de terceros

La app usa servicios de terceros que pueden recopilar información que te identifica.
Enlaces a las políticas de privacidad de los proveedores de servicios de terceros que usa la app:

* [Google Play Services](https://policies.google.com/privacy)
* [Google Analytics para Firebase](https://firebase.google.com/policies/analytics)
* [Firebase Crashlytics](https://firebase.google.com/support/privacy/)
* [Firebase](https://firebase.google.com/support/privacy/) (Authentication, Cloud Firestore, Realtime Database, Cloud Storage, Remote Config y Performance Monitoring) y [Google Cloud](https://cloud.google.com/terms/cloud-privacy-notice), que alojan nuestra base de datos, archivos y servidores.
* [Firebase Cloud Messaging](https://firebase.google.com/support/privacy/), que envía las notificaciones push (sección 6).
* [Servicio de notificaciones push de Apple (APNs)](https://www.apple.com/legal/privacy/), por el que llegan las notificaciones a iPhone.

## Cookies

Las cookies son archivos con una pequeña cantidad de datos que se usan comúnmente como identificadores únicos anónimos. Los sitios web que visitas los envían a tu navegador y se guardan en la memoria interna de tu dispositivo.

Este Servicio no usa estas «cookies» de forma explícita. Sin embargo, la app usa código y bibliotecas de terceros (como Firebase) que pueden usar «cookies» u otros identificadores para recopilar información y mejorar sus servicios. La app no tiene un ajuste para aceptarlos o rechazarlos.

## Proveedores de servicios

Podemos contratar a empresas y personas externas por las siguientes razones:
* Para facilitar nuestro Servicio;
* Para prestar el Servicio en nuestro nombre;
* Para realizar servicios relacionados con el Servicio; o
* Para ayudarnos a analizar cómo se usa nuestro Servicio.

Queremos que sepas que estos terceros tienen acceso a tu Información Personal. El motivo es realizar las tareas que les asignamos en nuestro nombre. Sin embargo, están obligados a no divulgar ni usar la información para ningún otro fin.

## Seguridad

Valoramos tu confianza al entregarnos tu Información Personal, por lo que nos esforzamos por usar medios comercialmente aceptables para protegerla. Pero recuerda que ningún método de transmisión por internet ni de almacenamiento electrónico es 100 % seguro y confiable, y no podemos garantizar su seguridad absoluta.

## Privacidad de los niños

Estos Servicios no están dirigidos a menores de 13 años. No recopilamos a sabiendas información de identificación personal de menores de 13 años. Si descubrimos que un menor de 13 años nos entregó información personal, la borramos de inmediato de nuestros servidores. Si eres madre, padre o tutor y sabes que tu hijo o hija nos entregó información personal, contáctanos para que podamos tomar las medidas necesarias.

## Conservación y eliminación de datos

Conservamos tu información personal solo durante el tiempo necesario para los fines descritos en esta Política de privacidad. Tienes derecho a solicitar la eliminación de tu cuenta. Puedes hacerlo directamente desde tu perfil en la app o escribiendo a nuestro correo de soporte.

Eliminar tu cuenta:
* Borra tu perfil y tu foto de perfil, tus sesiones de entrenamiento (incluidos los datos de frecuencia cardíaca), tus récords personales y tu ficha de salud.
* Borra las notas privadas que el equipo de los centros llevaba sobre ti.
* Borra los mensajes de tus centros, tus tokens de notificaciones y tus preferencias de notificaciones.
* Cancela tus reservas de clases futuras.

Los centros donde fuiste miembro conservan el historial de tus membresías, pagos y reservas de clases pasadas como parte de sus registros comerciales. Esos registros pueden incluir tu nombre y tu correo electrónico. Si fuiste parte del equipo de un centro, el registro de quién editó por última vez cada mensaje del centro, y cuándo, se conserva hasta que alguien vuelva a editar ese mensaje.

Revisa [Solicitar la eliminación de la cuenta](deletion.md) para ver los pasos.

## Cambios a esta Política de privacidad

Podemos actualizar nuestra Política de privacidad de vez en cuando, así que te recomendamos revisar esta página periódicamente. Te avisaremos de cualquier cambio publicando la nueva Política de privacidad en esta página.

### Historial de versiones

| Versión | Fecha | Qué cambió |
|---|---|---|
| 1 | 13 de enero de 2026 | Primera versión, en inglés. |
| 2 | 7 de octubre de 2026 | Ficha de salud, membresía y reservas, más detalle de la foto de perfil y del historial de entrenamiento, quién puede ver tu información, permisos de cámara y fotos, servicios de terceros y qué borra eliminar la cuenta. En inglés. |
| 3 | 3 de noviembre de 2026 | En español. Mensajes de tu centro y notificaciones push: Firebase Cloud Messaging, APNs, tokens de notificaciones, cuánto tiempo se guardan y cómo dejar de recibirlos. El permiso de notificaciones. «Cookies» ya no ofrece aceptar o rechazar cookies, un ajuste que la app no tiene. |

## Contacto

Si tienes preguntas o sugerencias sobre nuestra Política de privacidad, no dudes en escribirnos.

**Misticode**
Correo: contacto@misticode.cl
Sitio web: https://www.misticode.cl
