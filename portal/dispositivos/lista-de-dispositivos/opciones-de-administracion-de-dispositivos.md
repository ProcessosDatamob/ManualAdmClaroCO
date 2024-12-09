# Información del Dispositivo

En la pantalla de "Dispositivos" dentro de "Lista de Dispositivos" se puede acceder a la información del dispositivo haciendo clic en el botón de información.

<figure><img src="../../../.gitbook/assets/image (182).png" alt=""><figcaption></figcaption></figure>

Después de hacer clic en el ícono mencionado, se mostrará la siguiente pantalla, donde tendremos acceso a la Información del dispositivo:

<figure><img src="../../../.gitbook/assets/image (183).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
La fecha que aparece en **Última Actualización** en la esquina superior derecha de la pantalla de Información del dispositivo, es la fecha de actualización del dispositivo en Google, es decir, se refiere a la comunicación de AMAPI con el portal. Los datos que se actualizan son:

* Detalles
* Instalación
* Informe de No conformidad
{% endhint %}

<figure><img src="../../../.gitbook/assets/image (184).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../../.gitbook/assets/image (185).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../../.gitbook/assets/image (217).png" alt=""><figcaption></figcaption></figure>

A continuación, detallaremos la información contenida en cada uno de los campos de las imágenes anteriores:

### Detalles&#x20;

* **Usuario -** nombre del usuario registrado en el portal
* **Identificación -** Identificación registrada para el dispositivo.&#x20;
* **Grupo -** grupo registrado para el dispositivo;
*   **Departamento -** es un campo de texto libre, es decir, el administrador puede escribir lo que desee. Indica la unidad o departamento de la organización al que está asignado el dispositivo.

    Teléfono del Usuario - es un campo de texto libre, es decir, el administrador puede escribir lo que desee. Indica el número de teléfono asociado al usuario del dispositivo.
* **IMEI -** número interno y único en cada dispositivo.&#x20;
* **ICCID -** número de chip SIM.&#x20;
* **Licencia -** número de la Licencia.
* **Teléfono -** número de teléfono.
* **Modelo -** modelo de dispositivo.&#x20;
* **Fabricante -** nombre del fabricante del dispositivo.
* **Sistema Operativo -** sistema operativo del dispositivo.&#x20;
* **Versión de Android -** versión de Android del dispositivo.&#x20;
* **Contraseña de Acesso Temporal -** esta contraseña temporal es generada al activar la Configuración "Acceso Temporal al Dispositivo" en el Modo Kiosco. La contraseña debe ser proporcionada al usuario del dispositivo y se actualizará en el portal cada 5 minutos, con opción de copiar y mostrar el tiempo restante hasta que la contraseña expire. Por lo tanto, si se ha definido un tiempo de 10 minutos para que los usuarios accedan al dispositivo, si exceden esos 10 minutos, no podrán usar la misma contraseña, ya que habrá sido actualizada. En el dispositivo, con la contraseña en mano, el usuario deberá acceder a las Configuraciones Iniciales, hacer clic en la opción Acceso Temporal y escribir la contraseña en el campo "Código".

### Instalación&#x20;

* **Estado Aplicado -** si el dispositivo está completamente registrado, el estado será "Activo";
* **Fecha de registro -** fecha de registro de los dispositivos.
* **Modo de gestión -** muestra el modo de gestión utilizado.
* **Versión de la aplicación -** versión de la aplicación **\<NomeProduto>** instalado en el dispositivo.
* **Nombre de la Política en el Dispositivo -** nombre de la política asignada en el dispositivo;&#x20;
* **Versión de la Política Aplicada -** versión de la política;&#x20;
* **Fecha de Sincronización de la Política -** mostrará la fecha de sincronización de la política;&#x20;
* **En Conformidad -** es la adherencia del dispositivo a todas las configuraciones de políticas asignadas a él. Si alguna configuración no se ha aplicado, el valor de esta opción será "No";&#x20;
*   **Fecha de la Última Comunicación -** mostrará la fecha en que el dispositivo se comunicó por última vez con el portal.\
    Los datos que se actualizan en el portal cuando la **Fecha de Última Comunicación** se actualiza son:

    **Pantalla de Información del Dispositivo:** Los datos que se actualizan en el portal serán exactamente los que estén en el dispositivo en el momento de la última comunicación.

    * **Hardware:** Batería y almacenamiento
    * **Permisos:** Todos
    * **Conectividad:** Todos los datos listados en Conectividad

### Hardware&#x20;

