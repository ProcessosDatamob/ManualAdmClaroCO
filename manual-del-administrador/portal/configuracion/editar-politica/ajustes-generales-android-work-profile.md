# Ajustes generales - Android - Work Profile

Profile es un modo de gestión exclusivo para dispositivos personales, permite que un usuario con su dispositivo personal pueda crear un entorno seguro para utilizar aplicaciones de trabajo, Garantizar la seguridad necesaria para la información de la empresa y la privacidad del usuario, ya que el dispositivo es personal.

Para ello, el usuario debe descargar la aplicación Android Device Policy en la tienda de aplicaciones y leer el QR CODE de la política con el modo de gestión "**Android - Work Profile**". Al final de la provisión, el dispositivo mostrará aplicaciones de trabajo con el icono del perfil de trabajo (maletín azul) y las aplicaciones privadas sin iconos.

{% hint style="warning" %}
**IMPORTANTE**

* No es necesario realizar el restablecimiento de fábrica en el dispositivo para realizar la provisión, simplemente descargue la aplicación " **Android Device Policy**" y siga los pasos de aprovisionamiento.
* Al ejecutar el comando "**Quitar dispositivo**" en el menú agrupado de la pantalla "**Lista de dispositivos**", se eliminan el perfil de trabajo del dispositivo y las aplicaciones de trabajo. No se reinicia el dispositivo.
* El usuario tiene autonomía para eliminar el perfil de trabajo a través del dispositivo, sin que sea necesaria la autorización del Administrador.
* Android Go admite escenarios de implementación totalmente administrados y dedicados. Sin embargo, el perfil de trabajo (BYOD) es opcional y por lo tanto ausente en la mayoría de los dispositivos Go.
{% endhint %}

Las configuraciones generales se agrupan en tipos:

* Bloqueo Total
* Restricciones de contraseña - Dispositivo
* Restricciones de contraseña - Perfil Laboral

<figure><img src="../../../../.gitbook/assets/image (5) (1).png" alt=""><figcaption></figcaption></figure>

### Bloqueo Total

Esta funcionalidad permite al usuario administrador configurar un bloqueo total del dispositivo fuera de un período de tiempo específico o al alcanzar el límite de datos móviles. De esta manera, se puede bloquear el dispositivo cuando el usuario no esté en horario laboral o cuando se alcance el límite de datos móviles definido para el ciclo actual.

Estando en la pestaña "Configuraciones" de la pantalla "Editar Políticas", haga clic en "Bloqueo Total" para ver las opciones de configuración.

&#x20;Para realizar el bloqueo de dispositivos fuera del horario de trabajo, siga los siguientes pasos:<mark style="color:red;">:</mark>

1. Ative la opción "Bloquear dispositivo fuera del horario de laboral".
2. Complete el campo "Días laborales" con los días laborables de la semana, especificando el día de inicio y el día de finalización.
3. Complete el campo "Horario de trabajo" con la hora de inicio y la hora de finalización del horario laboral.

{% hint style="info" %}
**OBSERVACIÓN**

Al dejar los campos en blanco, el sistema considerará el período completo del día, o sea, 24 horas.
{% endhint %}

Cuando el dispositivo esté fuera del horario de trabajo configurado, se ocultarán todas las aplicaciones del dispositivo, excepto "Teléfono", "\<NomeProduto>" y "Play Store".

Las aplicaciones instaladas en el dispositivo solo se ocultarán y se mostrará una notificación fija en el dispositivo con el siguiente mensaje: "Acceso a las aplicaciones bloqueado por el administrador".

De este modo, cuando el dispositivo esté fuera del horario de trabajo configurado, no se podrá acceder a las aplicaciones ocultas; sin embargo, se podrá acceder a las configuraciones del dispositivo, y será posible apagar o reiniciar el dispositivo.

Cuando el dispositivo esté dentro del horario de trabajo configurado, todas las aplicaciones volverán a mostrarse sin necesidad de reinstalarlas.

### **Bloqueo por Límite de Datos**

