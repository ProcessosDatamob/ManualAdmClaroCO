# Modo Quiosco

Esta configuración tiene como objetivo permitir la creación de un entorno en el que el usuario del dispositivo solo pueda acceder a las aplicaciones previamente autorizadas por el administrador, es decir, solo se mostrarán los íconos de las aplicaciones seleccionadas en la pantalla del dispositivo.

Para acceder a la configuración del "**Modo Quiosco**", siga estos pasos:&#x20;

1. En la pantalla "[Editar política](./)", seleccione la pestaña "**Modo Quiosco**".&#x20;
2. Active el modo quiosco haciendo clic en el botón de activación.

<figure><img src="../../.gitbook/assets/Captura de tela 2024-01-11 135757.png" alt=""><figcaption></figcaption></figure>

3. En la pantalla se mostrará un mensaje de confirmación. Confirme haciendo clic en el botón "Activar".

<figure><img src="../../.gitbook/assets/image (28).png" alt=""><figcaption></figcaption></figure>

4. Al activar el Modo Quiosco en la política y aprovisionar un dispositivo con esta política, la aplicación Kiosk Launcher Manager se instalará automáticamente en el dispositivo.

Cuando el dispositivo instale la aplicación Kiosk, la aplicación capturará la lista de todos los aplicativos instalados en el dispositivo y la enviará al Portal de administración.  Además, enviará las  configuraciones administradas al portal y cambiará el lanzador del dispositivo por el de la aplicación Kiosk. No permitirá que el usuario cambie el lanzador en el dispositivo y mantendrá la configuración del Modo Quiosco recibida en la política.



### Opciones de configuración del Modo Quiosco

Cuando el modo quiosco esté activado, estarán disponibles las siguientes opciones de configuración:

<figure><img src="../../.gitbook/assets/image (53).png" alt=""><figcaption></figcaption></figure>

* **Botones de navegación:** Permite definir los botones de navegación del dispositivo como "Activo", "Bloqueado" o "Solo el botón Inicio".
* **Botão "Power":** permite definir el botón de encendido del dispositivo como "Disponible" o "Bloqueado.
* **Exhibir mensajes de error:** permite definir la exhibición de mensajes de error como "Activo" o "Silenciado".
* **Informaciones mostradas en la barra de estado:** permite definir la información que se mostrará en la barra de estado del dispositivo. Puede ser definido como "Notificaciones e información del sistema", "Solo información del sistema" o "Ninguna".
* **Acceso a configuraciones:** permite definir como "Liberado" o "Bloqueado".
* **Servicios de telefonía adicionales:** permite definir los servicios de telefonía como "Activo" o "Definido por dispositivo". Al definir como "Activo" y guardar la política, el sistema enviará los paquetes de servicios de telefonía al dispositivo, lo que permitirá recibir y realizar llamadas en el dispositivo que provisiona la política. Al definir como "Definido por  Dispositivo", el dispositivo funcionará según su configuración estándar, teniendo o no los servicios.
* **Fondo de pantalla** - Es posible cargar una imagen para el fondo de pantalla en la política y establecer la orientación de la pantalla, la cual se enviará a la aplicación.
* **Color de fuente de los iconos** - Permite configurar el color del texto de los iconos en la pantalla de inicio.
* **Orientación de pantalla** - Permite seleccionar la orientación de pantalla para el dispositivo, y el valor predeterminado es 'Definido por el usuario'."
* **Tamaño de iconos y fuentes** - Permite seleccionar las siguientes opciones de tamaño de pantalla: Estándar del sistema (predeterminado), Pequeño (75%) y Grande (125%).
* **Ordenación de los iconos** - Permite realizar la ordenación de los iconos por orden alfabético o por fecha de inclusión.
* **Posicionamiento de la imagen** - Permite seleccionar la posición de la imagen del fondo de pantalla en la pantalla de inicio del dispositivo.

Las aplicaciones que se mostrarán en el dispositivo se establecerán mediante la política, es decir, solo las aplicaciones autorizadas en la política se mostrarán en el quiosco.
