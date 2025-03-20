# Aplicaciones

La pestaña de configuración de aplicaciones le permite administrar configuraciones, permisos, establecer el modo de instalación, así como, incluir y eliminar aplicaciones.

La pantalla "**Editar política**" situada en la pestaña "**Aplicaciones**" se muestra a continuación.

<figure><img src="../../../../../.gitbook/assets/Captura de tela 2024-03-14 153400.png" alt=""><figcaption></figcaption></figure>

La pantalla tiene las siguientes partes, según la numeración en la figura:

1. **Modo de selección de aplicaciones en Play Store -** permite controlar cómo se mostrarán las aplicaciones en los dispositivos registrados en esta política. En el modo "Restricta", los usuarios solo pueden ver e instalar desde Google Play Store las aplicaciones elegidas por el administrador. Las otras aplicaciones se eliminarán y no estarán disponibles en los dispositivos.

El modo “Abierta” permite la instalación de aplicaciones que no están en la Google Play Administrada, o sea el usuario podrá consultar e instalar cualquier aplicación disponible en la tienda Play Store.&#x20;

{% hint style="info" %}
**NOTA**

Al seleccionar la opción “Abierta”, las aplicaciones agregadas a la política mostrarán el tipo de instalación: **Instalación Forzada**, al entender que todas las aplicaciones ya están disponibles.
{% endhint %}

2. Utilice el cuadro de búsqueda para buscar aplicaciones dentro de la lista que aparece.
3. Lista de aplicaciones incluidas en la política.
4. **Tipos de instalación** - elija el tipo de instalación para cada aplicación. Los tipos de instalación son:

* **Disponible:** La aplicación está disponible para su instalación; el usuario tiene la opción de instalarla según su conveniencia. No se instala automáticamente en el dispositivo.
* **Preinstalado:** La aplicación se instala automáticamente en el dispositivo. Cuando el usuario utilice el dispositivo, las herramientas o configuraciones necesarias ya estarán instaladas. Permite que el usuario desinstale la aplicación.
* **Instalación Forzada:** La aplicación se instala automáticamente en el dispositivo sin la intervención del usuario. El usuario no puede desinstalar la aplicación; si lo hace, el sistema la volverá a instalar, garantizando que las herramientas necesarias estén siempre presentes y activas.
* **Bloqueado:** La instalación de ciertas aplicaciones está explícitamente impedida. El usuario no podrá instalar ni acceder a estas aplicaciones o configuraciones restringidas en el dispositivo.

{% hint style="info" %}
**NOTA**

Si el usuario elige la opción “Pre instalada” deberá considerar que las aplicaciones se instalaran en ese momento ignorando si el dispositivo está en WIFI o si está usando la red de datos lo que podría traducirse en un alto consumo de datos. Es necesario asegurarse que el dispositivo esté conectado a WIFI si se utilizarán aplicaciones “Pre instaladas”.



Es importante destacar que el tipo de instalación "Preinstalado" de una aplicación, ocurre solo una vez en el dispositivo. Es decir: cuando una aplicación es preinstalada es eliminada por el usuario, al cambiar la política que tiene la misma aplicación con el tipo de instalación "preinstalado" la aplicación no se mostrará en el dispositivo ya que fue removida anteriormente.

Para que la aplicación se presente en el dispositivo con el tipo de instalación "preinstalado" es necesario realizar el comando "Remover Dispositivo (WIPE)" en el portal o factory reset a través del dispositivo".
{% endhint %}

5. Otras acciones "...":  permite acceder a las opciones de acciones disponibles para la aplicación: "[Configuraciones Administradas](./#configuraciones-administradas)", "[Permisos](./#permisos)", "[Configuraciones Avanzadas](./#configuraciones-avanzadas)" y "[Eliminar Aplicación](./#eliminar-aplicacion)".
6. **Agregar Aplicaciones:** Permite añadir aplicaciones para su gestión. Para obtener más información, acceda al contenido "[Agregar Aplicaciones](./#agregar-aplicaciones)" en esta página.
7. **Restricciones de Funcionamiento:** Permite crear restricciones de acceso a las aplicaciones por horario, para definir los momentos en los que las aplicaciones no podrán ser accedidas. Para más información, acceda al contenido "[Restricciones de Funcionamiento](./#restricciones-de-funcionamiento)" en esta página.

## **Configuraciones Administradas**

