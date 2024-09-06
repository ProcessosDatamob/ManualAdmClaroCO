# Opciones de administración de dispositivos

## **Comandos y Acciones del Dispositivo**

Clicando nos tres puntos "..." a la derecha en la lista de dispositivos, aparecen las opciones de consulta y configuración del dispositivo, como se ilustra en la imagen a continuación:

<figure><img src="../../../.gitbook/assets/image (186).png" alt=""><figcaption></figcaption></figure>

Las opciones disponibles se muestran en la tabla siguiente y se detallan a continuación.

<table><thead><tr><th width="233">Modo de Gestión</th><th>Opciones disponibles</th></tr></thead><tbody><tr><td>Android</td><td><p>Alterar Politica </p><p>Habilitar/ Deshabilitar el Dispositivo</p><p>Apagar Pantalla </p><p>Reiniciar Dispositivo </p><p>Generar nueva contraseña de dispositivo </p><p>Remover dispositivo (WIPE)</p><p>Administrar</p></td></tr><tr><td>Android Block SIM</td><td><p></p><p>Alterar Politica </p><p>Activar/Desahbilitar el Dispositivo</p><p>Apagar Pantalla</p><p>Reiniciar Dispositivo</p><p>Generar Nueva Contraseña del Bloqueo de Pantalla</p><p>Quitar Bloqueo de Pantalla</p><p>Quitar  Bloqueo de Chip</p><p>Remover Dispositivo (WIPE)</p><p>Administrar</p></td></tr><tr><td>Android Work Profile</td><td><p></p><p>Alterar Politica </p><p>Remover Dispositivo (WIPE)</p><p>Administrar</p></td></tr></tbody></table>

### **Alterar Política**

Al elegir Alterar política, aparecerá en el centro de la pantalla un cuadro de diálogo para elegir la política que se asignará al dispositivo. Elija la política entre las políticas enumeradas y haga clic en actualizar para cambiar la política del dispositivo.

La política define las preferencias, incluidos los criterios de hardware, software, sistema operativo, seguridad, etc. Para obtener más información sobre Políticas, lea la sección de configuración de este manual.

<figure><img src="../../../.gitbook/assets/image (60).png" alt=""><figcaption></figcaption></figure>

### **Deshabilitar Dispositivo**

Cuando se envía el comando 'Desactivar Dispositivos', se desactivan (o quedan bloqueadas) todas las aplicaciones que no son de Google, se permiten llamadas telefónicas y el estado del dispositivo cambian a "desactivado". Para desactivar un dispositivo, utilice la opción "Deshabilitar Dispositivo" en el menú de opciones del dispositivo. Esta opción solo está disponible para dispositivos que tienen el estado "Activo".

Para confirmar la operación, en la pantalla de confirmación haga clic en el botón "Deshabilitar".

<figure><img src="../../../.gitbook/assets/image (61).png" alt=""><figcaption></figcaption></figure>

### **Activar dispositivo**

Esta opción solo aparece para dispositivos que están en el estado "Deshabilitado". Para activar un dispositivo deshabilitado, haga clic en "Activar dispositivo" en las opciones de administración del dispositivo.

Confirme la actualización haciendo clic en "Activar dispositivo" en el cuadro de diálogo.

### **Desconectar la pantalla del dispositivo**

La opción "Apagar pantalla" envía un comando para apagar la pantalla del dispositivo. Al hacer clic en la opción "Apagar pantalla" el comando se ejecuta directamente y un mensaje aparecerá en la pantalla para informar que el comando ha sido enviado al dispositivo.

### **Reiniciar el dispositivo**

Esta operación envía una orden para reiniciar el dispositivo. Seleccione la opción "Reiniciar dispositivo". Se muestra un mensaje en la pantalla del portal para confirmar el envío de la orden. El mensaje mostrado se muestra a continuación.

<figure><img src="../../../.gitbook/assets/image (62).png" alt=""><figcaption></figcaption></figure>

### <mark style="color:red;">**Generar nueva contraseña del Bloqueo de Pantalla**</mark>

