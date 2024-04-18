# INFORMACIÓN GENERAL

**El propósito de este manual es ayudar al usuario administrador en el uso y configuración del \<NomeProduto>.**

## **Visión general de la solución**

**\<NomeProduto>** es una solución de gestión de movilidad empresarial que consta de:

* **Portal de Administración** **\<NomeProduto>** - sistema web que realiza toda la gestión de los dispositivos móviles de la empresa.
* **Aplicación \<NomeProduto>** - aplicación Android que recopila toda la información de uso y consumo del dispositivo móvil.  Esta aplicación se instala por defecto estando presente en todos los dispositivos que se registran en el sistema.
* **Aplicación Security Browser** - Aplicación Android de navegación web responsable de realizar los bloqueos de sitios web, así como monitorear la navegación del usuario del dispositivo.

{% hint style="warning" %}
IMPORTANTE

La aplicación Security Browser está disponible en Play Store y debe incluirse en la política de registro de los dispositivos. La sección [Bloqueo de Sitios Web](bloqueo-de-sitios-web-security-browser.md) presenta paso a paso la inclusión y configuración de la aplicación Security Browser.&#x20;
{% endhint %}

Desde el Portal **\<NomeProduto>** es posible acceder a la información sobre el consumo y uso de los dispositivos asignados a los empleados de la empresa. También es posible definir políticas de bloqueos para restringir el uso indebido de los dispositivos, permitiendo al administrador evaluar y aumentar la productividad de los empleados, a través del análisis y la gestión de los recursos de telecomunicaciones de la empresa.

## **Flujo de Datos**&#x20;

Toda la información recopilada por la aplicación **\<NomeProduto>** se envía periódicamente a los servidores del sistema.  Los datos de consumo recopilados por la aplicación se envían de acuerdo con el tiempo configurado en el portal, en la opción "Sincronizar cada", que varía de 60 minutos a 24 horas.

Los datos de localización se recogen cada 3 minutos en la aplicación y se envía al portal de acuerdo con la opción de sincronización elegida.&#x20;

## **Almacenamiento de datos**

Todos los datos del Portal permanecen almacenados durante 6 meses, después de lo cual la información se elimina de los servidores.

En caso de que los servidores de la solución no estén disponibles, la aplicación mantendrá la información hasta que se restablezca la comunicación con los servidores.

Todos los datos enviados por el portal y recibidos por el dispositivo permanecen almacenados, lo que garantiza que las políticas de bloqueo permanezcan activas, incluso cuando no se tenga acceso a Internet e independientemente de la disponibilidad de los servidores. La conexión será necesaria solo para recibir nuevas políticas y mensajes o enviar los datos al Portal.

## **Nivel de Acceso al Portal**

El Portal de Administración tiene dos niveles de acceso:

* **Administrador del portal:** este nivel brinda acceso completo a la información y le permite establecer políticas de bloqueo para dispositivos;
* **Administrador de grupo:** este nivel da acceso a los datos de su grupo y permite enviar mensajes al grupo;

Para saber cómo crear un administrador de portal o grupo, lea la sección "[Configuración inicial y niveles](readme/configuracion-inicial-y-niveles.md)'.
