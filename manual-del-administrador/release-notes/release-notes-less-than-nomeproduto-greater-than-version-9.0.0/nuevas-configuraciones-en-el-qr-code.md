# Nuevas Configuraciones en el QR Code

En la pantalla de "Token de Registro" de una política se han añadido nuevos campos para facilitar el enrolamiento del dispositivo, los cuales son:

**Gestionar Redes Wi-Fi:** es posible seleccionar una de las redes Wi-Fi configuradas en la pantalla "Gestionar Redes Wi-Fi". Al seleccionar una red, el sistema incluirá todas las configuraciones posibles en el QRCode, abarcando los siguientes tipos de seguridad: WPA/WPA 2, WEP y sin seguridad. Al realizar el enrolamiento con el QRCode, el dispositivo se conectará automáticamente a la red configurada, simplificando el proceso de configuración inicial del dispositivo.

**Omitir Cifrado:** al activar esta opción, el sistema incluirá la siguiente información en el QRCode: "android.app.extra.PROVISIONING\_SKIP\_ENCRYPTION": (true/false - valor predeterminado “false"). Al realizar el enrolamiento con el QRCode, el dispositivo ignorará el cifrado del dispositivo durante el proceso de configuración inicial.

**Usar Datos Móviles:** al activar esta opción, el sistema incluirá la siguiente información en el QRCode: "android.app.extra.PROVISIONING\_USE\_MOBILE\_DATA": (true/false - valor predeterminado “false"). Al realizar el enrolamiento con el QRCode, el dispositivo utilizará los datos móviles durante el proceso de configuración inicial.

[Volver a la lista de Release Notes](./)
