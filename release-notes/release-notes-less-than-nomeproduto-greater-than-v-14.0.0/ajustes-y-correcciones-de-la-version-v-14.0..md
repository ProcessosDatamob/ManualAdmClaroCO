# Ajustes y Correcciones de la Versión - V 14.0.

**En esta versión, se realizaron las siguientes correcciones:**

* **Configuración de Aplicaciones - Opción "Mostrar en Quiosco":**\
  Se ajustó el comportamiento de la opción "Mostrar en Quiosco". Cuando un dispositivo estaba registrado en una política con el Modo Quiosco activo y se instalaba manualmente una aplicación con tipo de instalación Forzada, se observó que la opción "Mostrar en Quiosco" no se actualizaba correctamente. La aplicación no se mostraba al activar la opción "Mostrar en Quiosco" y solo aparecía cuando la opción se desactivaba. Para resolver este problema, se ajustó este comportamiento para garantizar que la aplicación se muestre en el dispositivo según la configuración deseada.
* **Comportamiento Incorrecto al Eliminar Empresa:**\
  Al acceder al portal y eliminar una empresa desde el menú Empresa → Información de la Empresa, el sistema enviaba correctamente el comando WIPE a los dispositivos registrados, pero no notificaba al usuario sobre la acción realizada. Además, al volver a ingresar al portal, el sistema recuperaba indebidamente la información de la empresa, contradiciendo la solicitud de eliminación. Para solucionar este problema, se implementó un ajuste que muestra una notificación de confirmación al usuario y, al confirmarla, lo redirige fuera del portal, evitando la recuperación de los datos de la empresa eliminada.
* **Eliminación de Red Wi-Fi Configurada en Código QR:**\
  En el portal, al crear una política y dentro de la opción del token, asociarla con una red Wi-Fi previamente registrada, la eliminación de esta red resultaba en la eliminación del Código QR de la política. Para resolver este problema, se ajustó la configuración para garantizar que tanto el Código QR como el token de registro permanezcan accesibles, incluso si estaban previamente vinculados a una red Wi-Fi eliminada.
* **Configuraciones Gestionadas de Aplicaciones No Guardadas:**\
  En el menú Configuración > Gestionar Políticas, al activar opciones en aplicaciones específicas, se identificó que las configuraciones gestionadas no se guardaban correctamente. Para solucionar este problema, se ajustó el sistema para garantizar que las opciones activadas permanezcan activas después de actualizar la política, asegurando que el comportamiento deseado se refleje en el dispositivo.
