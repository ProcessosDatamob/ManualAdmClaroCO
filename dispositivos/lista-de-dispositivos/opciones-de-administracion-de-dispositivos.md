# Opciones de administración de dispositivos

En la pantalla de "Dispositivos" dentro de "Lista de Dispositivos" se puede acceder a la información del dispositivo haciendo clic en el botón de información.

<figure><img src="../../.gitbook/assets/image (141).png" alt=""><figcaption></figcaption></figure>

### Detalles&#x20;

* Usuario - nombre del usuario registrado en el portal
* Identificación - Identificación registrada para el dispositivo.&#x20;
* Grupo - grupo registrado para el dispositivo;
*   Departamento - es un campo de texto libre, es decir, el administrador puede escribir lo que desee. Indica la unidad o departamento de la organización al que está asignado el dispositivo.

    Teléfono del Usuario - es un campo de texto libre, es decir, el administrador puede escribir lo que desee. Indica el número de teléfono asociado al usuario del dispositivo.
* IMEI - número interno y único en cada dispositivo.&#x20;
* ICCID - número de chip SIM.&#x20;
* Número de serie - número de serie del dispositivo;
* Teléfono - número de teléfono.
* Modelo - modelo de dispositivo.&#x20;
* Fabricante - nombre del fabricante del dispositivo.
* Sistema Operativo - sistema operativo del dispositivo.&#x20;
* Versión de Android - versión de Android del dispositivo.&#x20;
* Contraseña de Acesso Temporal - esta contraseña temporal es generada al activar la Configuración "Acceso Temporal al Dispositivo" en el Modo Kiosco. La contraseña debe ser proporcionada al usuario del dispositivo y se actualizará en el portal cada 5 minutos, con opción de copiar y mostrar el tiempo restante hasta que la contraseña expire. Por lo tanto, si se ha definido un tiempo de 10 minutos para que los usuarios accedan al dispositivo, si exceden esos 10 minutos, no podrán usar la misma contraseña, ya que habrá sido actualizada. En el dispositivo, con la contraseña en mano, el usuario deberá acceder a las Configuraciones Iniciales, hacer clic en la opción Acceso Temporal y escribir la contraseña en el campo "Código".

### Instalación&#x20;

* Estado Aplicado - si el dispositivo está completamente registrado, el estado será "Activo";
* Fecha de registro - fecha de registro de los dispositivos.
* Modo de gestión - muestra el modo de gestión utilizado.
* Versión de la aplicación - versión de la aplicación **\<NomeProduto>** instalado en el dispositivo.
* Nombre de la Política en el Dispositivo: nombre de la política asignada en el dispositivo;&#x20;
* Versión de la Política Aplicada: versión de la política;&#x20;
* Fecha de Sincronización de la Política: mostrará la fecha de sincronización de la política;&#x20;
* En Conformidad: es la adherencia del dispositivo a todas las configuraciones de políticas asignadas a él. Si alguna configuración no se ha aplicado, el valor de esta opción será "No";&#x20;
* Fecha de la Última Comunicación: mostrará la fecha en que el dispositivo se comunicó por última vez con el portal.

### Hardware&#x20;

* Almacenamiento Interno - cuánto de almacenamiento interno tiene.
* Batería - Cuántos % de batería está actualmente.

Haciendo clic en los tres puntos "..." a la derecha en la lista de dispositivos, aparecen las opciones de consulta y configuraciones del dispositivo, como se ilustra en la imagen a continuación.

### **Permisos**

* **Acceso a los Datos de Uso:** estado sí o no, si el usuario no activa este permiso, la aplicación no capturará los datos de consumo y tiempo de uso de las aplicaciones.&#x20;
* **Ignorar Optimización de Batería:** estado sí o no, si el usuario no activa este permiso, la aplicación podrá verse afectada por las configuraciones de optimización de batería, dejará de capturar las ubicaciones de los dispositivos y dejará de enviar la información al portal.&#x20;
* **Cambio de Configuraciones del Sistema:** estado sí o no, si el usuario no activa este permiso, la aplicación Kiosk Launcher Manager no permitirá que el usuario altere algunas configuraciones del sistema cuando esté en el modo Kiosco.&#x20;
* **Lectura de SMS:** estado sí o no, si el usuario no activa este permiso, la aplicación no capturará la información de los SMS enviados.