<mark style="color:red;">Esta opción permite al administrador configurar la contraseña del bloqueo de pantalla del Block SIM para permitir el cambio remoto de la contraseña. En la Lista de Dispositivos, haga clic en la opción "Generar Nueva Contraseña del Bloqueo de Pantalla", complete y confirme la nueva contraseña del Bloqueo de Pantalla, utilizando letras, números y símbolos. Confirme el cambio de la contraseña, y al confirmar, el comando será enviado vía push a la Aplicación de Gestión para su aplicación en el dispositivo.</mark>

### <mark style="color:red;">**Remover Bloqueo de Pantalla**</mark>

<mark style="color:red;">Esta operación envía un comando para eliminar el bloqueo de pantalla del dispositivo. Elija la opción "Remover Bloqueo de Pantalla". Se mostrará un mensaje en la pantalla del portal para confirmar el envío del comando.</mark>

{% hint style="info" %}
<mark style="color:red;">**OBSERVACIÓN**</mark>\ <mark style="color:red;">Esta opción solo estará disponible para dispositivos activados con la política en modo de gestión Android Block SIM.</mark>
{% endhint %}

### **Generar nueva contraseña del dispositivo**

El sistema permite generar una nueva contraseña para el dispositivo. Para realizar esta operación, elija la opción "Generar nueva contraseña del dispositivo".

Rellene los campos "Nueva contraseña" y "Confirmar nueva contraseña" con valores iguales para que el botón "Confirmar" esté habilitado. Al clicar en confirmar, la contraseña cambiará automáticamente. Opcionalmente, y según la necesidad, podrán ser marcadas las opciones:

* No permitir que otros administradores cambien la contraseña de nuevo hasta que el usuario la ingrese en el dispositivo;
* No pedir credenciales de usuario al iniciar el dispositivo;
* Bloquear el dispositivo después de restablecer la contraseña.

La pantalla para generar nueva contraseña del dispositivo se muestra a continuación.

<figure><img src="../../../.gitbook/assets/image (63).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
**OBSERVACIÓN**\
Al seleccionar la opción "No pedir credenciales de usuario en la inicialización del dispositivo", la contraseña no será solicitada durante el proceso de inicialización. La contraseña será necesaria solo para desbloquear la pantalla del dispositivo.\
**Inicialización Segura (Secure Boot):** la contraseña solicitada en la inicialización es una medida de seguridad implementada por el Secure Boot. Esta funcionalidad protege el proceso de inicialización contra ataques de seguridad provenientes de códigos malintencionados, como malware y ransomware.
{% endhint %}

### <mark style="color:red;">**Remover Bloqueo de SIM**</mark>

<mark style="color:red;">Esta opción permite al administrador enviar un comando para eliminar el bloqueo de SIM de un dispositivo, permitiendo el acceso del usuario al dispositivo.</mark>

<mark style="color:red;">En la pantalla "Lista de Dispositivos", seleccione la política "Android - Block SIM" y la opción "Remover Bloqueo de SIM". El sistema mostrará un mensaje de confirmación para enviar la eliminación del bloqueo de SIM, permitiendo confirmar o cancelar. Después de enviar el comando de eliminación, el dispositivo recibirá un push con el comando, capturará el comando y lo enviará al Block SIM. El usuario del dispositivo debe hacer clic en el push o abrir la aplicación Block SIM para ejecutar la eliminación del bloqueo.</mark>

### <mark style="color:red;">**Reinicio de Bloqueo de SIM**</mark>

<mark style="color:red;">La funcionalidad de "Reinicio de Bloqueo de SIM" permite que, después de la eliminación del bloqueo del SIM en un dispositivo, el administrador pueda volver a bloquear el SIM.</mark>

<mark style="color:red;">Esto posibilita que, tras la eliminación del bloqueo, el administrador pueda cambiar el SIM del dispositivo y aplicar un nuevo bloqueo, garantizando la flexibilidad de gestión y la seguridad de los dispositivos gestionados.</mark>

{% hint style="info" %}
<mark style="color:red;">**OBSERVACIÓN**</mark>\ <mark style="color:red;">Después de la eliminación del bloqueo, es posible reiniciar un bloqueo sin reiniciar el dispositivo, sin la necesidad de formatearlo.</mark>
{% endhint %}

### **Remover dispositivo (WIPE)**

