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

# Información General

**\<NomeProduto>** es una solución de gestión de movilidad empresarial que consta de:

* **Portal de Administración** **\<NomeProduto>** - sistema web que realiza toda la gestión de los dispositivos móviles de la empresa.
* **Aplicación \<NomeProduto>** - aplicación Android que recopila toda la información de uso y consumo del dispositivo móvil.  Esta aplicación se instala por defecto estando presente en todos los dispositivos que se registran en el sistema.
* **Aplicación Security Browser** - Aplicación Android de navegación web responsable de realizar los bloqueos de sitios web, así como monitorear la navegación del usuario del dispositivo.

{% hint style="warning" %}
**IMPORTANTE**

La aplicación Security Browser está disponible en Play Store y debe incluirse en la política de registro de los dispositivos. La sección [Bloqueo de Sitios Web](../portal/configuracion/editar-politica/aplicaciones/bloqueo-de-sitios-web-security-browser.md) presenta paso a paso la inclusión y configuración de la aplicación Security Browser.&#x20;
{% endhint %}

Desde el Portal **\<NomeProduto>** es posible acceder a la información sobre el consumo y uso de los dispositivos asignados a los empleados de la empresa. También es posible definir políticas de bloqueos para restringir el uso indebido de los dispositivos, permitiendo al administrador evaluar y aumentar la productividad de los empleados, a través del análisis y la gestión de los recursos de telecomunicaciones de la empresa.

## **Flujo de Datos**&#x20;

Toda la información recopilada por la aplicación **\<NomeProduto>** se envía periódicamente a los servidores del sistema.  Los datos de consumo recopilados por la aplicación se envían de acuerdo con el tiempo configurado en el portal, en la opción "Sincronizar cada", que varía de 60 minutos a 24 horas.

Los datos de localización se recogen cada 3 minutos en la aplicación y se envía al portal de acuerdo con la opción de sincronización elegida.&#x20;

## **Almacenamiento de datos**

Todos los datos del Portal permanecen almacenados durante 6 meses, después de lo cual la información se elimina de los servidores.

En caso de que los servidores de la solución no estén disponibles, la aplicación mantendrá la información hasta que se restablezca la comunicación con los servidores.

Todos los datos enviados por el portal y recibidos por el dispositivo permanecen almacenados, lo que garantiza que las políticas de bloqueo permanezcan activas, incluso cuando no se tenga acceso a Internet e independientemente de la disponibilidad de los servidores. La conexión será necesaria solo para recibir nuevas políticas y mensajes o enviar los datos al Portal.

##



## Compatibilidad de Dispositivos

El producto **\<NomeProduto>** fue creado en asociación con Google en el programa Android Enterprise. Google mantiene una lista de dispositivos homologados y recomendados para su uso con Android Enterprise en su Directorio de Soluciones Enterprise.  Para tener acceso a los dispositivos recomendados dentro del programa Android Enterprise, es necesario dirigirse al Directorio de Soluciones de Google utilizando el enlace proporcionado: [https://androidenterprisepartners.withgoogle.com/devices/](https://androidenterprisepartners.withgoogle.com/devices/).

El sello Android Enterprise Recommended identifica dispositivos Android que cumplen con ciertos estándares de seguridad, rendimiento y gestión adecuados para su uso en entornos empresariales. Cuando un dispositivo recibe la certificación "Android Enterprise Recommended", esto significa que ha pasado por pruebas rigurosas y cumple con requisitos específicos establecidos por Google.

El que un dispositivo no se encuentre en la lista de recomendados de Google no significa que no funcionará. Actualmente, Android Enterprise es compatible con todas las versiones de Android desde Android 6.0. Sin embargo, algunas características pueden no estar disponibles en versiones anteriores del sistema operativo. Se recomienda utilizar las versiones más nuevas de Android para aprovechar todas las características y beneficios que ofrece la plataforma.

Importante destacar que **\<NomeProduto>** fue desarrollado con  Google Android Enterprise y otras tecnologías adicionales, esto significa que algunas funciones, como por ejemplo, localización, consumo de batería y almacenamiento, pueden presentar comportamiento diferente del esperado dependiendo de las configuraciones del sistema operativo del dispositivo. &#x20;