<figure><img src="../../.gitbook/assets/Captura de tela 2023-11-03 143049.png" alt=""><figcaption></figcaption></figure>

Las opciones disponibles se muestran en la tabla siguiente y se detallan a continuación.

<table><thead><tr><th width="233">Modo de Gestión</th><th>Opciones disponibles</th></tr></thead><tbody><tr><td>Android</td><td><p>Historial de la Batería </p><p>Historial de Almacenamiento</p><p>Reporte de no Conformidad </p><p>Alterar Politica </p><p>Habilitar/ Deshabilitar el dispositivo</p><p>Apagar Pantalla </p><p>Reiniciar Dispositivo </p><p>Generar nueva contraseña de dispositivo </p><p>Remover dispositivo (WIPE)</p><p>Administrar Información</p></td></tr></tbody></table>



### **Historial de la Batería**

Para ver el historial de batería del dispositivo, haga clic en "Historial de batería".

El sistema mostrará la pantalla del historial de batería del dispositivo.

1. Seleccione una fecha para ver los datos del historial.
2. Desplazar el cursor sobre el gráfico para ver los valores en un momento específico.

<figure><img src="../../.gitbook/assets/image (36).png" alt=""><figcaption></figcaption></figure>

### **Historial de Almacenamiento**

Para ver el historial de memoria libre en el almacenamiento interno del dispositivo, haga clic en "Historial de almacenamiento".

![](<../../.gitbook/assets/6 (12).png>)

El sistema mostrará la pantalla del "Historial de almacenamiento" con el historial de memoria libre del dispositivo. Seleccione una fecha, para visualizar los datos del histórico.

Desplace el cursor sobre el gráfico para ver los valores en una hora específica.

### **Reporte de no conformidad**

Para ver las inconsistencias en la configuración asignada al dispositivo, utilice la opción "reporte de no conformidad".

<figure><img src="../../.gitbook/assets/image (142).png" alt=""><figcaption></figcaption></figure>

### **Alterar Política**

Al elegir Alterar política, aparecerá en el centro de la pantalla un cuadro de diálogo para elegir la política que se asignará al dispositivo. Elija la política entre las políticas enumeradas y haga clic en actualizar para cambiar la política del dispositivo.

La política define las preferencias, incluidos los criterios de hardware, software, sistema operativo, seguridad, etc. Para obtener más información sobre Políticas, lea la sección de configuración de este manual.

<figure><img src="../../.gitbook/assets/image (60).png" alt=""><figcaption></figcaption></figure>

### **Deshabilitar Dispositivo**

Cuando se envía el comando 'Desactivar Dispositivos', se desactivan (o quedan bloqueadas) todas las aplicaciones que no son de Google, se permiten llamadas telefónicas y el estado del dispositivo cambian a "desactivado". Para desactivar un dispositivo, utilice la opción "Deshabilitar Dispositivo" en el menú de opciones del dispositivo. Esta opción solo está disponible para dispositivos que tienen el estado "Activo".

Para confirmar la operación, en la pantalla de confirmación haga clic en el botón "Deshabilitar".

<figure><img src="../../.gitbook/assets/image (61).png" alt=""><figcaption></figcaption></figure>

### **Activar dispositivo**

Esta opción solo aparece para dispositivos que están en el estado "Deshabilitado". Para activar un dispositivo deshabilitado, haga clic en "Activar dispositivo" en las opciones de administración del dispositivo.

Confirme la actualización haciendo clic en "Activar dispositivo" en el cuadro de diálogo.

### **Desconectar la pantalla del dispositivo**