* **Memoria Total:** cantidad total de memoria RAM disponible en el dispositivo.
* **Memoria Disponible:** cantidad de memoria RAM actualmente libre y disponible para uso en el dispositivo.
* **Almacenamiento Interno Total:** cantidad total de almacenamiento interno que posee el dispositivo.
* **Almacenamiento Interno Disponible:** cantidad de almacenamiento interno actualmente libre y disponible para uso en el dispositivo.
* **Almacenamiento Total en la Tarjeta SD:** cantidad total de almacenamiento disponible en la tarjeta SD insertada en el dispositivo.
* **Almacenamiento Disponible en la Tarjeta SD:** cantidad de almacenamiento actualmente libre y disponible en la tarjeta SD insertada en el dispositivo.
* **Procesador:** información sobre el procesador del dispositivo, incluyendo el modelo y la velocidad.
* **Salud de la Batería:** estado general de la batería del dispositivo, indicando su capacidad y condición.
* **Ciclo de Carga de la Batería:** número de ciclos completos de carga y descarga que ha experimentado la batería del dispositivo.

### **Permisos**

* **Acceso a los Datos de Uso:** estado sí o no, si el usuario no activa este permiso, la aplicación no capturará los datos de consumo y tiempo de uso de las aplicaciones.&#x20;
* **Ignorar Optimización de Batería:** estado sí o no, si el usuario no activa este permiso, la aplicación podrá verse afectada por las configuraciones de optimización de batería, dejará de capturar las ubicaciones de los dispositivos y dejará de enviar la información al portal.&#x20;
* **Cambio de Configuraciones del Sistema:** estado sí o no, si el usuario no activa este permiso, la aplicación Kiosk Launcher Manager no permitirá que el usuario altere algunas configuraciones del sistema cuando esté en el modo Kiosco.&#x20;
* **Lectura de SMS:** estado sí o no, si el usuario no activa este permiso, la aplicación no capturará la información de los SMS enviados.
* **Programar Alarmas**:  Los estados pueden ser "sí" o "no". Si el usuario no activa este permiso, la aplicación no ejecutará las siguientes funciones: notificación de mensajes y documentos recibidos, instalación remota de aplicaciones, registro de geolocalización del dispositivo, eliminación del bloqueo de SIM.
* **Instalación de Apps de Fuentes Desconocidas**: Este permiso es opcional y puede activarse durante la configuración inicial. Si el usuario decide no activarlo, la aplicación no podrá realizar la instalación de aplicaciones de forma remota.
* **Superposición de Pantalla**:  Este permiso también es opcional durante la activación. Si no se activa, la aplicación no podrá mostrar mensajes de confirmación al realizar la instalación de aplicaciones de forma remota.

### Conectividad

* **Tipo de red conectada (Wi-Fi/Móvil)** - indica si el dispositivo está conectado vía Wi-Fi o red móvil.
* **Ancho de Banda (Móvil)** - el ancho de banda disponible para la red móvil.
* **Ancho de Banda (Wi-Fi)** - el ancho de banda disponible para la red Wi-Fi.
* **Latencia** - el tiempo que tarda un paquete de datos en viajar desde su origen hasta su destino y regresar.
* **Configuración de Banda** - configuración específica de la banda de frecuencia utilizada.
* **Red Wi-Fi conectada** - nombre de la red Wi-Fi a la que el dispositivo está conectado.
* **Fuerza de señal** - la intensidad de la señal de la red conectada.
* **WiFi Roaming** - la capacidad del dispositivo de conectarse automáticamente a diferentes puntos de acceso Wi-Fi dentro de la misma red sin perder la conexión.
* **Frecuencia de la banda WiFi** - frecuencia utilizada por la red Wi-Fi (por ejemplo, 2.4 GHz ó 5 GHz).
* **Velocidad del link Wi-Fi** - velocidad de conexión con la red Wi-Fi.
* **Dirección MAC Wi-Fi** - dirección MAC del adaptador Wi-Fi del dispositivo.
* **IP (Red Wi-Fi)** - dirección IP asignada al dispositivo en la red Wi-Fi, con protocolo IPv4.
* **IPv6 (Red Wi-Fi)** - dirección IP asignada al dispositivo en la red Wi-Fi, con protocolo IPv6.
* **Red BSSID** - identificador único de la red Wi-Fi, endereço MAC do ponto de acesso.
* **Operadora de la Red Conectada** - nombre de la operadora de la red móvil conectada.
* **Roaming de Datos Móviles** - indica si el dispositivo está en roaming de datos móviles.
* **IP (Red móvil)** - dirección IP asignada al dispositivo en la red móvil, con protocolo IPv4.
* **IPv6 (Red móvil)** - dirección IP asignada al dispositivo en la red móvil, con protocolo IPv6.
* **DBM (RSRP - Potencia de la Antena)** - medida de la potencia de la señal con la antena conectada.
* **Cell ID** - identificación de la celda a la que el dispositivo está conectado.
* **LAC** - _Location Area Cod&#x65;**,**_ código de área de localización de la red conectada.
* **Tecnología de la Antena** - tipo de tecnología de antena utilizada

