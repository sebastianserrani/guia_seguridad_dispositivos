# **GUÍA DE SEGURIDAD DE DISPOSITIVOS ELECTRÓNICOS**
*Esta es un guía lo más completa y digerible que pude hacer para animar a los usuarios con menos conocimientos técnicos a usar configuraciones y herramientas que los mantengan lo mejor protegidos posible. Espero les sirva.*

---

## BÁSICOS
*Configuraciones básicas para tener el dispositivo mínimamente asegurado...*

### **Registrar los datos del equipo**
> 🔥 Importante! para 📱 Celular y Tablet

En la pantalla de marcación telefónica, escribir `*#06#` para ver el **IMEI** (Identidad Internacional de Equipo Móvil); es el dato que usan las operadoras para bloquear el equipo en caso de robo o extravío.

También verificar la **marca y modelo del equipo** en *Configuración > Acerca del teléfono* (o en *Ajustes > Acerca del dispositivo*).
En *Configuración > Acerca del teléfono > Estado* se puede ver el **número de serie** del equipo.

Además, en tarjeta de plástico donde viene el chip SIM, que entrega el proveedor (Claro, Personal, etc.) cuando se compra la línea, figuran el **PIN** y el **PUK** (sirven para bloquear y desbloquear el SIM). Si no se cuenta con esa tarjeta, se pueden pedir esos datos llamando a *Atención al cliente* del proveedor.

Tomar nota de toda esta información y guardarla en algún lugar seguro!

### **Definir método de bloqueo de pantalla**
> 🔥 Importante! para 📱 Celular y Tablet

Protegé tu dispositivo estableciendo un bloqueo de pantalla con un PIN (secuencia de números), una contraseña o un patrón.

Entrá a *Configuración > Seguridad y ubicación* y definí algún método de bloqueo de pantalla: **patrón, PIN o contraseña** (no elijas ni *Deslizar* ni *Ninguno*, ya que muy inseguro!).

Para el *patrón*, usar por lo menos 4 puntos y luego desactivar la opción *Hacer visible el patrón*, para que no se dibujen en la pantalla líneas cuando se pase el dedo por los puntos. Para usar el *PIN*, ingresá, por lo menos, 4 números. Para usar una *contraseña*, ingresá, por lo menos, 8 caracteres.

Además, sería recomendable guardar por escrito el PIN, patrón o contraseña, e informar a alguna persona de confianza al respecto, por si es necesario desbloquear el equipo en alguna emergencia.

### **Encriptar los datos**
> 🔥 Importante! para 📱 Celular y Tablet

La encriptación almacena tu información de forma tal que solo se puede leer cuando tu tablet o teléfono está desbloqueado. La encriptación ofrece protección adicional en caso de que te roben el dispositivo.

La mayoría de los equipos nuevos ya vienen con la encriptación activada y no es necesario hacer nada más al respecto; pero es importante verificarlo!

Antes de poder encriptar el equipo, la batería debe estar totalmente cargada (y adicionalmente, conectado al cargador) y debe haberse definido el bloqueo de pantalla (puede ser por patrón, PIN o contraseña). La encriptación *puede* durar más de 1 hora y es probable que el dispositivo se reinicie varias veces.

Entrar a *Configuración > Seguridad y ubicación > Encriptación y credenciales* (o a *Ajustes > Bloqueo y seguridad > Otros ajustes de seguridad > Encriptar dispositivo*) y verificar que en **Encriptar teléfono** diga *Encriptado*.

Si está presente la opción de encriptar la tarjeta SD (almacenamiento externo), probablemente sea buena idea hacerlo. Tener presente que, una vez encriptada la tarjeta, los datos sólo serán visibles en el teléfono donde se encriptó; no se puede usar normalmente en otro celular o computadora (salvo que se formatee).

### **Registrar las huellas digitales**
> ✨ Recomendado para 📱 Celular y Tablet

Si el dispositivo lo soporta, sería conveniente habilitar la lectura de huellas digitales, como método adicional para desbloquear la pantalla. Entrar a *Configuración > Seguridad y ubicación > Huella digital* y agregar, por lo menos, huellas de 2 dedos distintos (por ejemplo, pulgar e índice), preferentemente de ambas manos.

Además, *evaluar* la posibilidad de guardar la huella de alguna persona de mucha confianza, por si es necesario desbloquear el equipo en alguna emergencia.

### **Habilitar la copia de seguridad**
> ✨ Recomendado para 📱 Celular y Tablet

La copia de seguridad de los datos y la configuración del teléfono se puede hacer a una cuenta de Google, si está configurada (ver en la siguiente sección). Con esto vas a poder restablecer la información en tu teléfono original o en otro teléfono Android, conservando lo siguiente: contactos, calendario, SMS, redes WiFi, configuración y datos de las apps, incluso las que no son de Google.

Entrar a *Configuración > Sistema > Copia de seguridad*, y tocar el interruptor 🔛 para activarla. Inmediatamente después, verificar más abajo, en *Detalles de la copia de seguridad*, los ítems que se van a incluir:
- Apps: ✔
- Fotos y videos: si dice *Desactivado*, tocar esa opción (se abre la configuración de Google Fotos) y tocar el interruptor 🔛 de *Crear una copia de seguridad* para activarlo[^1]
- SMS y mensajes MMS: ✔
- Historial de llamadas: ✔
- Configuración del dispositivo: ✔
- Datos de la cuenta de Google: tocar el interruptor 🔛 para servicio que se quiera respaldar

