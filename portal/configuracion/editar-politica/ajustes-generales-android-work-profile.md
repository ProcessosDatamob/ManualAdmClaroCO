---
layout:
  title:
    visible: true
  description:
    visible: false
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
---

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

<mark style="color:red;background-color:orange;">ATUALIZAR IMAGEM</mark>

<figure><img src="../../../.gitbook/assets/image (2) (1).png" alt=""><figcaption></figcaption></figure>

### Bloqueo Total

<mark style="color:red;">Esta funcionalidad permite al usuario administrador configurar un bloqueo total del dispositivo fuera de un período de tiempo específico o al alcanzar el límite de datos móviles. De esta manera, se puede bloquear el dispositivo cuando el usuario no esté en horario laboral o cuando se alcance el límite de datos móviles definido para el ciclo actual.</mark>

<mark style="color:red;">Estando en la pestaña "Configuraciones" de la pantalla "Editar Políticas", haga clic en "Bloqueo Total" para ver las opciones de configuración.</mark>

<mark style="color:red;background-color:orange;">ADICIONAR IMAGEM</mark>

&#x20;Para realizar el bloqueo de dispositivos fuera del horario de trabajo, siga los siguientes pasos:<mark style="color:red;">:</mark>

1. Ative la opción "Bloquear dispositivo fuera del horario de laboral".
2. Complete el campo "Días laborales" con los días laborables de la semana, especificando el día de inicio y el día de finalización.<mark style="color:red;">.</mark>
3. Complete el campo "Horario de trabajo" con la hora de inicio y la hora de finalización del horario laboral.

{% hint style="info" %}
<mark style="color:red;">**OBSERVACIÓN**</mark>

<mark style="color:red;">Al dejar los campos en blanco, el sistema considerará el período completo del día.</mark>
{% endhint %}

<mark style="color:red;">Cuando el dispositivo esté fuera del horario de trabajo configurado, el ocultará todas las aplicaciones del dispositivo, excepto "Teléfono", "" y "Play Store".</mark>

<mark style="color:red;">Las aplicaciones instaladas en el dispositivo solo se ocultarán y se mostrará una notificación fija en el dispositivo con el siguiente mensaje: "Acceso a las aplicaciones bloqueado por el administrador".</mark>

<mark style="color:red;">De este modo, cuando el dispositivo esté fuera del horario de trabajo configurado, no se podrá acceder a las aplicaciones ocultas; sin embargo, se podrá acceder a las configuraciones del dispositivo, y será posible apagar o reiniciar el dispositivo.</mark>

<mark style="color:red;">Cuando el dispositivo esté dentro del horario de trabajo configurado, todas las aplicaciones volverán a mostrarse sin necesidad de reinstalarlas.</mark>

### <mark style="color:red;">**Bloqueo por Límite de Datos**</mark>

&#x20;<mark style="color:red;">Para activar el bloqueo del dispositivo por límite de uso de datos móviles, habilite la opción "Bloquear dispositivo por límite de uso de datos móviles".</mark>

<mark style="color:red;">Cuando el dispositivo alcance el límite de uso de datos móviles configurado para el ciclo actual, el ocultará todas las aplicaciones del dispositivo, excepto "Teléfono", "Aplicación de Gestión" y "Play Store".</mark>

<mark style="color:red;">El dispositivo mostrará una notificación fija con el mensaje: "Acceso a las aplicaciones bloqueado por el administrador". Esta notificación informará al usuario sobre el bloqueo.</mark>

<mark style="color:red;">De este modo, cuando el dispositivo esté bloqueado por el límite de uso de datos, las aplicaciones ocultas no podrán ser accedidas, pero seguirán instaladas. El usuario aún podrá acceder a las configuraciones del dispositivo, y será posible apagar o reiniciar el dispositivo.</mark>

<mark style="color:red;">Además, al instalar una aplicación a través de Play Store o de forma remota, la aplicación será ocultada.</mark>

<mark style="color:red;">Si el uso de datos móviles está por debajo del límite o si el administrador desactiva la configuración "Bloquear dispositivo por límite de uso de datos móviles" en la política, el mostrará correctamente todas las aplicaciones del dispositivo según la política provisionada.</mark>

<mark style="color:red;">Si el dispositivo se encuentra en cualquiera de las condiciones que requieren la activación de un Bloqueo Total (fuera del horario de trabajo o alcanzando el límite de datos móviles), la configuración y activación de un Bloqueo Total no anulará ni interferirá con la configuración y activación del otro. Ambos bloqueos pueden coexistir y aplicarse según sus respectivas condiciones.</mark>

### Restricciones de contraseña - Dispositivo

<figure><img src="../../../.gitbook/assets/image (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

### Restricciones de contraseña - Perfil Laboral

Si la clave está activada permite al usuario mantener la misma contraseña definida para el "Dispositivo" en el "Perfil de Trabajo".

Cuando la opción está desactivada, obliga al usuario a crear una contraseña diferente de la contraseña personal para acceder al perfil de trabajo. Se muestran las mismas configuraciones descritas en la tabla anterior para establecer la contraseña.

<figure><img src="../../../.gitbook/assets/image (2) (1) (1).png" alt=""><figcaption></figcaption></figure>

Sigue el detalle de la configuración de ambas restricciones de contraseña:

| Configuración                                                                 | Descripción                                                                                                                                                                                                                                     |
| ----------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Calidad de la contraseña**                                                  | <p></p><p>En esta configuración, tenemos las siguientes opciones disponibles:</p><ul><li>Ninguna</li><li>Biometría</li><li>Alguna</li><li>Numérica</li><li>Complejo Numérico</li><li>Alfabético</li><li>Alfanumérica</li><li>Compleja</li></ul> |
| **Historial máximo de contraseñas que el usuario no podrá volver a utilizar** | Define el número de contraseñas que ya se han usado y no pueden ser reutilizadas                                                                                                                                                                |
| **Máximo de contraseñas incorrectas antes de ejecutar wipe**                  | Define o máximo de tentativas incorretas antes de executar ou Wipe                                                                                                                                                                              |
| **Tiempo de espera de expiración de la contraseña (días)**                    | Define cuántos días la contraseña va a tardar en expirar                                                                                                                                                                                        |
| **Requerir desbloqueo de contraseña**                                         | En esta configuración tenemos las opciones: Dispositivo predeterminado, es decir, definido como configurado en el dispositivo o todos los días, en este caso la contraseña se pedirá todos los días                                             |