Para acceder a la configuración administrada de una aplicación, debe estar en la pantalla "**Editar política**" con la pestaña "**Aplicaciones**" seleccionada. Siga los siguientes pasos:

1. Localice la aplicación deseada y haga clic en los tres puntos al final de la línea para mostrar el menú con más opciones;
2. Haga clic en "**Configuraciones Administradas**".

<figure><img src="../../../../../.gitbook/assets/Captura de tela 2023-11-06 174309.png" alt=""><figcaption></figcaption></figure>

La pantalla siguiente será mostrada:

<figure><img src="../../../../../.gitbook/assets/Captura de tela 2024-05-16 145644.png" alt=""><figcaption></figcaption></figure>

En esta pantalla es posible ver la identificación de la aplicación seleccionada y la pantalla de configuración que fue elegida ("**Configuraciones Administradas**");

{% hint style="info" %}
**NOTA**

Las configuraciones disponibles se mostrarán según lo que esté disponible para cada aplicación, es decir, las configuraciones disponibles variarán dependiendo de la aplicación seleccionada. En algunos casos, por ejemplo, se mostrará el mensaje: No existen configuraciones disponibles para esta aplicación. Estas configuraciones de trabajo dependen de la empresa que creó la aplicación.
{% endhint %}

## **Permisos**

Para acceder a la configuración de permisos de una aplicación, debe estar en la pantalla "Editar política" con la pestaña "**Aplicaciones**" seleccionada. Siga los siguientes pasos:

1. Localice la aplicación deseada y haga clic en los tres puntos al final de la línea para mostrar el menú con más opciones;
2. Haga clic en "**Permisos**".

![](<../../../../../.gitbook/assets/4 (14).png>)

Después del paso 2 se mostrará la siguiente pantalla. La lista blanca, que se puede configurar en la aplicación seleccionada, se muestra en esta pantalla.

![](<../../../../../.gitbook/assets/5 (13).png>)

Los permisos se pueden configurar como: Solicitar al usuario, Activada o Denegada.

{% hint style="info" %}
**OBSERVACIÓN**\
Si la opción “Permisos" aparece deshabilitada en el sistema, es para evitar que el usuario acceda a configuraciones que no son relevantes para su función. Esto garantiza que el usuario no se confunda o intente ajustar configuraciones que no están dentro de sus atribuciones o necesidades específicas dentro del sistema.
{% endhint %}

## **Configuraciones Avanzadas**

Para acceder a la configuración avanzada de una aplicación, debe estar en la pantalla "**Editar política**" con la pestaña "**Aplicaciones**" seleccionada. Siga los siguientes pasos:

1. Localice la aplicación deseada y haga clic en los tres puntos al final de la línea para mostrar el menú con más opciones;
2. Haga clic en "**Configuraciones Avanzadas**".

![](<../../../../../.gitbook/assets/6 (13).png>)

Después del paso 2 se mostrará la siguiente pantalla. En esta pantalla tenemos los siguientes elementos:

* **Prioridad de actualización -** Establezca la prioridad de actualización de la aplicación como predefinida, retrasada o prioritaria.
* **Versión mínima -** permite definir una versión mínima de la aplicación.

![](<../../../../../.gitbook/assets/7 (12).png>)

## **Eliminar Aplicación**

Para eliminar una aplicación de la directiva, debe estar en la pantalla "**Editar política**" con la pestaña "**Aplicaciones**" seleccionada. Siga los siguientes pasos:

1. Localice la aplicación deseada y haga clic en los tres puntos al final de la línea para mostrar el menú con más opciones;
2. Haga clic en "**Eliminar aplicación**".

![](<../../../../../.gitbook/assets/8 (12).png>)

Después del paso 2 se mostrará la siguiente pantalla para confirmar la eliminación. Haga clic en el botón "Eliminar" para eliminar la aplicación de la lista.

![](<../../../../../.gitbook/assets/9 (12).png>)

{% hint style="info" %}
**NOTA**

La aplicación se eliminará de la lista de aplicaciones de la política que se está editando, pero permanecerá en Aplicaciones administradas, se puede volver a incluir en la política y puede formar parte de la configuración de otras políticas.
{% endhint %}

## Agregar aplicaciones

La opción Agregar aplicaciones tendrá diferentes comportamientos cuando el Modo Quiosco está activado o desactivado.

