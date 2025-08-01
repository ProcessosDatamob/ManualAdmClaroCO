# Modo Quiosco

Esta configuración tiene como objetivo permitir la creación de un entorno en el que el usuario del dispositivo solo pueda acceder a las aplicaciones previamente autorizadas por el administrador, es decir, solo se mostrarán los íconos de las aplicaciones seleccionadas en la pantalla del dispositivo.

Para acceder a la configuración del "**Modo Quiosco**", siga estos pasos:&#x20;

1. En la pantalla "[Editar política](./)", seleccione la pestaña "**Modo Quiosco**".&#x20;
2. Active el modo quiosco haciendo clic en el botón de activación.

<figure><img src="../../../../.gitbook/assets/Captura de tela 2024-01-11 135757.png" alt=""><figcaption></figcaption></figure>

3. En la pantalla se mostrará un mensaje de confirmación. Confirme haciendo clic en el botón "Activar".

<figure><img src="../../../../.gitbook/assets/image (32).png" alt=""><figcaption></figcaption></figure>

4. Al activar el Modo Quiosco en la política y aprovisionar un dispositivo con esta política, la aplicación Kiosk Launcher Manager se instalará automáticamente en el dispositivo.

Cuando el dispositivo instale la aplicación Kiosk, la aplicación capturará la lista de todos los aplicativos instalados en el dispositivo y la enviará al Portal de administración.  Además, enviará las  configuraciones administradas al portal y cambiará el lanzador del dispositivo por el de la aplicación Kiosk. No permitirá que el usuario cambie el lanzador en el dispositivo y mantendrá la configuración del Modo Quiosco recibida en la política.

### Opciones de configuración del Modo Quiosco

Cuando el modo quiosco esté activado, estarán disponibles las siguientes opciones de configuración:

<figure><img src="../../../../.gitbook/assets/image (223).png" alt=""><figcaption></figcaption></figure>

**Botón para Activar/Desactivar Personalizaciones del Modo Quiosco** – permite al administrador activar o desactivar las personalizaciones visuales y funcionales del modo quiosco en dispositivos Android. Esta opción ayuda a evitar fallas en la activación del modo quiosco en dispositivos con limitaciones.\
Al activar el modo quiosco, se mostrará un botón llamado **“Personalizaciones”**, que estará activado por defecto. Si el administrador decide desactivarlo, el sistema ocultará y dejará de aplicar las configuraciones en el dispositivo.

* **Botones de navegación:** Permite definir los botones de navegación del dispositivo como "Activo", "Bloqueado" o "Solo el botón Inicio".
* **Botão "Power":** permite definir el botón de encendido del dispositivo como "Disponible" o "Bloqueado.
* **Exhibir mensajes de error:** permite definir la exhibición de mensajes de error como "Activo" o "Silenciado".
* **Informaciones mostradas en la barra de estado:** permite definir la información que se mostrará en la barra de estado del dispositivo. Puede ser definido como "Notificaciones e información del sistema", "Solo información del sistema" o "Ninguna".
* **Acceso a configuraciones:** permite definir como "Liberado" o "Bloqueado".

{% hint style="info" %}
**OBSERVACIÓN**\
Durante la activación de un dispositivo en una política con Modo Kiosco Activo, la configuración "Acceso a Configuraciones" necesita estar como "Liberada" para que el usuario pueda conceder los permisos solicitados para la activación del Companion. Esto es porque el usuario necesita acceder directamente a la interfaz de configuraciones del dispositivo. Por este motivo, en el modo kiosco ninguna aplicación podrá activar permisos que requieran acceso a la interfaz de configuración del SO si las configuraciones están bloqueadas en la política. Después del enrolamiento, la opción "Acceso a Configuraciones" podrá ser bloqueada si es necesario.\
Otra opción, para no tener que dejar el acceso a las configuraciones liberado, es dejar los permisos del Companion como opcionales, así el usuario puede activar sin que sea necesario conceder los permisos; sin embargo, en este caso, los datos relacionados con los permisos no concedidos no serán recopilados.
{% endhint %}

* **Servicios de telefonía adicionales:** permite definir los servicios de telefonía como "Activo" o "Definido por dispositivo". Al definir como "Activo" y guardar la política, el sistema enviará los paquetes de servicios de telefonía al dispositivo, lo que permitirá recibir y realizar llamadas en el dispositivo que provisiona la política. Al definir como "Definido por  Dispositivo", el dispositivo funcionará según su configuración estándar, teniendo o no los servicios.

<figure><img src="../../../../.gitbook/assets/image (130).png" alt=""><figcaption></figcaption></figure>