Por otro lado, si no queremos o no tenemos una cuenta de Google, se pueden hacer respaldos parciales[^2] con éstas Apps:
- [IDrive Online Backup](https://www.idrive.com/iphone-ipad-android-backup) `Google Play: 4.4⭐, 1 M+`: guarda fotos y videos, contactos, calendarios y SMS; la cuenta gratuita ofrece **10 GB** de almacenamiento.
- [Microsoft OneDrive](https://play.google.com/store/apps/details?id=com.microsoft.skydrive) `Google Play: 4.7⭐, 1000 M+`: guarda imágenes, documentos, videos y cualquier otro tipo de archivo; el plan gratuito incluye **5 GB** de almacenamiento.
- [Icedrive](https://icedrive.net/apps/mobile-tablet) [[en español 💬](https://icedrive-net.translate.goog/apps/mobile-tablet?_x_tr_sl=auto&_x_tr_tl=es&_x_tr_hl=es-419)] `Google Play: 4.3⭐, 100 k+`: copias de seguridad de fotos, documentos y videos, e instantáneas de todo el dispositivo; la cuenta gratuita ofrece **10 GB** de almacenamiento, pero sin encripción de lado cliente.
- [Box](https://www.box.com/es-419/resources/downloads) `Google Play: 4.6⭐, 10 M+`: ofrece **10 GB** de almacenamiento gratuito en la nube, controles de seguridad a nivel de archivos y acceso sin conexión.
- [MEGA](https://mega.io/es/mobile) `Google Play: 4.5⭐, 100 M+`: backup automático de fotos y vídeos (no tiene sincronización de otros archivos), acceso sin conexión, permite usar contraseña y biometría; almacenamiento gratuito de **20 GB**.
- [Dropbox](https://www.dropbox.com/mobile) `Google Play: 4.6⭐, 1000 M+`: copia de seguridad y sincronización de imágenes, videos, documentos y otros archivos; la cuenta gratuita ofrece sólo **2 GB**.

Y para los más intrépidos, también es posible **sincronizar los dispositivos directamente con una PC**, evitando servicios de terceros, con [Syncthing](https://syncthing.net) [[en español 💬](https://syncthing-net.translate.goog/?_x_tr_sl=en&_x_tr_tl=es&_x_tr_hl=es-419)] o [Resilio Sync](https://www.resilio.com/individuals/) [[en español 💬](https://www-resilio-com.translate.goog/individuals/?_x_tr_sl=en&_x_tr_tl=es&_x_tr_hl=es-419)]. Lamentablemente, las páginas web de estas herramientas están en inglés y son de lo menos amigable que hay, así que recomiendo ver alguno de estos artículos[^3][^4][^5][^6][^7] y videos[^8][^9].

[^1]: Alternativamente, abrir la App de Google Fotos, tocar en el ícono de *perfil* (`Perfil 👤`, arriba a la derecha), luego ir a *Configuración de Fotos > Copia de seguridad* y activarla.
[^2]: Algunas Apps, sólo sincronizan o respaldan fotos y videos de la cámara; otras permiten el respaldo manual de algunas carpetas y archivos.
[^3]:[Syncthing, o cómo tener tu propio servicio de sincronización de archivos tipo Dropbox](https://www.lanacion.com.ar/tecnologia/syncthing-o-como-tener-tu-propio-servicio-de-sincronizacion-de-archivos-tipo-dropbox-nid27122022/)
[^4]:[Instalar Syncthing en Android y sincronizar archivos en tu red](http://somebooks.es/instalar-syncthing-en-android-para-sincronizar-archivos-en-tu-red/)
[^5]:[Gratis y sólo con una app: así he creado una nube personal que se sincroniza de forma automática, incluso desde un móvil Android](https://www.xatakahome.com/la-red-local/gratis-solo-app-asi-he-creado-nube-personal-que-se-sincroniza-forma-automatica-incluso-movil-android)
[^6]:[Resilio Sync: Cómo transferir archivos desde Android a tu PC](https://www.neoteo.com/como-transferir-archivos-desde-android-a-tu-pc/)
[^7]:[Syncing between a desktop computer and a mobile device](https://help.resilio.com/hc/en-us/articles/205451165-Syncing-between-a-desktop-computer-and-a-mobile-device)
[^8]:[Cómo Sincronizar archivos en Android y PC. Fácil y Gratis](https://www.youtube.com/watch?v=lkj_73FYLZM)
[^9]:[RESILIO SYNC Sincronizar FOTOS MÓVIL con PC y más](https://www.youtube.com/watch?v=Mh0oI50qKeo)

### **Ocultar el contenido de las notificaciones**
> ✨ Recomendado para 📱 Celular y Tablet

Cuando la pantalla del equipo está bloqueada, pueden aparecer notificaciones con información privada. Sería recomendable configurarlas para mostrar sólo lo indispensable (por ejemplo, WhatsApp dejaría de mostrar los mensajes no leídos, y en cambio informaría que *hay X mensajes en Y conversaciones, no leídos*).

Esto se activa entrando a *Configuración > Apps y notificaciones > Notificaciones > En la pantalla bloqueada* y seleccionando **Ocultar contenido confidencial de notificaciones**.

La contra de ésta configuración es que, posiblemente, nos fuerce a desbloquear el dispositivo más seguido.

### **Bloqueo de la tarjeta SIM**
> 👍 Opcional para 📱 Celular

El bloqueo de la tarjeta SIM es una opción de seguridad adicional, que sirve para inhabilitar los servicios (llamadas y datos) del proveedor de telefonía. Antes de activarlo, considerar que puede ser contraproducente, ya que en caso de robo o extravío, sería útil tener los servicios de datos activos, para poder rastrear el equipo y, además, llamar al operador para denunciar la pérdida y bloqueo de los servicios es un proceso rápido y simple!

Activar esto va a hacer que el teléfono solicite el PIN cada vez que se encienda o reinicie. No lo pide para desbloquear la pantalla!

Entrar a *Configuración > Seguridad y ubicación > Bloqueo de la tarjeta SIM* (o a *Ajustes > Bloqueo y seguridad > Otros ajustes de seguridad > Definir bloqueo de la tarjeta SIM*) y activarlo. Va a solicitar el **PIN actual** que, si no se modificó, debiera figurar en la tarjeta de plástico donde venía el chip SIM.

Si se ingresa un PIN incorrecto 3 veces, la SIM puede bloquearse y será necesario tener el código **PUK** para desbloquearla; este código también viene impreso en la misma tarjeta del chip SIM.

### **Denuncia por robo o extravío**
> ⚠️ Información para 📱 Celular

Además de llamar a la compañía telefónica que corresponda, también se puede llamar al `*910`, una línea de ENACOM para [denunciar](https://www.enacom.gob.ar/denuncia-al-910_p4034) el robo, dar de baja la línea y bloquear el celular. El servicio es para todo el país y abarca a todas las compañías en cualquiera de sus planes.

Si se recupera el equipo, luego de haberlo bloqueado, es posible que la compañía telefónica solicite un **comprobante de denuncia policial**, por lo tanto es recomendable hacerla inmediatamente después del hecho.

Para más info, entrá a [ENACOM](https://www.enacom.gob.ar/), en el menú *Atención a usuarios > Telefonía móvil* y a la izquierda, elegí *Denunciá al \*910*.

También está activo el `*234#` para que los usuarios de *abonos prepagos* puedan [registrar su línea](https://www.enacom.gob.ar/tu-linea-es-tuya_p3874) y validar su identidad como titulares. Este paso es vital para posteriormente solicitar el desbloqueo de línea o equipo, si fuese recuperado.

Para denunciar:
- **Claro**: llamar al `*611`.
- **Movistar**: llamar al `*611`.
- **Personal**: llamar al `*111`.

### **Registrarse en el Registro Nacional No Llame**
> ⚠️ Información para 📱 Celular

El *Registro Nacional No Llame* reúne los números telefónicos de las personas que no quieren recibir llamadas publicitarias. Una vez que inscribís tu número en el Registro, quienes publiciten, oferten o vendan bienes o servicios tienen hasta 30 días para dejar de llamarte.

Registrá tus números en [https://nollame.aaip.gob.ar](https://nollame.aaip.gob.ar/).

---

## **CUENTA DE GOOGLE**
*Si en el celular hay configurada alguna cuenta de email de Gmail, incluso si no se usa, se pueden usar las siguientes características para asegurar el equipo...*

### **Verificar la cuenta configurada**
> 🔥 Importante! para 📱 Celular y Tablet

Antes que nada, entrar a *Configuración > Cuentas* y verificar si hay alguna cuenta de Google o Gmail configurada. Es bastante probable que se haya configurado una, apenas se adquirió el equipo.

Verificar que se dispone de los datos de acceso (usuario y contraseña) para la cuenta y luego probar si es posible ingresar a cualquier servicio de Google con esos datos, por ejemplo a [Gmail](https://mail.google.com/mail/).

### **Activar Encontrar mi dispositivo**
> 🔥 Importante! para 📱 Celular y Tablet

Para buscar, bloquear o borrar un teléfono perdido o robado, el método más fácil es tener activada la función de encontrar el dispositivo que ofrece Google.

Entrar a *Configuración > Google > Encontrar mi dispositivo* y en esa pantalla:
- **Activar** el servicio.
- Si aparece la opción de «Almacenar ubicación reciente», activarla también.
- Tocar el enlace *App de Encontrar mi dispositivo* para abrir la App, si no está instalada se abre la Play Store para instalarla.

Luego, hay que comprobar que *Encontrar mi dispositivo* tenga los permisos necesarios para cumplir su función: entrar a *Configuración* y buscar `administración` o `administrador` (depende del fabricante del celular).
Seleccionar la opción que diga *Aplic. administración dispositivo* o *Administradores de dispositivos* (o similar) y si no estaba ya, habilitar a *Encontrar mi dispositivo*.

Para que esta característica funcione, además, hay que verificar lo siguiente:
- La **Ubicación** este activada (*Configuración > Ubicación* y Activar)
- Que el celular figure en los [Dispositivos](https://play.google.com/library/devices) de Google Play y tenga marcada la opción «Mostrar en menús».

Luego, entrar a [https://www.google.com/android/find](https://www.google.com/android/find) usando tu cuenta de Gmail, para comprobar que el celular aparece conectado y la ubicación sea la tuya. También es posible rastrear el equipo desde otro dispositivo con Android, instalando la app **Encontrar mi dispositivo** y accediendo como invitado.

### **Activar Google Play Protect**
> ✨ Recomendado para 📱 Celular y Tablet

Google Play Protect verifica la seguridad de las apps de Google Play Store antes de descargarlas y analiza la actividad del dispositivo para detectar apps potencialmente dañinas.

Para activarlo, abrir la Play Store, presioná el *menú* (`≡`, arriba a la izquierda) y luego, pulsar sobre *Play Protect*. Si no esta activo, te va a mostrar un botón para activarlo.

### **Activar el historial de ubicaciones de Google Maps**
> 👍 Opcional para 📱 Celular y Tablet

Activar el historial de ubicaciones de Google Maps permite que se puedan ver las últimas ubicaciones del celular si fue robado o extraviado (y está apagado o sin servicio) o si no se puede usar la función de *Encontrar mi dispositivo*, por cualquier razón.

Entrar a *Configuración > Seguridad y ubicación > Ubicación > Historial de ubicaciones* (o a *Ajustes > Privacidad > Ubicación > Historial de ubicaciones*) y activarlo. Luego, ir a [https://www.google.com/maps/timeline](https://www.google.com/maps/timeline) para comprobar si hay datos. Puede demorar hasta 20 minutos en aparecer información nueva.

Esta no es, ni por asomo, la mejor forma de *tratar* de ubicar un equipo desaparecido, y probablemente no arroje los resultados que uno desearía. En lo posible, **no activarlo**.

### **Evitar usar la liberación de espacio**
> 👍 Opcional para 📱 Celular y Tablet

*Google Fotos* tiene una función de [liberar espacio](https://support.google.com/photos/answer/6128843?hl=es-419): cuando se haya hecho, por lo menos, un respaldo de las fotos y videos a la cuenta de Google, es posible habilitar esta función que **borra fotos del dispositivo**; esta no es una función automática, debe hacerse manualmente.
Esto puede ser útil en equipos (viejos o) con muy poco espacio de almacenamiento, pero luego las fotos sólo son accesibles mientras haya conexión, este instalada la App de Google Fotos e iniciada la sesión en Google; creo que es preferible descargarlas a una PC.

Además, en algunos equipos con Android (dependiendo del fabricante), está disponible el *Administrador de almacenamiento* (en *Configuración > Almacenamiento*) que, una vez activado, permite **quitar fotos y videos** que tengan una copia de seguridad en Google Fotos, automáticamente.
De nuevo, creo que es preferible descargarlas a una PC.

---

## **SEGURIDAD**
*Medidas adicionales para manejar información con mayor seguridad...*

### **Usar contraseñas seguras**
> 🔥 Importante! para 📱 Celular, 📱 Tablet, 💻 Notebook y 🖥 PC

A la hora de crear una contraseña (pass*word*), para el propósito que sea, es recomendable que:
- Tenga 16 caracteres como mínimo
- Incluya números
- Incluya símbolos (tipo: `! # $ % & ( ) = ? [ ] { } , ; . : - _ ~ * | + < > @`)
- Incluya letras en minúsculas y mayúsculas (sin acentos ni diéresis)

Ejemplos de contraseñas seguras:
- Aleatoria (usando un Generador): `?~fxNZ|Xk&~k9*xFRZP2` (muy segura, 20 caracteres)
- Inventada: `Metalico~1492,Pinguino` (muy segura, 20 caracteres)

Alternativamente se puede inventar una **frase de contraseña** (pass*phrase*) que no es más que una cadena de palabras; más larga y más fácil de recordar que una contraseña complicada, y no por eso menos segura, se recomienda que:
- Tenga un mínimo de 5 palabras
- Use un separador de palabras que no sea el espacio

Ejemplos de frase de contraseñas seguras:
- Aleatoria (usando un Generador): `ambito.alegria.produjo.aparentemente.gregorio` (segura, 5 palabras, punto como separador)
- Inventada: `guitarra-perro-lluvioso-varitono-mameluco-tehuelche-2023` (muy segura, 6 palabras y números, guión como separador)
- En inglés: `skipper-grinch-mule-numerator-silencer` (segura, 5 palabras)

Pero, **es recomendable usar un generador** como éstos:
- Contraseñas:
  - [NordPass](https://nordpass.com/es/password-generator/)
  - [LastPass](https://www.lastpass.com/es/features/password-generator#generatorTool)
  - [Dashlane](https://www.dashlane.com/es/features/password-generator)
  - [Bitwarden](https://bitwarden.com/password-generator) (en inglés) (también genera frases)
- Frases:
  - [contraseñasegura.com](https://contraseñasegura.com)
  - [Generador de frases fuertes legibles](https://mirrodriguezlombardo.com/passphrase) (usar la plantilla *Normal*)
  - [Random Spanish Password Generator](https://passwordcreator.org/es.html#great) (listadas en la columna *Common Words*)
  - [Worksighted](https://www.worksighted.com/random-passphrase-generator/#passphrase-generator) (en inglés)

Además, se puede comprobar la fortaleza de una contraseña desde cualquiera de éstas páginas:
- [(Kaspersky) Comprueba tu contraseña](https://password.kaspersky.com/es)
- [(Bitwarden) Password Strength Testing Tool](https://bitwarden.com/password-strength) (en inglés)
- [PasswordMonster](https://www.passwordmonster.com) (en inglés)

### **Usar verificación de dos pasos**
> 🔥 Importante! para 📱 Celular, 📱 Tablet, 💻 Notebook y 🖥 PC

La verificación de dos pasos o **2FA** («Two Factor Authentication»), es un sistema para verificar tu identidad al iniciar sesión en una web o App, agregando una capa de seguridad adicional a tu cuenta, ya que además del usuario y contraseña, deberás ingresar un **código de verificación** (o *token*).

Esto sirve para evitar que alguien más pueda acceder a tu cuenta, incluso en el caso de que *averigue* tu contraseña.

La verificación se hace con un código descartable que se genera para cada inicio de sesión. A este código lo podemos obtener a través de una App específica para gestionar 2FA (lo recomendado, ver abajo), una llave de seguridad USB (como las Yubikey), la cuenta de email asociada al servicio, biometría o mensajes SMS (no recomendable!).

Este sistema se debe activar en cada servicio (web o App) que queramos asegurar con 2FA. En líneas generales, debemos ingresar a la configuración de *Seguridad*, buscar la opción de *Verificación en dos pasos* y seguir las instrucciones.

Sobre las Apps para gestionar 2FA, esta es mi recomendación:
- [Microsoft Authenticator](https://www.microsoft.com/es-ar/security/mobile-authenticator-app)
- [Authy](https://authy.com) [[en español 💬](https://authy-com.translate.goog/?_x_tr_sl=en&_x_tr_tl=es&_x_tr_hl=es-419)]
- [Google Authenticator](https://support.google.com/accounts/answer/1066447?hl=es-419)
- [Aegis](https://getaegis.app/) [[en español 💬](https://getaegis-app.translate.goog/?_x_tr_sl=en&_x_tr_tl=es&_x_tr_hl=es-419)] (esta es mi preferida)
- [Bitwarden Authenticator](https://bitwarden-com.translate.goog/help/authenticator-keys/?_x_tr_sl=en&_x_tr_tl=es&_x_tr_hl=es-419) (si se usa también como administrador de contraseñas)

Algunas guías específicas sobre este tema:
- WhatsApp: [Información acerca de la verificación en dos pasos](https://faq.whatsapp.com/1278661612895630)
- Google: [Activar la verificación en dos pasos](https://support.google.com/accounts/answer/185839?hl=es)
- Microsoft: [Cómo utilizar la verificación en dos pasos con su cuenta de Microsoft](https://support.microsoft.com/es-es/account-billing/c%C3%B3mo-utilizar-la-verificaci%C3%B3n-en-dos-pasos-con-su-cuenta-de-microsoft-c7910146-672f-01e9-50a0-93b4585e7eb4)
- Samsung: [¿Qué es la verificación en dos pasos?](https://www.samsung.com/ar/support/apps-services/what-is-two-step-verification/)
- Facebook: [Cómo funciona la autenticación en dos pasos en Facebook](https://es-la.facebook.com/help/148233965247823)
- Instagram: [Proteger tu cuenta de Instagram con la autenticación en dos pasos](https://es-es.facebook.com/help/instagram/566810106808145)
- Mercado Libre: [¿Cómo fortalecer la seguridad de mi cuenta?](https://www.mercadolibre.com.ar/ayuda/281)

Es recomendable, activarlo en todos los servicio financieros que lo soporten (apps de bancos, de tarjetas virtuales, cryptos, etc.), en WhatsApp, en los mails, etc.

### **Usar un administrador de contraseñas**
> 🔥 Importante! para 📱 Celular, 📱 Tablet, 💻 Notebook y 🖥 PC

Un administrador de contraseñas te ayuda a gestionar todas tus contraseñas (o cualquier información confidencial) de forma segura, guardándolas en una bóveda, que se bloquea con una llave maestra. Así que, sólo hay que recordar una única **contraseña maestra** para acceder a todos los datos resguardados.

Estas son las características más importantes de los administradores:
- Principalmente, *rellenan automáticamente formularios de inicio de sesión* y de registro.
- Funcionan en cualquier página web, programa de computadora o App del celular.
- Sincroniza las contraseñas entre PCs, notebooks y celulares.
- No necesitan conexión a Internet continua para funcionar (pueden trabajar offline).
- En el celular se puede usar, además, la biometría (huellas o cara) para acceder a la bóveda.
- Pueden generar automáticamente una contraseña segura cuando se registra algún servicio nuevo.
- Además, permiten guardar *tarjetas* de débito o crédito o *identidades* (DNI, pasaporte, etc).
- Permite enviar a terceros, textos confidenciales o archivos de forma segura (con opción de fecha de expiración, número máximo de descargas o contraseña).
- Permite compartir contraseñas con miembros de la familia, sin revelarlas.
- Permite importar o exportar las contraseñas, para archivado o impresión.
- Puede generar informes de: contraseñas comprometidas, reutilizadas, débiles o filtradas al público.
- Permite configurar un doble factor de autenticación (2FA) para las páginas que lo soportan.

Hay dos tipo de gestores: como *servicio*, en los cuales, a nuestros datos los guarda el proveedor de forma segura y me parecen los más amigables; o como *producto*: es sólo un programa que genera una base de datos en nuestro equipo y es nuestra responsabilidad mantenerlo a salvo (de borrado por error, virus, etc.).

La forma más sencilla de iniciarse con este tema, sería usar **[Bitwarden](https://bitwarden.com)** [[en español 💬](https://bitwarden-com.translate.goog/?_x_tr_sl=auto&_x_tr_tl=es&_x_tr_hl=es-419)] que tiene apps para el navegador, celular y computadora; alternativamente [Proton Pass](https://proton.me/es/pass), [LastPass](https://www.lastpass.com/es) o [1Password](https://1password.com/es). Entrar a la página de cualquiera de estos servicios, crear una cuenta gratuita y seguir las instrucciones.

La otra opción sería usar la app [KeePass DX](https://www.keepassdx.com/) en Android y [KeePassXC](https://keepassxc.org/) en la computadora, si queremos evitar que a nuestros datos los almacene un tercero. El archivo-bóveda que generan estos programas, se puede guardar en una carpeta sincronizada a la nube (DropBox, OneDrive, Nextcloud, etc.), para accederlo desde otros dispositivos.

Cualquiera sea la elección, hay que mantener a salvaguarda la *contraseña maestra* elegida. Escribirla en un papel o una libreta y archivarla en un lugar seguro!

Llegados a este punto, se pueden empezar a cargar las contraseñas.
Tener en cuenta que se pueden guardar muchas cosas en el administrador:
- Usuarios y contraseñas de:
  - Sitios web
  - Emails
  - Computadoras
  - Celulares
- Información personal:
  - DNI
  - pasaporte
- Información financiera:
  - Cuentas de bancos
  - Tarjetas de crédito
- Configuraciones:
  - Router
  - WiFi
- Etc.

Para todos los ítems, también se pueden agregar *notas*, para identificar el origen, uso u otros datos de relevancia.

Finalmente, es importante deshabilitar el *guardado de contraseñas* y el *auto-completado* que ofrecen los navegadores, así evitamos tener múltiples copias de contraseñas (puede volverse problemático si se cambian y quedan registradas nuevas en un lado y antiguas en otro...).
- En [Chrome](https://support.google.com/chrome/answer/95606?hl=es-419) y derivados (Edge, Opera, Brave):
  - Hacer clic en `Perfil 👤` y luego `Contraseñas 🗝` (esquina superior derecha)
  - En el *Administrador de contraseñas* ir a `⚙ Configuración` (a la izquierda)
  - Desactivar *Sugerir que se guarden las contraseñas* y *Acceder automáticamente*
- En [Firefox](https://support.mozilla.org/es/kb/autocompletar-los-inicios-de-sesion-en-firefox) y [Firefox para Android](https://support.mozilla.org/en-US/kb/logins-sync-autofill-saving-firefox-preview) [[en español 💬](https://support-mozilla-org.translate.goog/en-US/kb/logins-sync-autofill-saving-firefox-preview?_x_tr_sl=auto&_x_tr_tl=es&_x_tr_hl=es-419)]:
  - Ir al menú (`≡`, arriba a la derecha) y elegir *Preferencias > Privacidad y seguridad*
  - Ir a la sección de *Inicios de sesión y contraseñas*
  - Desactivar todas las opciones activas
- En Edge:
  - Ir al menú (`≡`, arriba a la derecha) y elegir `⚙ Configuración`
  - En la sección *Perfiles*, elegir la opción `🗝 Contraseñas`
  - Desactivar *Ofrecer la posibilidad de guardar las contraseñas* y *Autorrellenar contraseñas*

### **Usar un servicio de seguimiento o anti-robo**
> 👍 Opcional para 📱 Celular, 📱 Tablet, 💻 Notebook y 🖥 PC

Se puede crear una cuenta gratuita en **[Prey](https://preyproject.com)** y descargar la aplicación. La cuenta gratis permite rastrear hasta 3 dispositivos y recolectar evidencia, pero *no permite el borrado remoto, ni el bloqueo del equipo*.

En equipos marca Samsung, que tengan una *[Samsung Account](https://account.samsung.com)* configurada, se pueden usa [SmartThings Find](https://smartthingsfind.samsung.com) para localizarlos.

Si no se quiere depender de ningún servicio de terceros, se puede usar **[FindMyDevice](https://gitlab.com/Nulide/findmydevice)**, disponible sólo desde [F-Droid](https://f-droid.org/packages/de.nulide.findmydevice/) (está en Beta todavía).

### **Usar un navegador más seguro**
> ✨ Recomendado para 📱 Celular, 📱 Tablet, 💻 Notebook y 🖥 PC

Recomiendo instalar y usar el navegador **[Firefox](https://www.mozilla.org/es-AR/firefox/new/)**; como alternativas, [DuckDuckGo Privacy Browser](https://duckduckgo.com/app), [Vivaldi](https://vivaldi.com/es/) o [Brave](https://brave.com/).

Si vas a usar Firefox en Android, ir al menú (`≡`, arriba a la derecha) y elegir *Complementos*. En la pantalla de complementos, elegir *Descubre las extensiones*… y buscar **uBlock Origin** de *Raymond Hill*, seleccionar e instalarlo.

Con uBlock, Firefox puede bloquear casi toda la publicidad y rastreo de las páginas web, además de hacer la navegación más rápida.

También desde el menú se puede acceder a la configuración, donde es posible crear una cuenta de Firefox, para que (opcionalmente) los favoritos, contraseñas e historial se sincronicen con una PC u otro celular.

Si vas a usar a DuckDuckGo, ya tenés integrado un bloqueado de rastreo y el buscador seguro de DuckDuckGo.

### **Instalar un antivirus**
> 👍 Opcional para 📱 Celular y Tablet

Si bien el consenso general es que en Android NO se necesitan antivirus, si en el dispositivo que fuera, se viven instalando todo tipo de aplicaciones (para niños, por ejemplo), tal vez no sea mala idea instalar un antivirus y escanear el aparato esporádicamente (y, opcionalmente, desinstalarlo inmediatamente después de usarlo).

Como dato interesante, varios de los antivirus más conocidos traen incluidas características adicionales que podrían ser útiles, como bloqueo de apps, seguimiento anti-robo, VPN, escaneo de la red, filtro web, etc.

Yo recomendaría probar alguna de las siguientes apps:
- Android:
  - [Kaspersky Security Cloud](https://play.google.com/store/apps/details?id=com.kaspersky.security.cloud) de *Kaspersky Lab*
  - [AVG Antivirus Gratis – Limpiador de virus Android](https://play.google.com/store/apps/details?id=com.antivirus) de *AVG Mobile*
  - [Sophos Intercept X for Mobile](https://play.google.com/store/apps/details?id=com.sophos.smsec) de *Sophos Limited*

---

## **CONTROLES PARENTALES**
*A continuación, configuraciones y aplicaciones para controlar el uso de dispositivos por parte de menores...*

### **Crear usuarios adicionales**
> 👍 Opcional para 📱 Celular y Tablet

En los dispositivos Android es posible crear un usuario distinto para cada persona que los vaya a usar. También es posible crear una cuenta de Invitado. Cada usuario tienen su propio espacio con pantalla principal, cuenta, apps y opciones de configuración personalizadas.

Esta no es la mejor forma de limitar la funcionalidad de un celular; seguí leyendo...

Tener en cuenta que, aunque se trate de usuarios distintos, hay algunas cosas que se comparten (o sea, afectan al dispositivo) como la instalación y actualización de apps y algunas opciones de configuración, como la conexión Wi-Fi y Bluetooth.

No todos lo fabricantes incluyen esta opción en sus celulares, sobre todo si son de gama media o baja.

Para crear un nuevo usuario, entrar en *Configuración > Usuarios y cuentas > Usuarios*. Presioná **Agregar usuario** y seguí las instrucciones en pantalla.

Si el equipo es una tablet, se pueden crear **perfiles restringidos**, sobre los cuáles se puede ejercer un mayor control. Buscá las instrucciones en Google escribiendo “Cómo usar perfiles restringidos en tablets”.

### **Activar control parental en Google Play Store**
> ✨ Recomendado para 📱 Celular y Tablet

Esto permite controlar qué tipo de apps se pueden instalar en el equipo. Es necesario crear un PIN (y recordarlo) para activar esta función. Una vez activada, vamos a poder establecer restricciones de contenido en: *Apps y juegos*, *Películas* y *Música*.

Tener en cuenta que las restricciones son efectivas para las apps instaladas luego de la implementación del control parental; o sea, esto no afecta a las apps que ya están están instaladas. En caso de querer controlar una app existente, hay que desinstalarla y volver a instalar.

Para activarlo, abrir la Play Store, presioná el *menú* (`≡`, arriba a la izquierda) y luego ir a *Configuración > Controles parentales*. Activalo y abajo configurás la restricción adecuada (acá es cuando solicita inventar un PIN nuevo).

Si se pierde el PIN, no importa; no es complejo reemplazarlo, pero hay que resetear la configuración de la Play Store.

### **Bloquear las compras**
> ✨ Recomendado para 📱 Celular y Tablet

Desde la Play Store y desde dentro de algunas aplicaciones y juegos es posible hacer compras; es conveniente tener esto bajo control.

Para activarlo, abrir la Play Store, presioná el *menú* (`≡`, arriba a la izquierda) y luego ir a *Configuración > Pedir autenticación para realizar compras*. Elegir la primer opción, *Para todas las compras…* y listo.

### **Instalar una app específica de control parental**
> ✨ Recomendado para 📱 Celular y Tablet

Hay muchas aplicaciones de esta clase, yo recomendaría usar cualquiera de estas:

- Android:
  - [Kids Place - Control Parental y Modo niños]((https://kiddoware.com/)) de *kiddoware*
  - [Localizador Familiar GPS y control parental]((https://locategy.com/)) de *Locategy SL*
  - [SecureKids Control Parental]((https://securekids.es/)) de *Grupo Deidev*
  - [Kaspersky SafeKids: Control parental para Android](https://www.kaspersky.es/safe-kids) de *Kaspersky Lab*
  - [Qustodio Control Parental](https://www.qustodio.com/es) de *Qustodio LLC* 

Estas se pueden usar gratis (aunque disponen de planes pagos).

Otra opción es usar [Google Family Link](https://families.google.com/intl/es/familylink), pero me parece más compleja de poner en marcha (entendiendo que cada dispositivo/niño debe tener su propia cuenta de Google, etc.), pero, igualmente, vale la pena ver.

### **Instalar una app de bloqueo de apps**
> 👍 Opcional para 📱 Celular y Tablet

Se puede instalar alguna aplicación como [Cerradura (AppLock)](https://www.domobile.com/best/applock.html) de *DoMobile Lab*, que permiten bloquear apps individuales y configuraciones del equipo (conexión Wi-Fi y Bluetooth, llamadas, Play Store, etc.) con un PIN o patrón.

---

## **AVANZADAS**
*Las siguientes son medidas opcionales que pueden requerir algo de lectura extra, paciencia, instructivos en video o más conocimientos técnicos, pero igualmente recomiendo considerar...*

### **Usar una conexión VPN**
> ✨ Recomendado para 📱 Celular, 📱 Tablet, 💻 Notebook y 🖥 PC

Resumiendo groseramente, una VPN se puede usar en internet para:

- Esconder los datos de navegación: todos los datos que circulan a través de una conexión VPN están cifrados, por lo que, por ejemplo, en caso de estar conectados a una WiFi pública, será difícil que alguien pueda rastrear nuestra actividad, robarnos datos, etc.
- Entrar en sitios con bloqueo geográfico: es posible que una aplicación (como Netflix) o página web sólo nos deje acceder si estamos navegando desde un país en concreto, por lo que si ese país no es el nuestro, difícilmente podremos acceder a ella. Con una VPN podemos conectarnos a casi cualquier país y parecerá que estamos accediendo desde dicho país.
- Evitar la censura en Internet: si estamos en un país que decide censurar ciertas páginas o aplicaciones, bastaría con conectarnos a una VPN para poder saltarnos esa censura.

Generalmente, no es un servicio gratuito, pero hay algunos que ofrecen planes personales sin costo (pero limitados en la cantidad de datos que pueden transferirse por mes). Para mí, los mejores gratuitos son **[Windscribe](https://windscribe.com/)**, [ProtonVPN](https://protonvpn.com/), [TunnelBear](https://www.tunnelbear.com/) o [hide.me](https://hide.me/).

Hay que instalar la app que corresponda al servicio (siguiendo las instrucciones en el sitio web correspondiente) y, en lo posible, mantener la conexión VPN activa siempre y con el *kill-switch* o *firewall* (opción que bloquea internet si los datos no pasan por la VPN, evitando fuga de datos) también activo.

### **Encriptar el almacenamiento en la nube**
> ✨ Recomendado para 📱 Celular, 📱 Tablet, 💻 Notebook y 🖥 PC

Si usas algún servicio de almacenamiento en la nube como Dropbox, Nextcloud, Google Drive, Microsoft OneDrive, etc., podes usar [Cryptomator](https://cryptomator.org/) para crear una *bóveda* en que se guardan todos los archivos encriptados. El sitio de esta herramienta está en inglés, pero es fácil de seguir.

En Android, casi seguro ya tenés instalado Drive y disponibles hasta 15GB de espacio de almacenamiento en la nube, que proporciona Google a cada cuenta (que también seguramente ya tengas configurada en el celular).

---

## **PRIVACIDAD**
*Este es un tema aparte, que nadie va a leer…*

La privacidad es un concepto muy sencillo e importante, pero increíblemente difícil de vender a la gente: **privacidad es el derecho a la intimidad y vida privada**.

En el contexto de la tecnología, usualmente se refiere a la **potestad de controlar la información propia** (nombre, mails, ubicación, búsquedas, etc.) frente al acopio y procesamiento masivo e indiscriminado por parte de gobiernos y, especialmente, empresas privadas.

Sólo por si hace falta, voy a aclararlo: Google es una de las multinacionales con más poder para acumular y comercializar (o, mejor dicho, monetizar) la información de los usuarios de sus servicios. Y Android es de Google. Unir puntos.

Y si, me doy cuenta que la mitad de los consejos que puse en las secciones anteriores se basan en los servicios de Google, pero también es la forma más fácil (si no la única) de animar a los usuarios menos técnicos a que adopten mínimas medidas de seguridad (aunque sea a perjuicio de su privacidad).

Dicho esto, manos a la obra…

### **Verificar los permisos de las apps**
> ✨ Recomendado para 📱 Celular y Tablet

Primero lo primero: hay que revisar qué permisos tienen las apps instaladas en el dispositivo. Para esto hay que entrar en *Configuración > Apps y notificaciones > Permisos de aplicaciones* (o a *Configuración > Aplicaciones >* `⚙` *> Permisos de aplicaciones*) y explorar cada permiso para ver a qué app se le han otorgado; en especial, los permisos de *Cámara*, *Micrófono*, *SMS*, *Teléfono* y *Ubicación*.

Acá entra en juego el sentido común: por ejemplo, la app del *Traductor* no tiene porqué acceder a los contactos; y el acceso a la ubicación, sólo debieran tenerlo apps de mapas o similares.

Y si resulta que le quitamos demasiados permisos a alguna app, que realmente los requiera, la propia app los va a volver a solicitar cuando la vayamos a usar.

### **Deshabilitar el identificador único del móvil**
> ✨ Recomendado para 📱 Celular y Tablet

Todos los equipos generan un identificador único o *ID*, que comunican a las apps y a los anunciantes. Es muy recomendable deshabilitarlo: hay que entrar en *Configuración > Google > Anuncios* y activar la opción **Cancelar personalización de anuncios**. Opcionalmente, también hacer clic sobre *Restablecer ID de publicidad* y aceptar: esto genera un nuevo identificador aleatorio.

### **Salir de la burbuja**
> ✨ Recomendado para 📱 Celular, 📱 Tablet, 💻 Notebook y 🖥 PC

Un [filtro burbuja](https://es.wikipedia.org/wiki/Filtro_burbuja) es el filtrado de los resultados que hacen algunos buscadores (Google, Facebook, Twitter, etc.), *prediciendo* la información que al usuario le gustaría ver, basándose en información sobre él mismo. Como consecuencia, los usuarios son menos expuestos a puntos de vista diversos y son aislados intelectualmente en su propio sesgo informativo, en burbujas ideológicas y culturales.

Esto se puede contrarrestar usando bloqueadores de publicidad y rastreo, usando el modo incógnito de los navegadores y, principalmente, usando un buscador que no filtre resultados, como [DuckDuckGo](https://duckduckgo.com/) o [Startpage](https://www.startpage.com/).

### **Independizarse**
> ✨ Recomendado para 📱 Celular, 📱 Tablet, 💻 Notebook y 🖥 PC

Si te animás y querés renegar un poquito, es posible encontrar alternativas a la mayoría de los productos y servicios de Google; esto es lo que recomiendo yo:

- **Búsqueda**
  - [DuckDuckGo](https://duckduckgo.com)
  - [Startpage](https://www.startpage.com)
- **Chrome**
  - [Firefox](https://www.mozilla.org/es-AR/firefox/new)
  - [Vivaldi](<https://vivaldi.com/es)
  - [Brave](https://brave.com)
- **Gmail**
  - [ProtonMail](https://protonmail.com/es)
  - [Tutanota](https://tutanota.com/es)
- **GDrive**
  - [MEGA](https://mega.nz/start)
  - [Sync](https://www.sync.com)
  - [pCloud](https://www.pcloud.com/es)
  - [Box](https://www.box.com/es-419)
- **Play Store** (para instalar estas tiendas se deben habilitar los *Orígenes desconocidos*)
  - [F-Droid](https://f-droid.org/es) (sólo apps open source)
  - [Aurora Store](https://auroraoss.com) (instalable a través de F-Droid; permite descargar apps de la Play Store sin una cuenta de Google)
  - [Aptoide](https://es.aptoide.com)
- **Maps**
  - Maps (instalable a través de F-Droid)
  - [Maps.me](https://mapsme.es)
  - [OsmAnd](https://osmand.net)
  - [Waze](https://www.waze.com/es)
- **Hangouts**
  - [Jitsi Meet](https://meet.jit.si)
  - [Signal](https://signal.org/es)
  - [Telegram](https://telegram.org)
- **YouTube**
  - [NewPipe](https://newpipe.schabi.org) (permite ver videos de YouTube sin publicidad ni rastreo)
  - [Vimeo](https://vimeo.com/es)
- **Play Música** (servicio de música)
  - [Deezer](https://www.deezer.com/es)
  - [Spotify](https://www.spotify.com/ar)
  - [Jamendo Music](https://www.jamendo.com/start)
- **Keep**
  - [Joplin](https://joplinapp.org)
  - [Simplenote](https://simplenote.com)
  - [Omni-Notes](https://play.google.com/store/apps/details?id=it.feio.android.omninotes) (e instalable a través de F-Droid)
  - [Simple Notes Pro](https://www.simplemobiletools.com)
  - [Standard Notes](https://standardnotes.org)
- **Traductor**
  - [DeepL](https://www.deepl.com/translator)
  - [Linguee](https://www.linguee.com)

También hay alternativas para apps básicas de Android (también de Google):

- **Mensajes** (SMS / MMS)
  - [QKSMS](https://qklabs.com)
  - [Signal](https://signal.org/es)
  - [Disa](https://disa.im)
- **Calendario**
  - [Etar Calendar](https://play.google.com/store/apps/details?id=ws.xsoh.etar) (e instalable a través de F-Droid)
  - [Simple Calendar](https://www.simplemobiletools.com))
  - Offline Calendar (instalable a través de F-Droid; habilita un calendario sin sincronización)
  - [Fruux](https://fruux.com/)
- **Gboard** (teclado)
  - [AnySoftKeyboard](https://anysoftkeyboard.github.io)
  - [Fleksy](https://www.fleksy.com)
  - [SwiftKey](https://www.microsoft.com/es-es/swiftkey)
- **Fotos**
  - [Simple Gallery](https://www.simplemobiletools.com)
  - [Camera Roll](https://play.google.com/store/apps/details?id=us.koller.cameraroll) (e instalable a través de F-Droid)
- **Google Play Música** (reproductor)
  - Music (instalable a través de F-Droid)
  - [Simple Music Player](https://www.simplemobiletools.com)
  - [Music Player GO](https://play.google.com/store/apps/details?id=com.iven.musicplayergo) (e instalable a través de F-Droid)
  - Timber (instalable a través de F-Droid)
  - [Phonograph](https://play.google.com/store/apps/details?id=com.kabouzeid.gramophone) (e instalable a través de F-Droid)

---

## **MÁS**
*Y por si a alguien llegó hasta acá, un listado de recursos útiles e información...*

- [Página de Controles de privacidad de Google](https://safety.google/privacy/privacy-controls): muy recomendable leerla y seguir las instrucciones para examinar cómo se usan tus datos.
- [Página de Cuenta de Google](https://myaccount.google.com/): acá se pueden ver y cambiar todas las configuraciones de tu cuenta de Google. Dentro del apartado Información personal y privacidad, la opción Revisión de privacidad nos permite ver qué compartimos.
- Controlar la [sincronización de Chrome](https://support.google.com/chrome/answer/185277?hl=es&co=GENIE.Platform%3DAndroid&oco=1): si está activa, se guardan en tu cuenta de Google los marcadores, el historial, las contraseñas y otras opciones de configuración, e inicia sesión automáticamente en Gmail, YouTube, la búsqueda y otros servicios.
- [¿Qué datos personales guarda Google?](https://ayudaleyprotecciondatos.es/2018/11/13/privacidad-google/)
- [Vivir sin Google o cómo proteger tu privacidad en Internet](https://www.muycomputer.com/2019/07/03/servicios-de-google/)
- [Protección de la Privacidad](https://www.proteccionprivacidad.com/)
- [Pilar y su Celular](http://www.pilarysucelular.com)
- [Informes de convivencia digital de UNICEF](https://www.unicef.org/argentina/informes/convivencia-digital)
- [Recursos sobre el ciberbullying](https://www.ciberbullying.com/cyberbullying)
- [Recursos sobre privacidad y seguridad de Mozilla](https://www.mozilla.org/es-MX/internet-health/privacy-security/)
- Recursos para niños y adolescentes de [Chicos.net](https://www.chicos.net)
- [Los problemas de privacidad que harán que te pienses si merece la pena seguir utilizando Google Chrome](https://www.businessinsider.es/google-chrome-privacidad-merece-pena-seguir-usandolo-456645)
- [Este buscador ofrece privacidad, ¿será suficiente para dejar Google?](https://www.nytimes.com/es/2019/07/22/privacidad-google-duckduckgo/)
- [Evita que Google comparta tus datos privados con los anunciantes](https://www.lavanguardia.com/tecnologia/20161024/411265785773/google-gmail-google-maps-youtube-privacidad.html)
- [On the Feeding and Care of Password Managers](https://www.reddit.com/r/Passwords/comments/qu68zj/on_the_feeding_and_care_of_password_managers/)

Y esto podría seguir y seguir...