* **Modo Kiosco Desactivado:** Al hacer clic en el botón "**Agregar Aplicaciones**", si se trata de una política con modo kiosco desactivado, se mostrarán dos opciones: Play Store, que incluye la lista de aplicaciones que fueron añadidas usando [**Google Play Administrado**](../../../gestion-de-aplicaciones/google-play-administrada.md), y la opción Manual, que permite agregar aplicaciones de forma manual.

<figure><img src="../../../../../.gitbook/assets/image (133).png" alt=""><figcaption></figcaption></figure>

* **Modo Quiosco Habilitado:** Si la política que se está editando es una política con el Modo Quiosco Habilitado, al hacer clic en el botón **Agregar aplicaciones**, se mostrarán las 3 opciones para agregar las aplicaciones.

<figure><img src="../../../../../.gitbook/assets/image (134).png" alt=""><figcaption></figcaption></figure>

* **Sistema**

1. Haga clic en la opción "**Sistema**", y se abrirá la pantalla "**Aplicaciones del sistema**"
2. Seleccione el fabricante y el dispositivo
3. Seleccione una o más aplicaciones haciendo clic en la casilla
4. Haga clic en el botón "**Añadir seleccionados**"

<figure><img src="../../../../../.gitbook/assets/image (159).png" alt=""><figcaption></figcaption></figure>

* **Playstore**

1. Haga clic en la opción "**Playstore**", y se abrirá la pantalla "**Agregar aplicaciones**"
2. Seleccione una o más aplicaciones haciendo clic en la casilla
3. Haga clic en el botón "**Añadir seleccionados**"

<figure><img src="../../../../../.gitbook/assets/image (160).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
IMPORTANTE

Las aplicaciones deben agregarse primero con **Google Play Administrado.**
{% endhint %}

* **Manual**

1. Haga clic en la opción "Manual", y abrirá la pantalla "Agregar aplicaciones manualmente"&#x20;
2. Rellenar los campos: Nombre de la aplicación (opcional), Nombre del paquete y haga clic en "Agregar".

El tipo de instalación será "Disponible" y permitirá cambiar el tipo de instalación de la aplicación a las opciones: Disponible, Preinstalado, Instalación forzada o Bloqueado, y enviará al dispositivo la aplicación con el tipo de instalación definido al guardar la política.

{% hint style="info" %}
**NOTA**&#x20;

Si la aplicación no está en Google Play, las opciones "Preinstalado" e "Instalación forzada" tendrán el mismo efecto que la opción "Disponible". Es decir, la aplicación estará disponible para instalación y el usuario tendrá la opción de instalarla según su conveniencia. No se instala automáticamente en el dispositivo.
{% endhint %}

<figure><img src="../../../../../.gitbook/assets/image (161).png" alt="" width="447"><figcaption></figcaption></figure>

* **Remota**

Los aplicativos enviados mediante instalación remota, a través del menú "**Instalación Remota de Aplicaciones**", se mostrarán en la lista de aplicativos con el ORIGEN = "Remota" y con el tipo de instalación 'Disponible' con la edición bloqueada.



### Restricciones de Funcionamiento

Para definir restricciones de funcionamiento de aplicaciones por días y horarios, es necesario hacer clic en el icono de restricciones de funcionamiento en la linea correspondiente a la aplicación deseada. La siguiente imagen destaca:

1. Ícono para acceder a la opción 'Restricciones de Funcionamiento'"

<figure><img src="../../../../../.gitbook/assets/image (4) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

2. Botón selector para activar restricciones.

<figure><img src="../../../../../.gitbook/assets/image (6) (1) (1) (1).png" alt="" width="563"><figcaption></figcaption></figure>

La opción de "Restricciones de Funcionamiento" está disponible para todas las aplicaciones, excepto la aplicación del sistema **\<NombreProduto>** Cuando una aplicación ya tiene restricciones de funcionamiento, su ícono de restricción cambiará y mostrará un pequeño punto rojo<img src="../../../../../.gitbook/assets/image (7) (1) (1) (1).png" alt="" data-size="line">.

Para activar las restricciones:

1. Seleccione el campo “Permitir restricciones".
2. Indique la hora de uso para cada día, movendo el punto inicial(hora inicial) e punto final (hora final) con el mouse, o seleccione el campo "Restringir" para bloquear el funcionamiento durante todo el día.

<figure><img src="../../../../../.gitbook/assets/image (8) (1) (1) (1).png" alt="" width="563"><figcaption></figcaption></figure>

3. Haga clic en "Confirmar" para guardar los cambios. La política enviará la información de las restricciones de la aplicación a los dispositivos vinculados.