Para activar el bloqueo del dispositivo por límite de uso de datos móviles, habilite la opción "Bloquear dispositivo por límite de uso de datos móviles".

Cuando el dispositivo alcance el límite de uso de datos móviles configurado para el ciclo actual, el ocultará todas las aplicaciones del dispositivo, excepto "Teléfono", "\<NomeProduto>" y "Play Store".

El dispositivo mostrará una notificación fija con el mensaje: "Acceso a las aplicaciones bloqueado por el administrador". Esta notificación informará al usuario sobre el bloqueo.

De este modo, cuando el dispositivo esté bloqueado por el límite de uso de datos, las aplicaciones ocultas no podrán ser accedidas, pero seguirán instaladas. El usuario aún podrá acceder a las configuraciones del dispositivo, y será posible apagar o reiniciar el dispositivo.

Además, al instalar una aplicación a través de Play Store o de forma remota, la aplicación será ocultada.

Si el uso de datos móviles está por debajo del límite o si el administrador desactiva la configuración "Bloquear dispositivo por límite de uso de datos móviles" en la política, el mostrará correctamente todas las aplicaciones del dispositivo según la política provisionada.

Si el dispositivo se encuentra en cualquiera de las condiciones que requieren la activación de un Bloqueo Total (fuera del horario de trabajo o alcanzando el límite de datos móviles), la configuración y activación de un Bloqueo Total no anulará ni interferirá con la configuración y activación del otro. Ambos bloqueos pueden coexistir y aplicarse según sus respectivas condiciones.

### Restricciones de contraseña - Dispositivo

<table data-header-hidden><thead><tr><th width="270"></th><th></th></tr></thead><tbody><tr><td><strong>Configuración</strong></td><td><strong>Descripción</strong></td></tr><tr><td>Calidad mínima de la contraseña</td><td><p>Cuando la calidad mínima de la contraseña es "Cualquiera" significa que se requiere una contraseña, pero no hay restricciones sobre lo que la contraseña debe contener.</p><p>Las otras posibilidades de configuración de contraseña son:</p><ul><li>ninguna - no hay requisito de contraseña;</li><li>numérica - la contraseña debe contener <strong>al menos</strong> caracteres numéricos;</li><li>numérica compleja - la contraseña debe contener <strong>al menos</strong> caracteres numéricos sin secuencias repetidas (4444) u ordenadas (1234, 4321, 2468).</li><li>alfabética - la contraseña debe contener <strong>al menos</strong> caracteres alfabéticos (o símbolos).</li><li>alfanumérica - la contraseña debe contener <strong>al menos</strong> caracteres numéricos y alfabéticos (o símbolos).</li><li>compleja - la contraseña debe contener <strong>al menos</strong> una letra, un carácter numérico y un símbolo.</li><li>biometría - El dispositivo debe protegerse con una tecnología de reconocimiento biométrico de baja seguridad como mínimo.</li></ul><p><em>Para más información, acceda a la sección</em> <a href="ajustes-generales-android-work-profile.md#exigencia-de-contrasena-y-cumplimiento-de-la-politica"><em>Exigencia de Contraseña y Cumplimiento de la Política</em></a> <em>más abajo en esta página.</em></p></td></tr><tr><td>Historial máximo de contraseñas que el usuario no podrá volver a utilizar</td><td>Define la cantidad máxima del historial de las últimas contraseñas utilizadas que el usuario no podrá volver a usar. Ingrese un número siendo el valor máximo 10.</td></tr><tr><td>Máximo de contraseñas incorrectas antes de ejecutar Wipe</td><td>Utilice esta configuración si desea establecer un número de intentos de contraseña incorrectos aceptados (máximo 10). Después del número de intentos establecido, el dispositivo ejecutará un borrado (wipe) y restablecerá los datos de fábrica.</td></tr><tr><td>Tiempo de espera de expiración de la contraseña (días)</td><td>Utilice esta configuración si desea establecer una cantidad de días para la expiración de la contraseña. Después de este período (días) la contraseña necesitará ser restablecida por el usuario.</td></tr><tr><td>Requerir desbloqueo de contraseña</td><td><p>Con esta opción se define el periodo que transcurre después de desbloquear un dispositivo o perfil de trabajo con una forma de autenticación segura (contraseña, PIN, patrón) que además se puede desbloquear mediante cualquier otro método de autenticación (p.ej., huella dactilar, agentes de confianza o rostros). Una vez transcurrido el período especificado, solo se pueden usar formas seguras de autenticación para desbloquear el dispositivo o el perfil de trabajo.</p><p>Si se selecciona: “ Todos los días” el tiempo de espera se establece en 24hrs</p><p>Si se selecciona: “Patrón del dispositivo”, el tiempo de espera se establece en el valor predeterminado del dispositivo.</p></td></tr><tr><td>Longitud mínima de la contraseña</td><td>Esta configuración establece el tamaño mínimo necesario para las contraseñas creadas, fortaleciendo la seguridad de los datos.</td></tr><tr><td>Número mínimo de letras requeridas en la contraseña</td><td>Esta configuración establece la cantidad mínima de letras necesarias para las contraseñas, con un número específico de caracteres alfabéticos en las combinaciones de contraseñas.</td></tr><tr><td>Número mínimo de letras minúsculas requeridas en la contraseña</td><td>Esta configuración determina el mínimo de letras minúsculas necesarias en contraseñas</td></tr><tr><td>Número mínimo de caracteres que no sean letras (dígitos numéricos o símbolos) necesarios en la contraseña</td><td>Establece el mínimo de caracteres no alfabéticos necesarios en las contraseñas</td></tr><tr><td>Número mínimo de dígitos numéricos necesarios en la contraseña</td><td>Estipula el número mínimo de dígitos numéricos necesarios en las contraseñas</td></tr><tr><td>Número mínimo de símbolos necesarios en la contraseña</td><td>Esta configuración establece la cantidad mínima de símbolos requeridos en las contraseñas, dentro de las combinaciones de contraseñas.</td></tr><tr><td>Número mínimo de letras mayúsculas requeridas en la contraseña</td><td>Establece la cantidad mínima de letras mayúsculas obligatorias en la contraseña.</td></tr></tbody></table>

