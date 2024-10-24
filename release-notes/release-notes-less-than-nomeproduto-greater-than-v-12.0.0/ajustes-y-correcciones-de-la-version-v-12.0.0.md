# Ajustes y Correcciones de la Versión - V 12.0.0

En esta versión, se realizaron las siguientes correcciones:

* **Remover Bloqueo de SIM (Block SIM):** Al enviar el comando de "Remover Bloqueo de SIM" desde el menú de Dispositivos en el portal, se estaba eliminando el bloqueo de pantalla de manera indebida.
* **Remover Bloqueo de Pantalla (Block SIM):** Cuando se enviaba el comando de "Remover Bloqueo de Pantalla" al dispositivo desde el menú de Dispositivos en el portal, el dispositivo seguía solicitando la contraseña. Incluso al intentar ingresar la contraseña anterior u otra contraseña, el acceso no se liberaba.
* **Configuraciones - Gestionar Políticas - Editar Política:** En la pestaña Aplicaciones, el contador en el pie de página de la lista de aplicaciones de la política era incorrecto, ya que no reflejaba la cantidad real de aplicaciones incluidas en la política, mostrando un número inferior a la cantidad real.
* **Configuraciones - Gestionar Redes Wi-Fi:** El campo Contraseña del SSID era obligatorio, por lo que al seleccionar una red WPA-EAP, que no requiere este tipo de contraseña, sin llenar el campo, el sistema no permitía guardar la red.
