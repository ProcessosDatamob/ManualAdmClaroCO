# Ajustes y Correcciones de la Versión - V 12.0.0

<mark style="color:red;">En esta versión, se realizaron las siguientes correcciones:</mark>

* <mark style="color:red;">**Remover Bloqueo de SIM (Block SIM):**</mark> <mark style="color:red;"></mark><mark style="color:red;">Al enviar el comando de "Remover Bloqueo de SIM" desde el menú de Dispositivos en el portal, se estaba eliminando el bloqueo de pantalla de manera indebida.</mark>
* <mark style="color:red;">**Remover Bloqueo de Pantalla (Block SIM):**</mark> <mark style="color:red;"></mark><mark style="color:red;">Cuando se enviaba el comando de "Remover Bloqueo de Pantalla" al dispositivo desde el menú de Dispositivos en el portal, el dispositivo seguía solicitando la contraseña. Incluso al intentar ingresar la contraseña anterior u otra contraseña, el acceso no se liberaba.</mark>
* <mark style="color:red;">**Configuraciones - Gestionar Políticas - Editar Política:**</mark> <mark style="color:red;"></mark><mark style="color:red;">En la pestaña Aplicaciones, el contador en el pie de página de la lista de aplicaciones de la política era incorrecto, ya que no reflejaba la cantidad real de aplicaciones incluidas en la política, mostrando un número inferior a la cantidad real.</mark>
* <mark style="color:red;">**Configuraciones - Gestionar Redes Wi-Fi:**</mark> <mark style="color:red;"></mark><mark style="color:red;">El campo Contraseña del SSID era obligatorio, por lo que al seleccionar una red WPA-EAP, que no requiere este tipo de contraseña, sin llenar el campo, el sistema no permitía guardar la red.</mark>
