# Instalación remota de aplicaciones

Esta pantalla del sistema tiene como objetivo posibilitar la instalación, desinstalación y actualización remota de aplicaciones en los dispositivos de la empresa, sin la necesidad de subir la la aplicación a la Play Store. Para que esto sea posible, la aplicación debe estar en un servidor con acceso público a una URL y en un entorno HTTPS. Si el archivo no cumple con estas condiciones, la descarga de la aplicación no se realizará.\
Para gestionar y enviar la instalación remota de aplicaciones a los dispositivos, haga clic en el menú “Gestión de Aplicaciones” y en la opción "Instalación Remota de Aplicaciones".

<figure><img src="../.gitbook/assets/Captura de tela 2024-05-16 144645 (2).png" alt=""><figcaption></figcaption></figure>

El sistema mostrará una lista con las aplicaciones instaladas en los dispositivos de la empresa. La pantalla de visualización de las aplicaciones se presenta a continuación.

<figure><img src="../.gitbook/assets/Captura de tela 2024-05-16 145207.png" alt=""><figcaption></figcaption></figure>

1. El sistema mostrará un filtro de un periodo por fecha.
2. En el campo de búsqueda es posible buscar por una información específica.
3. Para exportar el informe de las aplicaciones, haga clic en el botón “Excel”.
4. Para copiar la información de las aplicaciones, haga clic en el botón “Copiar”.
5. En el botón "Nueva Instalación" es posible enviar la instalación remota de una aplicación a los dispositivos. Para más detalles, acceda a "Instalar Aplicación" en esta misma página.
6. La lista de información de las aplicaciones muestra los siguientes detalles: Fecha de Envío, Nombre de la Aplicación, Nombre del paquete y URL para descarga.
7. Ordene la lista de aplicaciones por las columnas con las flechas "↑↓".
8. Al hacer clic en los tres puntos "...", y hacer clic en “Ver Instalación", es posible acceder a la pantalla “Detalles de Envío de la Aplicación".

<figure><img src="../.gitbook/assets/image (127).png" alt=""><figcaption></figcaption></figure>

#### <mark style="color:red;">**Instalar Aplicación**</mark>

<mark style="color:red;">Para instalar una aplicación remotamente, siga los pasos a continuación:</mark>

1. <mark style="color:red;">Seleccione la política y los usuarios de dispositivos vinculados a políticas de los siguientes modos de gestión: Android, Android - Block SIM y Android - Work Profile.</mark>
2. <mark style="color:red;">Complete los campos obligatorios: Nombre, Nombre del paquete y URL para descarga.</mark>
3. <mark style="color:red;">Haga clic en "Enviar".</mark>

<mark style="color:red;">El Companion descargará la aplicación recibida y solicitará la confirmación del usuario para realizar la instalación de la aplicación descargada. Se mostrará una notificación informando que hay una aplicación disponible para la instalación:</mark>

<mark style="color:red;">**"¡Tiene una instalación pendiente! Haga clic aquí para iniciar."**</mark>

<mark style="color:red;">Después de hacer clic en la notificación, se solicitará nuevamente la instalación.</mark>

{% hint style="info" %}
<mark style="color:red;">**OBSERVACIÓN**</mark>\ <mark style="color:red;">Al confirmar el envío, el sistema mostrará un mensaje de éxito, enviará una notificación push de instalación de la aplicación a todos los dispositivos de la política y a los usuarios seleccionados, solicitando la autorización del usuario y añadirá el paquete de la aplicación en la política de todos los dispositivos seleccionados como "Disponible". Es decir, la instalación no es silenciosa.</mark>
{% endhint %}

<figure><img src="../.gitbook/assets/image (128).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
<mark style="color:red;">**NOTA**</mark>\ <mark style="color:red;">El aplicativo enviado a través de la instalación remota se envía con el tipo de instalación "Disponible". Por lo tanto, si el usuario desinstala la aplicación, para volver a instalarla, el administrador deberá enviar nuevamente el comando de instalar la aplicación vía portal al dispositivo.</mark>\ <mark style="color:red;">Actualmente, esta funcionalidad no está disponible en políticas que tengan el Modo Kiosco activado.</mark>\ <mark style="color:red;">Si el paquete insertado por el usuario es diferente del paquete de la aplicación disponible en el enlace de descarga:</mark>

* <mark style="color:red;">La notificación permanecerá fija en el dispositivo hasta que el mismo sea reiniciado.</mark>
* <mark style="color:red;">La aplicación será eliminada del dispositivo automáticamente por Google.</mark>
{% endhint %}