La opción "Apagar pantalla" envía un comando para apagar la pantalla del dispositivo. Al hacer clic en la opción "Apagar pantalla" el comando se ejecuta directamente y un mensaje aparecerá en la pantalla para informar que el comando ha sido enviado al dispositivo.

### **Reiniciar el dispositivo**

Esta operación envía una orden para reiniciar el dispositivo. Seleccione la opción "Reiniciar dispositivo". Se muestra un mensaje en la pantalla del portal para confirmar el envío de la orden. El mensaje mostrado se muestra a continuación.

<figure><img src="../../.gitbook/assets/image (62).png" alt=""><figcaption></figcaption></figure>

### **Generar nueva contraseña del dispositivo**

El sistema permite generar una nueva contraseña para el dispositivo. Para realizar esta operación, elija la opción "Generar nueva contraseña del dispositivo".

Rellene los campos "Nueva contraseña" y "Confirmar nueva contraseña" con valores iguales para que el botón "Confirmar" esté habilitado. Al clicar en confirmar, la contraseña cambiará automáticamente. Opcionalmente, y según la necesidad, podrán ser marcadas las opciones:

* No permitir que otros administradores cambien la contraseña de nuevo hasta que el usuario la ingrese en el dispositivo;
* No pedir credenciales de usuario al iniciar el dispositivo;
* Bloquear el dispositivo después de restablecer la contraseña.

La pantalla para generar nueva contraseña del dispositivo se muestra a continuación.

<figure><img src="../../.gitbook/assets/image (63).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
**OBSERVACIÓN**\
Al seleccionar la opción "No pedir credenciales de usuario en la inicialización del dispositivo", la contraseña no será solicitada durante el proceso de inicialización. La contraseña será necesaria solo para desbloquear la pantalla del dispositivo.\
**Inicialización Segura (Secure Boot):** la contraseña solicitada en la inicialización es una medida de seguridad implementada por el Secure Boot. Esta funcionalidad protege el proceso de inicialización contra ataques de seguridad provenientes de códigos malintencionados, como malware y ransomware.
{% endhint %}

### **Remover dispositivo (WIPE)**

Esta operación le permite eliminar un dispositivo. Limpia los datos y configuraciones del dispositivo. Los dispositivos eliminados no aparecen en la lista de dispositivos de la empresa. La opción "Eliminar dispositivo" aparece en la lista de opciones del dispositivo en la pantalla de lista de dispositivos (menú "Dispositivos", opción "Listar dispositivos").

Como se puede ver en la siguiente imagen, se muestra un mensaje en la pantalla para información y advertencia. La operación no se puede deshacer, por lo tanto, confirme solo cuando esté seguro de que desea eliminar el dispositivo.

<figure><img src="../../.gitbook/assets/image (64).png" alt=""><figcaption></figcaption></figure>

### **Administrar**

Esta opción permite acceder a la pantalla para editar datos del dispositivo, como: Usuario, identificación y Grupo.

<figure><img src="../../.gitbook/assets/image (143).png" alt=""><figcaption></figcaption></figure>

Además de poder editar los datos, se muestran más abajo en la pantalla dos listas con la información de Software y Hardware relacionados con el dispositivo administrado:

<figure><img src="../../.gitbook/assets/image (144).png" alt=""><figcaption></figcaption></figure>

### **Información de Software**

* Modo de gestión - muestra el modo de gestión utilizado.
* Versión de la aplicación - versión de la aplicación **\<NomeProduto>** instalado en el dispositivo.
* Fecha de la última actualización - fecha y hora en que la información del dispositivo se sincronizó con el portal. Esta fecha proviene de AMAPI (API de Google), es decir, es la información recopilada por la API de Google en el dispositivo.
* Nombre de la Política en el Portal - nombre de la política asignada al dispositivo.

### Información sobre el hardware&#x20;

* Almacenamiento Interno - cuánto de almacenamiento interno tiene.
* Batería - Cuántos % de batería está actualmente.