* **Fondo de pantalla** - Es posible cargar una imagen para el fondo de pantalla en la política y establecer la orientación de la pantalla, la cual se enviará a la aplicación.
* **Color de fuente de los iconos** - Permite configurar el color del texto de los iconos en la pantalla de inicio.
* **Orientación de pantalla** - Permite seleccionar la orientación de pantalla para el dispositivo, y el valor predeterminado es 'Definido por el usuario'."
* **Tamaño de iconos y fuentes** - Permite seleccionar las siguientes opciones de tamaño de pantalla: Estándar del sistema (predeterminado), Pequeño (75%) y Grande (125%).
* **Ordenación de los iconos** - Permite realizar la ordenación de los iconos por orden alfabético o por fecha de inclusión.
* **Posicionamiento de la imagen** - Permite seleccionar la posición de la imagen del fondo de pantalla en la pantalla de inicio del dispositivo.
* **Bloquear acceso a las configuraciones de Wi-Fi** - impide que los usuarios accedan y modifiquen las configuraciones de Wi-Fi durante la inicialización y el uso del dispositivo en el modo Kiosco.

<figure><img src="../../../../.gitbook/assets/image (131).png" alt=""><figcaption></figcaption></figure>

* **Acceso Temporal al Dispositivo** - Configuración para permitir que el usuario acceda al dispositivo durante un tiempo determinado. Para activar el permiso, deslice el interruptor hacia la derecha desde la pantalla principal. Además, es posible definir la duración del acceso del usuario al dispositivo, que puede ser de 5, 10, 15, 30 minutos ó 1 hora. Al habilitar el acceso temporal, se generará una contraseña para que el usuario pueda acceder al dispositivo. En la sección "Opciones de Gestión de Dispositivos" detallaremos mejor cómo funcionará.

A continuación, listamos los accesos que el usuario tendrá en el dispositivo al ingresar la contraseña de acceso temporal:&#x20;

* Liberará acceso a todas las aplicaciones instaladas que estén en la política, incluso si no están visibles en el Modo Kiosco (Google Play y Remotos);
* Liberará acceso a todas las aplicaciones de sistema que existen en la política (independientemente de si están visibles);
* Liberará acceso a todas las configuraciones del dispositivo, pero para esto, es necesario que la aplicación de sistema "Configuraciones" esté incluida en la política y que el permiso Acceso a Configuraciones esté como Liberado en el Modo Kiosco.

Después de finalizar el tiempo definido, el Modo Kiosco se activará nuevamente de forma automática.

<figure><img src="../../../../.gitbook/assets/image (132).png" alt=""><figcaption></figcaption></figure>

## **Modo Quiosco ChromeOS**

El Modo Quiosco en ChromeOS fue desarrollado para configurar dispositivos Chromebook en un entorno controlado, ideal para escenarios como la aplicación de exámenes, garantizando que los estudiantes utilicen el dispositivo solo para actividades autorizadas.

Pasos para la configuración:

1. Seleccione el menú "Información de la Empresa".
2. En la sección "Google Workspace", ingrese el ID del Cliente en Workspace.
3. Acceda a la pantalla de Gestión de Políticas y haga clic en "Crear nueva política".
4. Haga clic en la pestaña ChromeOS, seleccione el modo de gestión ChromeOS y registre la política.

Para acceder a las configuraciones de la política:

1. En la pantalla "Editar política", vaya a la pestaña "Modo Quiosco".
2. Haga clic en la flecha "˅" para acceder a las opciones de configuración disponibles.
3. Complete el formulario para la activación de eventos:

* Unidades Organizacionales: seleccione las unidades que contienen los dispositivos.
* Unidad Organizacional de Destino: seleccione dónde se aplicará el Modo Quiosco.

<figure><img src="../../../../.gitbook/assets/image (220).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
**Nota**

* Las unidades deben configurarse previamente en Google Workspace.
* No está permitido seleccionar la misma unidad como origen y destino.
* Según Google, los cambios pueden tardar hasta 24 horas en hacerse efectivos.
* Algunas opciones, como **Copiar Política** y **Token de Registro**, estarán deshabilitadas para políticas ChromeOS.
{% endhint %}

4. Después de completar las unidades, haga clic en **Guardar**.
5. El sistema habilitará los botones **"Iniciar"** y **"Concluir"** el evento:
   * **Iniciar:** Al hacer clic en "Iniciar", las unidades de dispositivos se moverán a la unidad de destino.
   * **Concluir:** Al hacer clic en "Concluir", las unidades de dispositivos regresarán a la unidad original antes de la transferencia.
