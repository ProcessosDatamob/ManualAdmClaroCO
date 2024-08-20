# CONFIGURACIÓN INICIAL Y NIVELES

Al ingresar al Portal  **Claro Monitor Empresarial**, el usuario tendrá acceso a las configuraciones y funcionalidades.

## **Configuración de inicio**

Al ingresar al portal de administración **Claro Monitor Empresarial** por vez primera, se recomienda realizar la siguiente configuración:

* **Perfil de Consumo -** Las configuraciones de perfil son importantes ya que se utilizan en el Dashboard del Portal para mostrar el consumo en porcentaje con respecto a los límites definidos. Además, con la información de perfil definida, el sistema puede enviar notificaciones por correo electrónico al administrador cuando se alcanza el 80%, 90% y 100% del perfil de consumo configurado. Para garantizar que todos los datos capturados se analicen correctamente, siga las instrucciones detalladas en la sección "[Perfil de Consumo](../configuracion/perfil-de-consumo.md)" de este manual.  &#x20;
* **Día de inicio del ciclo -** para definir la fecha de inicio de la contabilización de los datos que serán analizados (detallado en la sección "[Configuraciones Generales](../empresa/configuracion-general.md)" de este manual).

## **Configuración de Perfil de Consumo**

El perfil de consumo se puede definir en tres niveles (Empresa / Grupo / Usuario) y estos se aplican a los dispositivos de la siguiente manera:

* **Empresa (General) -** Al crear una configuración de perfil en ese nivel el sistema verificará si existe una regla configurada en el nivel de usuario. Si no existe, verifica si existe una regla configurada en el nivel de Grupo y, si tampoco existe, el sistema aplicará en los dispositivos de la Empresa la regla configurada a nivel de Empresa;
* **Grupo -** Al crear una configuración de perfil en ese nivel, el sistema verificará si existe una configuración en el nivel de Usuario, si no existe, el sistema aplicará en los dispositivos del grupo la regla configurada en el nivel del Grupo;
* **Usuario -** Al crear una configuración de perfil en ese nivel, el sistema aplicará en el dispositivo del usuario la regla configurada.

La siguiente imagen muestra la pantalla de configuración del perfil de consumo a la que se accede desde el menú "[Configuraciones](../configuracion/)". Un rectángulo destaca el acceso a las pestañas "General", "Grupos" y "Usuarios".

<figure><img src="../.gitbook/assets/9 (12).png" alt=""><figcaption></figcaption></figure>