Esta operación le permite eliminar un dispositivo. Limpia los datos y configuraciones del dispositivo. Los dispositivos eliminados no aparecen en la lista de dispositivos de la empresa. La opción "Eliminar dispositivo" aparece en la lista de opciones del dispositivo en la pantalla de lista de dispositivos (menú "Dispositivos", opción "Listar dispositivos").

Como se puede ver en la siguiente imagen, se muestra un mensaje en la pantalla para información y advertencia. La operación no se puede deshacer, por lo tanto, confirme solo cuando esté seguro de que desea eliminar el dispositivo.

<figure><img src="../../../.gitbook/assets/image (64).png" alt=""><figcaption></figcaption></figure>

### <mark style="color:red;">**Remover Dispositivo con SIM Bloqueado**</mark>

<mark style="color:red;">Al enviar el comando de eliminación de un dispositivo que está activado en una política Android Block SIM y con el SIM bloqueado, el usuario administrador será alertado para que pueda enviar un comando para eliminar el bloqueo del SIM antes de remover el dispositivo del portal.</mark>

<figure><img src="../../../.gitbook/assets/image (187).png" alt=""><figcaption></figcaption></figure>

<mark style="color:red;">Se mostrará el siguiente mensaje: "Este dispositivo puede tener el SIM bloqueado."</mark>

<mark style="color:red;">¿Desea enviar un comando para eliminar el "Bloqueo del SIM"?</mark>

<mark style="color:red;">Al hacer clic en la opción</mark> <mark style="color:red;"></mark><mark style="color:red;">**SÍ**</mark><mark style="color:red;">, se enviará el comando para eliminar el bloqueo del SIM, y se mostrará el mensaje: "¡Comando enviado con éxito! Espere para intentar eliminar el dispositivo nuevamente."</mark>

<mark style="color:red;">El sistema esperará la confirmación antes de permitir la eliminación del dispositivo.</mark>

{% hint style="info" %}
<mark style="color:red;">El usuario del dispositivo debe hacer clic en la notificación push o abrir la aplicación Block SIM para ejecutar la eliminación del bloqueo.</mark>
{% endhint %}

<mark style="color:red;">Si el administrador decide no enviar el comando, se mostrará el siguiente mensaje: "¡Al eliminar este dispositivo, el uso de los datos móviles del SIM del usuario podría quedar bloqueado!"</mark>

<mark style="color:red;">¿Está seguro de que desea eliminar este dispositivo? Esta acción no se puede deshacer.</mark>

<mark style="color:red;">Después de optar por enviar el comando de desbloqueo del SIM, y una vez que el portal haya recibido la confirmación de la eliminación del bloqueo del SIM en el dispositivo, el sistema mostrará el siguiente mensaje:</mark>

<mark style="color:red;">¿Está seguro de que desea eliminar este dispositivo? Esta acción no se puede deshacer.</mark>

<mark style="color:red;">Y se mostrarán las opciones "Eliminar" y "Cancelar."</mark>

<mark style="color:red;">De esta manera, esta funcionalidad ayuda a evitar problemas de bloqueo de SIM que puedan surgir al eliminar dispositivos de la gestión.</mark>

### **Administrar**

Al hacer clic en la opción **Gestionar**, se mostrará la pantalla **Gestionar Dispositivo**.

<figure><img src="../../../.gitbook/assets/image (188).png" alt=""><figcaption></figcaption></figure>

<mark style="color:red;">En esta pantalla se agrupan los</mark> <mark style="color:red;"></mark><mark style="color:red;">**Comandos y Acciones del Dispositivo**</mark> <mark style="color:red;"></mark><mark style="color:red;">que ya hemos detallado anteriormente, de acuerdo con el Modo de Gestión o el Sistema Operativo. El comportamiento de cada funcionalidad será el mismo que en la pantalla "Lista de Dispositivos".</mark>

<mark style="color:red;">Se mostrarán las opciones de</mark> <mark style="color:red;"></mark><mark style="color:red;">**Volver**</mark> <mark style="color:red;"></mark><mark style="color:red;">y</mark> <mark style="color:red;"></mark><mark style="color:red;">**Actualizar**</mark><mark style="color:red;">, y al hacer clic en</mark> <mark style="color:red;"></mark><mark style="color:red;">**Actualizar**</mark><mark style="color:red;">, se actualizará la información y se mostrará la fecha de actualización al pasar el ratón sobre el botón de actualizar.</mark>

