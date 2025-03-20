# Instalación remota de aplicaciones

Esta pantalla del sistema tiene como objetivo posibilitar la instalación, desinstalación y actualización remota de aplicaciones en los dispositivos de la empresa, sin la necesidad de subir la la aplicación a la Play Store. Para que esto sea posible, la aplicación debe estar en un servidor con acceso público a una URL y en un entorno HTTPS. Si el archivo no cumple con estas condiciones, la descarga de la aplicación no se realizará.\
Para gestionar y enviar la instalación remota de aplicaciones a los dispositivos, haga clic en el menú “Gestión de Aplicaciones” y en la opción "Instalación Remota de Aplicaciones".

<figure><img src="../../../.gitbook/assets/Captura de tela 2024-05-16 144645 (2).png" alt=""><figcaption></figcaption></figure>

El sistema mostrará una lista con las aplicaciones instaladas en los dispositivos de la empresa. La pantalla de visualización de las aplicaciones se presenta a continuación.

<figure><img src="../../../.gitbook/assets/Captura de tela 2024-05-16 145207.png" alt=""><figcaption></figcaption></figure>

1. El sistema mostrará un filtro de un periodo por fecha.
2. En el campo de búsqueda es posible buscar por una información específica.
3. Para exportar el informe de las aplicaciones, haga clic en el botón “Excel”.
4. Para copiar la información de las aplicaciones, haga clic en el botón “Copiar”.
5. En el botón "Nueva Instalación" es posible enviar la instalación remota de una aplicación a los dispositivos. Para más detalles, acceda a "Instalar Aplicación" en esta misma página.
6. La lista de información de las aplicaciones muestra los siguientes detalles: Fecha de Envío, Nombre de la Aplicación, Nombre del paquete y URL para descarga.
7. Ordene la lista de aplicaciones por las columnas con las flechas "↑↓".
8. Al hacer clic en los tres puntos "...", y hacer clic en “Ver Instalación", es posible acceder a la pantalla “Detalles de Envío de la Aplicación".

<figure><img src="../../../.gitbook/assets/image (127).png" alt=""><figcaption></figcaption></figure>

#### **Instalar Aplicación**

Para instalar una aplicación remotamente, siga los pasos a continuación:

1. Seleccione la política y los usuarios de dispositivos.
2. Complete los campos obligatorios: Nombre, Nombre del paquete y URL para descarga.
3. Haga clic en "Enviar".

El Companion descargará la aplicación recibida y solicitará la confirmación del usuario para realizar la instalación de la aplicación descargada. Se mostrará una notificación informando que hay una aplicación disponible para la instalación:

**"¡Tiene una instalación pendiente! Haga clic aquí para iniciar."**

Después de hacer clic en la notificación, se solicitará nuevamente la instalación.

{% hint style="info" %}
**OBSERVACIÓN**\
Al confirmar el envío desde el portal, el sistema mostrará un mensaje de éxito, enviará una notificación push de instalación de la aplicación a todos los dispositivos de la política y a los usuarios seleccionados, solicitando la autorización del usuario y añadirá el paquete de la aplicación en la política de todos los dispositivos seleccionados como "Disponible". Es decir, la instalación no es silenciosa.
{% endhint %}

<figure><img src="../../../.gitbook/assets/image (128).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
**NOTA**\
El aplicativo enviado a través de la instalación remota se envía con el tipo de instalación "Disponible". Por lo tanto, si el usuario desinstala la aplicación, para volver a instalarla, el administrador deberá enviar nuevamente el comando de instalar la aplicación desde el portal al dispositivo.\
Actualmente, esta funcionalidad no está disponible en políticas que tengan el Modo Kiosco activado.\
Si el nombre del paquete informado por el usuario es diferente del nombre de paquete de la aplicación disponible en el enlace de descarga:

* La notificación permanecerá fija en el dispositivo hasta que el mismo sea reiniciado.
* La aplicación será eliminada del dispositivo automáticamente por Google.
{% endhint %}
