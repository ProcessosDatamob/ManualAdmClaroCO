# Ajustes y Correcciones de la Versión - V 13.0.0

En esta versión, se realizaron las siguientes correcciones:

1. **Configuraciones - Gestionar Políticas - Editar Política - Pantalla:**\
   Tras la formateo y activación de dispositivos en el portal, se detectó un problema en el que los dispositivos no aplicaban automáticamente el fondo de pantalla predeterminado en la política, incluso cuando la opción "Deshabilitar cambio de fondo de pantalla" estaba desactivada. Para resolver este problema, se implementó un control en la configuración de "Pantalla" que vuelve a aplicar automáticamente el fondo de pantalla al modificar la política, eliminando la necesidad de cargar el fondo de pantalla nuevamente y garantizando que las configuraciones se apliquen correctamente.
2. **Remover Bloqueo de Pantalla (Block SIM):**\
   Al desbloquear la pantalla, especialmente después de que el dispositivo se hubiera apagado, aparecía repetidamente el mensaje: "¿Fijar para usar solo esta aplicación?" Incluso al seleccionar la opción de fijar, el mensaje seguía mostrándose. Para solucionar este problema, se ajustó el comportamiento del Block SIM para que el mensaje no se muestre repetidamente tras la activación de la aplicación, permitiendo que el usuario utilice el dispositivo normalmente después de desbloquearlo.
3. **Mob Settings:**\
   Había un error al instalar la aplicación Mob Settings en Modo Quiosco, donde al intentar habilitar el Bluetooth, la aplicación se cerraba automáticamente, impidiendo el acceso a las configuraciones de Bluetooth y el uso de esta función en el dispositivo. Para resolver el problema, se ajustó el comportamiento de la aplicación para garantizar que las configuraciones de Bluetooth puedan ser accesibles y modificadas correctamente, incluso con el Modo Quiosco activo.

[Volver a la lista de Release Notes](./)