<mark style="color:red;">3 - Las pestañas con opciones para edición e información del dispositivo. Las pestañas son:</mark>

* <mark style="color:red;">**Información**</mark>
* <mark style="color:red;">**Aplicaciones**</mark>
* <mark style="color:red;">**Batería**</mark>
* <mark style="color:red;">**Almacenamiento Libre**</mark>
* <mark style="color:red;">**Geolocalización**</mark>
* <mark style="color:red;">**No Conformidades**</mark>

<mark style="color:red;">A continuación, se explica cada una de ellas:</mark>

#### <mark style="color:red;">**Información**</mark>

<mark style="color:red;">Al abrir la pantalla de</mark> <mark style="color:red;"></mark><mark style="color:red;">**Gestionar Dispositivo**</mark><mark style="color:red;">, la primera pestaña,</mark> <mark style="color:red;"></mark><mark style="color:red;">**Información**</mark><mark style="color:red;">, estará preseleccionada. En esta pestaña, es posible editar los siguientes datos del dispositivo: Usuario, Identificación, Grupo, Departamento y Teléfono del Usuario.</mark>

<mark style="color:red;">Además de poder editar los datos, se muestran a continuación listas con</mark> <mark style="color:red;"></mark><mark style="color:red;">**Detalles**</mark><mark style="color:red;">,</mark> <mark style="color:red;"></mark><mark style="color:red;">**Instalación**</mark><mark style="color:red;">,</mark> <mark style="color:red;"></mark><mark style="color:red;">**Hardware**</mark><mark style="color:red;">,</mark> <mark style="color:red;"></mark><mark style="color:red;">**Permisos**</mark><mark style="color:red;">,</mark> <mark style="color:red;"></mark><mark style="color:red;">**Conectividad**</mark> <mark style="color:red;"></mark><mark style="color:red;">y</mark> <mark style="color:red;"></mark><mark style="color:red;">**SIM**</mark><mark style="color:red;">, relacionadas con el dispositivo gestionado.</mark>

<mark style="color:red;">Las secciones están detalladas en la página de Información del Dispositivo: "Detalles", "Instalación", "Hardware", "Permisos", "Conectividad" y "SIM".</mark>

{% hint style="info" %}
<mark style="color:red;">**OBSERVACIÓN**</mark>\ <mark style="color:red;">Es posible acceder rápidamente a la pantalla de edición de una política en el dispositivo haciendo clic en el nombre de la política, que funciona como un enlace.</mark>


{% endhint %}

#### <mark style="color:red;">**Aplicaciones**</mark>

<mark style="color:red;">En la pestaña</mark> <mark style="color:red;"></mark><mark style="color:red;">**Aplicaciones**</mark><mark style="color:red;">, se puede acceder a la lista de todas las aplicaciones instaladas en el dispositivo, que contienen la siguiente información: ícono, nombre, consumo de datos móviles, consumo de datos en Wi-Fi y tiempo de uso. Los datos de consumo y tiempo de uso se registran dentro del ciclo. Es posible buscar una aplicación específica utilizando el campo de búsqueda, exportar informes completos o de la página, además de copiar la información de la lista. Al hacer clic en los tres puntos, es posible visualizar el gráfico del</mark> <mark style="color:red;"></mark><mark style="color:red;">**Historial de Consumo**</mark> <mark style="color:red;"></mark><mark style="color:red;">de la aplicación durante el ciclo.</mark>

#### <mark style="color:red;">**Batería**</mark>

<mark style="color:red;">En la pestaña</mark> <mark style="color:red;"></mark><mark style="color:red;">**Batería**</mark><mark style="color:red;">, es posible seleccionar una fecha para visualizar la información deseada. Al elegir la fecha, el sistema buscará y mostrará los datos de la batería en formato de gráfico.</mark>

#### <mark style="color:red;">**Almacenamiento Libre**</mark>

