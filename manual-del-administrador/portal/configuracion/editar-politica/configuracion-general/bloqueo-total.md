# Bloqueos

Esta funcionalidad permite al usuario administrador configurar un bloqueo por velocidad, bloqueo total del dispositivo fuera de un período de tiempo específico, al alcanzar el límite de datos móviles o bloquear el dispositivo cuando se encuentra fuera de una ubicación configurada. De esta forma, se permite bloquear el dispositivo cuando el usuario no está en su horario laboral y cuando se alcanza el límite de datos móviles definido para el ciclo actual.\
Estando en la pestaña "Configuraciones" de la pantalla "Editar Políticas", haz clic en "Bloqueos" para ver las opciones de configuración.

### **Bloqueo de Aplicaciones por Velocidad**

Esta funcionalidad permite bloquear el uso de determinadas aplicaciones según la velocidad a la que se esté desplazando el dispositivo. El objetivo es aumentar la seguridad, impidiendo el uso de aplicaciones mientras el dispositivo está en movimiento (por ejemplo, durante la conducción de un vehículo).

**Cómo Configurar en el Portal**

1. Accede a la edición de una política Android o Android - Block SIM.
2. Ve a la pestaña "Configuraciones" y abre la opción "Bloqueos".
3. Activa la opción **"Activar bloqueo por velocidad"**.

{% hint style="info" %}
**IMPORTANTE**\
Para que funcione correctamente, la política debe tener la configuración de ubicación activada.\
El uso continuo de la ubicación puede aumentar el consumo de batería, por lo que se recomienda mantener el dispositivo conectado al cargador.
{% endhint %}

**Define los siguientes parámetros:**

* **Velocidad de inicio del bloqueo:** valor a partir del cual se activará el bloqueo (por defecto: 20 km/h).
* **Unidad de Medida:** km/h, mph (millas por hora) o m/s.
* **Tiempo de espera:** intervalo, en minutos (de 1 a 10), para verificar si la velocidad se mantiene antes de aplicar o quitar el bloqueo.

Guarda la política para enviar las configuraciones al dispositivo.

**Selección de las Aplicaciones que Serán Bloqueadas**

1. Accede a la pestaña **"Aplicaciones"** de la política.
2. Se mostrará la columna **"Bloqueo por Velocidad"** en la lista de aplicaciones.
3. Activa el bloqueo individualmente para las aplicaciones deseadas.

{% hint style="info" %}
**Observación:** No es posible activar el bloqueo para las aplicaciones: \<NombreProducto>, Kiosk Launcher y Block SIM.
{% endhint %}

**Cómo Funciona en el Dispositivo**

* Cuando la velocidad alcanza o supera el límite configurado:
  * El sistema inicia el conteo del tiempo de espera.
  * Si la velocidad continúa por encima después de ese tiempo:
    * La aplicación bloqueada será **ocultada**.
    * El usuario no podrá utilizarla de ninguna forma.
* Cuando la velocidad cae por debajo del límite:
  * El sistema inicia nuevamente el tiempo de espera.
  * Si la velocidad se mantiene por debajo después de ese tiempo:
    * La aplicación será **visible nuevamente**.
    * El uso será permitido según la política.

### Bloqueo Fuera del Horario Laboral

&#x20;Para realizar el bloqueo de dispositivos fuera del horario de trabajo, siga los siguientes pasos:<mark style="color:red;">:</mark>

1. Ative la opción "Bloquear dispositivo fuera del horario de laboral".
2. Complete el campo "Días laborales" con los días laborables de la semana, especificando el día de inicio y el día de finalización.<mark style="color:red;">.</mark>
3. Complete el campo "Horario de trabajo" con la hora de inicio y la hora de finalización del horario laboral.

{% hint style="info" %}
**OBSERVACIÓN**

Al dejar los campos en blanco, el sistema considerará el período del día entero, ó 24 horas.
{% endhint %}

Cuando el dispositivo esté fuera del horario de trabajo configurado, el ocultará todas las aplicaciones del dispositivo, excepto "Teléfono", "" y "Play Store".

Las aplicaciones instaladas en el dispositivo solo se ocultarán y se mostrará una notificación fija en el dispositivo con el siguiente mensaje: "Acceso a las aplicaciones bloqueado por el administrador".

De este modo, cuando el dispositivo esté fuera del horario de trabajo configurado, no se podrá acceder a las aplicaciones ocultas; sin embargo, se podrá acceder a las configuraciones del dispositivo, y será posible apagar o reiniciar el dispositivo.

Cuando el dispositivo esté dentro del horario de trabajo configurado, todas las aplicaciones volverán a mostrarse sin necesidad de reinstalarlas.

### **Bloqueo por Límite de Datos**

&#x20;Para activar el bloqueo del dispositivo por límite de uso de datos móviles, habilite la opción "Bloquear dispositivo por límite de uso de datos móviles".

Cuando el dispositivo alcance el límite de uso de datos móviles configurado para el ciclo actual, el ocultará todas las aplicaciones del dispositivo, excepto "Teléfono", "Aplicación de Gestión" y "Play Store".

El dispositivo mostrará una notificación fija con el mensaje: "Acceso a las aplicaciones bloqueado por el administrador". Esta notificación informará al usuario sobre el bloqueo.

De este modo, cuando el dispositivo esté bloqueado por el límite de uso de datos, las aplicaciones ocultas no podrán ser accedidas, pero seguirán instaladas. El usuario aún podrá acceder a las configuraciones del dispositivo, y será posible apagar o reiniciar el dispositivo.

Además, al instalar una aplicación a través de Play Store o de forma remota, la aplicación será ocultada.

Si el uso de datos móviles está por debajo del límite o si el administrador desactiva la configuración "Bloquear dispositivo por límite de uso de datos móviles" en la política, el mostrarán correctamente todas las aplicaciones del dispositivo según la política provisionada.

Si el dispositivo se encuentra en cualquiera de las condiciones que requieren la activación de un Bloqueo Total (fuera del horario de trabajo o alcanzando el límite de datos móviles), la configuración y activación de un Bloqueo Total no anulará ni interferirá con la configuración y activación del otro. Ambos bloqueos pueden coexistir y aplicarse según sus respectivas condiciones.

### **Bloquear dispositivo fuera de la ubicación**

Para activar el bloqueo total del dispositivo al salir de una ubicación específica, habilite la opción **"Bloquear dispositivo fuera de la ubicación"** en la política configurada.

Cuando el dispositivo esté fuera del radio de la ubicación definida, el sistema ocultará todas las aplicaciones, widgets y accesos directos, excepto los siguientes: Teléfono, y Play Store.

El dispositivo mostrará una notificación fija con el mensaje: **"Acceso a las aplicaciones bloqueado por el administrador"**, informando al usuario sobre el bloqueo. Aunque esté bloqueado, será posible acceder a las configuraciones del dispositivo, apagarlo o reiniciarlo. Las aplicaciones permanecerán instaladas, pero inaccesibles.

**Desbloqueo Automático:**\
El dispositivo se desbloqueará automáticamente cuando:

* Regrese al radio de la ubicación configurada.
* Se desactive la configuración **"Bloquear dispositivo fuera de la ubicación"** en la política.
* Ya no haya una ubicación configurada para el dispositivo.

Al desbloquearse, todas las aplicaciones y funcionalidades serán restaurados según las políticas provisionadas.

**Requisitos Previos:**\
Para que esta funcionalidad funcione correctamente, es necesario que los servicios de ubicación estén activados en el dispositivo, incluyendo:

* Precisión de Ubicación
* Alta Precisión