<figure><img src="../../../../.gitbook/assets/image (7) (1).png" alt=""><figcaption></figcaption></figure>

### Restricciones de contraseña - Perfil Laboral

Si la clave está activada permite al usuario mantener la misma contraseña definida para el "Dispositivo" en el "Perfil de Trabajo".

Cuando la opción está desactivada, obliga al usuario a crear una contraseña diferente de la contraseña personal para acceder al perfil de trabajo. Se muestran las mismas configuraciones descritas en la tabla anterior para establecer la contraseña.

<figure><img src="../../../../.gitbook/assets/image (2) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

Sigue el detalle de la configuración de ambas restricciones de contraseña:

| Configuración                                                                 | Descripción                                                                                                                                                                                                                            |
| ----------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Calidad de la contraseña**                                                  | <p></p><p></p><p>En esta configuración, tenemos las siguientes opciones disponibles:</p><ul><li>Biometría</li><li>Alguna</li><li>Numérica</li><li>Numérica Compleja</li><li>Alfabética</li><li>Alfanumérica</li><li>Compleja</li></ul> |
| **Historial máximo de contraseñas que el usuario no podrá volver a utilizar** | Define el número de contraseñas que ya se han usado y no pueden ser reutilizadas                                                                                                                                                       |
| **Máximo de contraseñas incorrectas antes de ejecutar wipe**                  | Define o máximo de tentativas incorretas antes de executar ou Wipe                                                                                                                                                                     |
| **Tiempo de espera de expiración de la contraseña (días)**                    | Define cuántos días la contraseña va a tardar en expirar                                                                                                                                                                               |
| **Requerir desbloqueo de contraseña**                                         | En esta configuración tenemos las opciones: Dispositivo predeterminado, es decir, definido como configurado en el dispositivo o todos los días, en este caso la contraseña se pedirá todos los días                                    |