### SIM

* **SIM Conectada** - indica cuál tarjeta SIM está activa y conectada.
* **Operadora SIM 1** - nombre de la operadora de la primera tarjeta SIM.
* **Número de Teléfono SIM 1** - número de teléfono asociado a la primera tarjeta SIM.
* **ICCID SIM 1** - identificador exclusivo de la tarjeta SIM 1.
* **IMEI SIM 1** - IMEI de la entrada de la tarjeta SIM 1 del dispositivo. IMEI es el número de identificación internacional de equipo móvil, acrónimo en inglés para _International Mobile Equipment Identity_.
* **Número de abonado SIM 1** - número del suscriptor asociado al SIM 1. MSIN?
* **MCC do SIM 1** - código del país de la tarjeta SIM 1.
* **MNC do SIM 1** - código de la red móvil de la tarjeta SIM 1.
* **Operador SIM 2** - nombre de la operadora de la tarjeta SIM 2.
* **Número de Teléfono SIM 2** - número de teléfono asociado a la tarjeta SIM 2.
* **ICCID SIM 2** - identificador exclusivo de la tarjeta SIM 2.
* **IMEI SIM 2** - IMEI de la entrada de la tarjeta SIM 2 del dispositivo. IMEI es el número de identificación internacional de equipo móvil, acrónimo en inglés para _International Mobile Equipment Identity_.
* **Número de abonado SIM 2** - número del suscriptor asociado al SIM 2. MSIN?
* **MCC do SIM 2** - código del país de la tarjeta SIM 2.
* **MNC do SIM 2** - código de la red móvil de la tarjeta SIM 2.
* **Operadora del eSIM** - nombre de la operadora asociada al eSIM.
* **Número de teléfono del eSIM** - número de teléfono asociado al eSIM.
* **ICCID del eSIM** - identificador único del eSIM.
* **ID de suscripción del eSIM** - identificador de la suscripción asociada al eSIM.

### **Ubicación**

* **Nombre:** Identifica el nombre asociado a la ubicación, como el nombre de la empresa o del punto de interés.
* **Dirección:** Indica la dirección completa de la ubicación, incluyendo calle, número, ciudad, estado/provincia y código postal.
* **Latitud:** Coordenada geográfica que representa la posición norte-sur de la ubicación en el mapa.
* **Longitud:** Coordenada geográfica que representa la posición este-oeste de la ubicación en el mapa.
* <mark style="color:red;">**Radio:**</mark> <mark style="color:red;"></mark><mark style="color:red;">Distancia en metros alrededor de la ubicación, utilizada para definir un área de cobertura o interés.</mark>
* <mark style="color:red;">**Código:**</mark> <mark style="color:red;"></mark><mark style="color:red;">Código único o identificador asignado a la ubicación para fines de organización o referencia.</mark>
* **Región:** Región geográfica o administrativa donde se encuentra la ubicación.
* <mark style="color:red;">**CNPJ:**</mark> <mark style="color:red;"></mark><mark style="color:red;">Registro Nacional de Persona Jurídica asociado a la ubicación, generalmente utilizado para empresas.</mark>
* <mark style="color:red;">**Responsable:**</mark> <mark style="color:red;"></mark><mark style="color:red;">Nombre de la persona responsable de la ubicación, como el gerente o propietario.</mark>
* <mark style="color:red;">**Teléfono:**</mark> <mark style="color:red;"></mark><mark style="color:red;">Número de teléfono de contacto de la ubicación o del responsable.</mark>
* <mark style="color:red;">**Correo Electrónico:**</mark> <mark style="color:red;"></mark><mark style="color:red;">Dirección electrónica para contactar con la ubicación o el responsable.</mark>
* <mark style="color:red;">**Distancia a la Ubicación:**</mark> <mark style="color:red;"></mark><mark style="color:red;">Medida de la distancia entre la ubicación actual u otra referencia y la ubicación especificada.</mark>
