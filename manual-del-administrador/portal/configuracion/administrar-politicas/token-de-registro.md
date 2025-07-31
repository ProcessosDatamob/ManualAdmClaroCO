# Token de Registro

Como se ve en la sección anterior, puede acceder al token de registro de dispositivos desde el menú "**Configuraciones**" en la opción "**Administrar Políticas**". La pantalla del token de registro se muestra a continuación.

<figure><img src="../../../../.gitbook/assets/Captura de tela 2024-05-16 161844 (1).png" alt=""><figcaption></figcaption></figure>

Los elementos disponibles en esta pantalla se describen a continuación:

1. El Token de Registro de la política puede ser copiado para enviarlo.
2. La configuración Zero Touch de la política puede ser copiada para ser insertada en el panel Zero Touch.
3. El sistema presentará un campo para la selección de la 'Red Wi-Fi'. En esta pantalla, será posible elegir una de las redes Wi-Fi previamente configuradas en la sección '**Administrar Redes Wi-Fi**'. Al seleccionar, se incluirán en el QR Code todas las configuraciones posibles con los siguientes tipos de seguridad:

* WPA/WPA 2
* WEP
* Ninguna

Al realizar el registro utilizando el QR Code, el dispositivo se conectará automáticamente a la red configurada.

4. La opción “**Habilitar aplicaciones del sistema**" permite habilitar todos las aplicaciones de sistema nativas del dispositivo. Cuando esta opción está activada, el sistema actualizará la imagen del QRCode incluyendo la información para habilitar las aplicaciones de sistema.
5. Al activar el campo "**Saltar criptografia**", se incluirá la siguiente información en el QR Code: "android.app.extra.PROVISIONING\_SKIP\_ENCRYPTION". El sistema también actualizará la imagen del QR Code con la nueva configuración y actualizará la configuración de Zero Touch. Después de realizar el enrolamiento con el QR Code, el dispositivo ignorará el cifrado del sistema.
6. Al activar la opción "**Usar datos móviles**" del sistema operativo (SO), se incluirá la siguiente información en el QR Code: “android.app.extra.PROVISIONING\_USE\_MOBILE\_DATA". El sistema actualizará la imagen del QR Code con la nueva configuración. Después de realizar el enrolamiento con el QR Code, el dispositivo utilizará los datos móviles durante el proceso de configuración.
7. Al concluir las configuraciones, el sistema permitirá guardar o cancelar el guardado de las configuraciones, almacenándolas al finalizar el proceso de guardado.
8. El QR Code de la política puede ser leído en la pantalla para el proceso de registro de dispositivos o puede ser copiado y enviado a los usuarios de los dispositivos; basta con hacer clic con el botón derecho del ratón para que aparezcan las opciones.
