# Política de Privacidad de GlucScreen

**Última actualización:** Noviembre de 2026

En **GlucScreen** (en adelante, la "Aplicación"), respetamos y protegemos la privacidad de nuestros usuarios. Esta política de privacidad explica cómo se maneja tu información cuando utilizas nuestra aplicación móvil.

### 1. Recopilación de Información y Datos
GlucScreen **no recopila, almacena ni procesa ningún tipo de información personal, credenciales ni datos de salud en servidores propios**. 

* **Credenciales de Acceso:** Tu correo electrónico y contraseña introducidos al iniciar sesión se utilizan exclusivamente para autenticarte de forma directa y segura con los servidores oficiales de **LibreView**. Estos datos se almacenan de manera local y cifrada únicamente en tu dispositivo mediante almacenamiento seguro (`shared_preferences` / almacenamiento local cifrado).
* **Datos de Glucemia:** Las lecturas de glucosa se obtienen en tiempo real mediante solicitudes HTTPS cifradas directamente desde los servidores de LibreView hacia tu dispositivo. Ningún dato glucémico pasa por servidores intermediarios ni es registrado por nosotros.

### 2. Uso de Permisos del Dispositivo
La aplicación requiere permisos básicos estrictamente necesarios para su funcionamiento como pantalla Always-On Display (AOD):
* **Acceso a Internet:** Necesario para consultar de forma periódica las lecturas de glucosa a través de la API oficial.
* **Bloqueo de activación (Wakelock):** Necesario para evitar que la pantalla del dispositivo se apague mientras actúa como monitor dedicado en una mesilla de noche o cocina.

### 3. Servicios de Terceros
GlucScreen se comunica de forma exclusiva con la infraestructura de **LibreView** (`libreview.io`). Te recomendamos revisar los términos y la política de privacidad de LibreView / Abbott Laboratories para más información sobre cómo gestionan los datos en su nube.

### 4. Seguridad
Tomamos medidas razonables para proteger la información local de tu dispositivo. Sin embargo, recuerda que ningún método de transmisión por internet o almacenamiento digital es 100% seguro.

### 5. Menores de Edad
La aplicación está destinada al seguimiento de pacientes con diabetes bajo supervisión de adultos o usuarios responsables. No recopilamos conscientemente información personal de menores sin el consentimiento de sus tutores legales.

### 6. Cambios en esta Política de Privacidad
Podemos actualizar nuestra política de privacidad ocasionalmente. Te recomendamos revisar esta página de forma periódica para cualquier cambio.

### 7. Contacto
Si tienes alguna duda o sugerencia sobre nuestra política de privacidad, puedes ponerte en contacto a través del repositorio oficial de GitHub del proyecto.