<mark style="color:red;">En la pestaña</mark> <mark style="color:red;"></mark><mark style="color:red;">**Almacenamiento Libre**</mark><mark style="color:red;">, es posible visualizar la memoria libre en el almacenamiento interno del dispositivo al seleccionar una fecha para visualizar la información deseada. Al elegir la fecha, el sistema buscará y mostrará los datos de almacenamiento en formato de gráfico.</mark>

#### <mark style="color:red;">**Geolocalización**</mark>

<mark style="color:red;">En la pestaña</mark> <mark style="color:red;"></mark><mark style="color:red;">**Geolocalización**</mark><mark style="color:red;">, es posible filtrar las ubicaciones utilizando los filtros: Localizar, Fecha, Zona horaria y Precisión. Al hacer clic en</mark> <mark style="color:red;"></mark><mark style="color:red;">**Buscar**</mark><mark style="color:red;">, se mostrará un mapa que muestra las geolocalizaciones registradas, si las hay.</mark>

<mark style="color:red;">Para visualizar las ubicaciones geográficas de un dispositivo, siga los siguientes pasos:</mark>

* <mark style="color:red;">Seleccione la opción</mark> <mark style="color:red;"></mark><mark style="color:red;">**Localizar: Por Fecha o Ahora**</mark><mark style="color:red;">.</mark>\ <mark style="color:red;">Si elige "Localizar por Fecha", siga los pasos:</mark>

1. <mark style="color:red;">Seleccione la fecha en la que se registraron las ubicaciones.</mark>
2. <mark style="color:red;">Especifique la zona horaria deseada.</mark>
3. <mark style="color:red;">Defina el límite de precisión de las ubicaciones.</mark>
4. <mark style="color:red;">Haga clic en</mark> <mark style="color:red;"></mark><mark style="color:red;">**Buscar**</mark> <mark style="color:red;"></mark><mark style="color:red;">para mostrar las ubicaciones en el mapa, según el filtro especificado.</mark>

<mark style="color:red;">El sistema mostrará las ubicaciones con marcadores que forman el recorrido realizado por el usuario del dispositivo. Los marcadores tienen diferentes colores, que indican el tipo de ubicación. Use la leyenda para identificar:</mark>

* <mark style="color:red;">**Posición inicial de la lectura del GPS**</mark> <mark style="color:red;"></mark><mark style="color:red;">– primera ubicación del dispositivo registrada en el día.</mark>
* <mark style="color:red;">**Posición actual o última posición registrada**</mark> <mark style="color:red;"></mark><mark style="color:red;">– última ubicación del dispositivo registrada en el día.</mark>
* <mark style="color:red;">**Lugar por donde pasó el usuario**</mark> <mark style="color:red;"></mark><mark style="color:red;">– ubicaciones registradas en el día entre la primera y la última.</mark>

<mark style="color:red;">Haga clic en el marcador para visualizar la información de la ubicación. Use las funciones del mapa para optimizar la visualización.</mark>

#### <mark style="color:red;">**No Conformidades**</mark>

<mark style="color:red;">En esta pestaña se enumerarán todas las no conformidades del dispositivo con información detallada sobre la Configuración, Motivo de la No Conformidad y Detalles de la No Conformidad.</mark>

{% hint style="info" %}
<mark style="color:red;">**OBSERVACIÓN**</mark>\ <mark style="color:red;">La pestaña</mark> <mark style="color:red;"></mark><mark style="color:red;">**No Conformidades**</mark> <mark style="color:red;"></mark><mark style="color:red;">estará deshabilitada si el dispositivo no tiene ninguna inconformidad.</mark>
{% endhint %}

<mark style="color:red;">Para cada elemento de no conformidad enumerado, se mostrarán: Nombre del Paquete, Ruta del Campo, Valor Actual, Motivo del Error en la Instalación, Contexto de Wi-Fi y Contexto de la Contraseña de la Política.</mark>

<mark style="color:red;">Es posible</mark> <mark style="color:red;"></mark><mark style="color:red;">**Exportar**</mark> <mark style="color:red;"></mark><mark style="color:red;">y</mark> <mark style="color:red;"></mark><mark style="color:red;">**Copiar**</mark><mark style="color:red;">, lo que permite exportar la información del informe a un archivo Excel o copiar la información al portapapeles.</mark>
