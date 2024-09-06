# Dashboard

Esta pantalla del sistema tiene como objetivo permitir al usuario la visualización y análisis de los diversos datos de consumo y uso obtenidos de los dispositivos. Todos estos datos se detallarán en esta sección.

Para saber cómo acceder y analizar los datos mostrados en el Dashboard, siga los pasos descritos en esta sección.

La pantalla de Dashboard puede ser considerada la "Pantalla de Inicio" del sistema, pues se muestra inmediatamente después de que el usuario acceda al Portal, pero también se puede acceder haciendo clic en el menú "Dashboard". En un primer acceso, los indicadores de usuarios, dispositivos y consumos no tendrán aún información, por lo que estarán en cero.

<figure><img src="../.gitbook/assets/image (169).png" alt=""><figcaption></figcaption></figure>

Al acceder a la pantalla, toda la información se mostrará separada por secciones. Cada sección corresponde a un dato diferente, obtenido del dispositivo y toda la información se muestra de acuerdo con las opciones seleccionadas en el filtro (Empresa, Grupo o Usuario).

<mark style="color:red;">Al habilitar la opción del filtro “Roaming internacional”, en la esquina superior derecha de la pantalla, el sistema también mostrará la información recopilada cuando los dispositivos estén utilizando una conexión en Roaming.</mark>

![](<../.gitbook/assets/11 (4).png>)

Los filtros "Empresa", "Grupo" y "Usuario" permiten realizar un análisis de los datos de los dispositivos de un nivel determinado.

Haga clic en el filtro "Empresa", escriba y seleccione el nombre de la empresa para mostrar la información recopilada de todos los dispositivos.

<figure><img src="../.gitbook/assets/image (163).png" alt=""><figcaption></figcaption></figure>

Haga clic en el filtro "Grupo", escriba y seleccione el nombre del grupo para mostrar la información recopilada de todos los dispositivos que forman parte de un grupo.

<figure><img src="../.gitbook/assets/image (164).png" alt=""><figcaption></figcaption></figure>

Haga clic en el filtro "Usuario" escriba y seleccione el usuario, para mostrar la información recopilada del dispositivo del usuario.

<figure><img src="../.gitbook/assets/image (165).png" alt=""><figcaption></figcaption></figure>

En la esquina superior derecha de la pantalla, tenemos algunos iconos que tienen las siguientes características:

* Notificaciones - En el icono ![](https://lh7-us.googleusercontent.com/LIqOOPLli\_-KQv0gbnkeBAgAG1\_EOWziv1kRkMmMtO2dOIvA17vDOpWbmtTw5\_2RUg1D-mUt1PWNvciaKyYAHysUPk47UBQ8yIufI8DmrX523Zqn\_ntcDKa0ff0KqkWZeeaDLHoJF9MB762IkIm6vw)el administrador puede ver las notificaciones del portal, por ejemplo, al solicitar la generación de un reporte.
* Admin - En el icono ![](https://lh7-us.googleusercontent.com/XnN5TtWJIzJYNZfcb\_18o7Mzx\_RrJYRxyodSpfkBQuPCce64vPyFVeN6g6umpqRYxKpCZ\_v8JGiU3iuMYa4vOmakPCagWJmIJFLK3dsOj3f7Ta1mH0KwNpxCTIGDJ5xs1IUicW1Ncuv2XJcBMyJvGg) despliega la opción para que el administrador pueda salir del portal y también muestra la versión actual de la solución el número de versión.

<figure><img src="../.gitbook/assets/image (166).png" alt=""><figcaption></figcaption></figure>

## **Barra de Estado**

La barra de estado de Dashboard muestra el estatus actual de todos los usuarios y licencias de la empresa.

<figure><img src="../.gitbook/assets/image (170).png" alt=""><figcaption></figcaption></figure>

## **Total de Usuarios**

Este indicador muestra el número total de usuarios de dispositivos que utilizan la aplicación **\<NomeProduto>.**

![](<../.gitbook/assets/19 (4).png>)

## **Total de Licencias** Contratadas

Este indicador muestra el número total de licencias disponibles en el portal **\<NomeProduto>**.

<figure><img src="../.gitbook/assets/image (171).png" alt=""><figcaption></figcaption></figure>

## **Licencias sin uso**

Este indicador muestra el número total de licencias que no tienen dispositivo registrado en el portal. Es decir, son las licencias disponibles.

Al hacer clic en este indicador, el sistema mostrará la pantalla "Licencias contratadas". Para saber cómo usar esta pantalla, lea la sección "[Licencias contratadas](empresa/licencias-contratadas.md)".

![](<../.gitbook/assets/21 (1).png>)

## **Dispositivos**

Este indicador muestra el número total de dispositivos que están activos en el sistema y los dispositivos sin comunicación. Además, permite al administrador tener la visibilidad de los dispositivos que están en Modo Quiosco.

![](<../.gitbook/assets/0 (3).png>)

* **Total -** Estos dispositivos se consideran "activos" al instalar y activar la aplicación **\<NomeProduto>**. Al hacer clic en "Total" el indicador mostrará la pantalla "Lista de dispositivos" que contiene el reporte con la información clave de los dispositivos activos

Al hacer clic en "Total" el indicador mostrará la pantalla "Lista de dispositivos" que contiene el informe con la información clave de los dispositivos activos.

* **Sim Comunicación -** Este indicador muestra el número total de dispositivos que no están enviando datos a los servidores durante un período prolongado. Al hacer clic en "Sin comunicación" el sistema muestra la pantalla de dispositivos sin comunicación.

<figure><img src="../.gitbook/assets/image (125).png" alt=""><figcaption></figcaption></figure>

Esta falta de comunicación puede ocurrir cuando el dispositivo se encuentra en las siguientes situaciones:

* Desconectado.
* Sin conexión a Internet.
* Aplicación desinstalada.

El cálculo de tiempo para considerar el dispositivo sin comunicación es el tiempo de sincronización configurado en la empresa + 10 minutos.

Si el dispositivo no envía consumos generales/información del dispositivo durante un tiempo superior al tiempo de sincronización establecido + 10 minutos, cambia el estado a Sin comunicación.

Para que el dispositivo vuelva a comunicarse, el administrador puede enviar un mensaje con el comando START\_SERVICES a través del menú Mensajes del portal.

Al hacer clic en el indicador Sin comunicación ,el sistema mostrará una pantalla que contiene el informe con la información de los dispositivos que están sin comunicación.

## **Consumo de Datos Móviles**

Este indicador muestra el porcentaje de consumo de datos móviles de los dispositivos durante el ciclo con respecto al límite total configurado en el perfil de consumo. Si no se establece un límite en el perfil de consumo, el gráfico no muestra el porcentaje y el sistema solo muestra el valor total de datos en MB utilizado.

<figure><img src="../.gitbook/assets/Captura de tela 2024-09-06 144221.png" alt=""><figcaption></figcaption></figure>

## **Consumo de SMS**

Este indicador muestra el porcentaje de consumo de SMS enviados por los dispositivos durante el ciclo con respecto al límite total configurado en el perfil de consumo. Si no se establece un límite en el perfil de consumo, el gráfico no muestra el porcentaje y solo muestra el valor total de SMS utilizado.

<figure><img src="../.gitbook/assets/image (172).png" alt=""><figcaption></figcaption></figure>



## <mark style="color:red;">**Consumo total de datos**</mark>&#x20;

<mark style="color:red;">Este gráfico permite visualizar el consumo de datos, incluyendo datos móviles, Wi-Fi y datos en roaming, en el Dashboard del portal. La funcionalidad permite un análisis detallado del uso de datos en los dispositivos.</mark>

<mark style="color:red;">El gráfico mostrará:</mark>

* <mark style="color:red;">Porcentaje del consumo de datos móviles locales en relación con el total de datos (móviles + Wi-Fi).</mark>
* <mark style="color:red;">Porcentaje del consumo de datos vía Wi-Fi en relación con el total de datos (móviles + Wi-Fi).</mark>

<figure><img src="../.gitbook/assets/image (173).png" alt=""><figcaption></figcaption></figure>

<mark style="color:red;">**Leyenda Mostrada:**</mark>

* <mark style="color:red;">**Total:**</mark> <mark style="color:red;"></mark><mark style="color:red;">Suma de datos móviles y Wi-Fi.</mark>
* <mark style="color:red;">**Datos móviles locales:**</mark> <mark style="color:red;"></mark><mark style="color:red;">Consumo de datos móviles en redes locales.</mark>
* <mark style="color:red;">**Wi-Fi:**</mark> <mark style="color:red;"></mark><mark style="color:red;">Consumo total de datos vía Wi-Fi.</mark>

<mark style="color:red;">Al activar la opción de Roaming, el gráfico mostrado se actualizará para incluir el consumo de datos en roaming.</mark>

<mark style="color:red;">El gráfico mostrará:</mark>

* <mark style="color:red;">Porcentaje de datos móviles locales (móviles + roaming + Wi-Fi).</mark>
* <mark style="color:red;">Porcentaje de datos móviles en roaming (móviles + roaming + Wi-Fi).</mark>
* <mark style="color:red;">Porcentaje de Wi-Fi (móviles + roaming + Wi-Fi).</mark>

<figure><img src="../.gitbook/assets/image (174).png" alt=""><figcaption></figcaption></figure>

<mark style="color:red;">**Leyenda Mostrada:**</mark>

* <mark style="color:red;">**Total:**</mark> <mark style="color:red;"></mark><mark style="color:red;">Suma de datos móviles, Wi-Fi y roaming.</mark>
* <mark style="color:red;">**Datos móviles locales:**</mark> <mark style="color:red;"></mark><mark style="color:red;">Consumo de datos móviles en redes locales.</mark>
* <mark style="color:red;">**Datos móviles en roaming:**</mark> <mark style="color:red;"></mark><mark style="color:red;">Consumo de datos móviles en roaming.</mark>
* <mark style="color:red;">**Wi-Fi:**</mark> <mark style="color:red;"></mark><mark style="color:red;">Consumo total de datos vía Wi-Fi.</mark>

<mark style="color:red;">Al pasar el ratón sobre el gráfico o la leyenda en el Dashboard, el sistema mostrará una caja de texto.</mark>

<mark style="color:red;">La caja de texto mostrará:</mark>

* <mark style="color:red;">El tipo de dato (móvil, Wi-Fi o roaming).</mark>
* <mark style="color:red;">El porcentaje en relación con el total de datos.</mark>
* <mark style="color:red;">El valor exacto del consumo de datos.</mark>

## **Consumo de Datos por Aplicación**

<mark style="color:red;">Este gráfico muestra el nombre y el valor del porcentaje de las 5 aplicaciones que más consumieron datos móviles y las 5 aplicaciones que más consumieron datos en WiFi durante el ciclo. Solo es necesario hacer clic en la opción de visualización deseada (Datos móviles o WiFi). Los datos mostrados están ordenados según el porcentaje.</mark>

El valor porcentual de cada una de las 5 aplicaciones se calcula en relación con la suma total de consumo de todas las aplicaciones durante el ciclo.

Al hacer clic en el botón “Ver lista completa” el sistema exhibirá en pantalla todos los datos de las aplicaciones. Para saber cómo utilizar esa pantalla, lea la sección “[Aplicaciones](configuracion/editar-politica/aplicaciones/)” en este manual.

<mark style="color:red;">Esto ofrece a los usuarios una visión más detallada y específica del consumo de datos, permitiendo un análisis más preciso y segmentado, tanto en redes móviles como en WiFi.</mark>

<figure><img src="../.gitbook/assets/image (175).png" alt=""><figcaption></figcaption></figure>

## **Consumo de Datos por Usuario**

<mark style="color:red;">Este gráfico muestra a los 5 usuarios que más consumieron datos móviles y a los que más consumieron datos en WiFi durante el ciclo. Solo es necesario hacer clic en la opción de visualización deseada (Datos móviles o WiFi). Los datos mostrados están ordenados por porcentaje.</mark>

El valor porcentual de cada uno de los 5 usuarios se calcula en relación con la suma total de consumo de todos los usuarios durante el ciclo.

Al hacer clic en el botón "Ver lista completa" el sistema mostrará la pantalla con la información de consumo de la empresa. Para saber cómo utilizar esta pantalla, lea la sección "[Consumo de la empresa](empresa/consumo-de-la-empresa.md)" de este manual.

<figure><img src="../.gitbook/assets/image (176).png" alt=""><figcaption></figcaption></figure>

## **Tiempo de uso por aplicación**

Este gráfico muestra las 5 aplicaciones más utilizadas durante el ciclo. Este tiempo se cuenta solo cuando la aplicación está en uso, y no necesita estar consumiendo datos. Las aplicaciones en segundo plano no se contabilizan en este análisis. También no se contabilizan uso en Wi-Fi ni en otras redes.

El valor porcentual de cada una de las 5 aplicaciones se calcula en relación con la suma total del tiempo de uso de todas las aplicaciones durante el ciclo.

Al hacer clic en el botón "Ver lista completa" el sistema mostrará la pantalla con la información de todas las aplicaciones. Para saber cómo utilizar esta pantalla, lea la sección "[Aplicaciones](configuracion/editar-politica/aplicaciones/)" de este manual.

![](<../.gitbook/assets/6 (3).png>)

## **Inventario de Dispositivos**

Este indicador muestra el porcentaje de los 5 fabricantes de dispositivos activos. El valor porcentual de cada uno de los 5 fabricantes se calcula en relación con la suma total de todos los dispositivos activos.

<figure><img src="../.gitbook/assets/image (177).png" alt=""><figcaption></figcaption></figure>

## **Sitios más visitados**

Este indicador muestra el porcentaje de los 5 sitios más visitados en los dispositivos durante el ciclo. El valor porcentual de cada uno de los 5 sitios se calcula en relación a la suma total de todos los accesos a los sitios durante el ciclo.

{% hint style="warning" %}
**ATENCIÓN**

Los sitios web visitados son obtenidos por el navegador web predeterminado del sistema  **\<NomeProduto>**. Este navegador se llama Security Browser y necesita estar instalado y configurado en los dispositivos. Para obtener más información sobre la administración y configuración del navegador, visite la sección "[Security Browser"](configuracion/editar-politica/aplicaciones/bloqueo-de-sitios-web-security-browser.md).
{% endhint %}

![Gráfico, Gráfico de barras

Descrição gerada automaticamente](<../.gitbook/assets/8 (2).png>)

## **Indicador de Consumo y su Historial**

Este indicador muestra en porcentaje los datos móviles y SMS consumidos en los últimos 6 ciclos. Para realizar el análisis individual de los consumos de datos móviles o SMS, acceda al punto "[Consumos de la empresa](empresa/consumo-de-la-empresa.md)" en el menú "[Empresa](empresa/)".

![Gráfico, Gráfico de barras

Descrição gerada automaticamente](<../.gitbook/assets/9 (2).png>)

## **Indicador de Nuevos Usuarios de dispositivos y su Historial**

Este indicador muestra la cantidad de usuarios de dispositivos activados en los últimos 6 ciclos y la evolución de los nuevos usuarios del ciclo actual con respecto a los del trimestre y del semestre.

Para realizar el análisis individual de los usuarios de dispositivos, haga clic en "[Lista de dispositivos](dispositivos/lista-de-dispositivos/)" en el menú "[Dispositivos](dashboard.md#dispositivos)".

![Gráfico, Gráfico de barras

Descrição gerada automaticamente](<../.gitbook/assets/10 (2).png>)

## **Ubicación de los Dispositivos**

El mapa muestra la última ubicación de los dispositivos. Para que la ubicación se muestre y actualice, el dispositivo debe estar conectado a Internet, debe haber señal GPS y la configuración de "Modo de Localización" debe estar "Activa" en Ubicación en la política aplicada al dispositivo.

<figure><img src="../.gitbook/assets/Captura de tela 2024-05-16 144307.png" alt=""><figcaption></figcaption></figure>

Si el sistema no carga las ubicaciones en el mapa, haga clic en el botón "Ver ubicaciones" para mostrar las ubicaciones.

<mark style="color:red;">Si el sistema no carga las ubicaciones en el mapa, haga clic en el botón "Mostrar ubicaciones", entonces se mostrarán según la pantalla a continuación:</mark>

<figure><img src="../.gitbook/assets/image (167).png" alt=""><figcaption></figcaption></figure>

<mark style="color:red;">La regla de agrupamiento de los dispositivos es la siguiente:</mark>

* <mark style="color:red;">**Azul:**</mark> <mark style="color:red;"></mark><mark style="color:red;">mayor o igual a 5</mark>
* <mark style="color:red;">**Amarillo:**</mark> <mark style="color:red;"></mark><mark style="color:red;">mayor o igual a 10</mark>
* <mark style="color:red;">**Rojo:**</mark> <mark style="color:red;"></mark><mark style="color:red;">mayor o igual a 100</mark>

<mark style="color:red;">Por debajo de 5, se muestran los pines normalmente.</mark>

<mark style="color:red;">El símbolo de gota naranja con un número dentro indica los puntos por los que pasó el usuario en orden numérico durante el día.</mark>

Lea la sección "[Administrar políticas](configuracion/administrar-politicas/)" de este manual para saber cómo activar el "Modo de ubicación" de los dispositivos.

Utilice los recursos del mapa para optimizar la visualización de las ubicaciones.

## **Manuales para Descargar**

En esta pantalla tendremos acceso a los manuales descargables. Al hacer clic en "Más información", se mostrará la pantalla con Documentos y Materiales de Apoyo.

<figure><img src="../.gitbook/assets/image (178).png" alt=""><figcaption></figcaption></figure>

## **Alguna Duda**

A través de la sesión “_Alguna duda?_" tendremos acceso a la pantalla donde es posible visualizar las preguntas frecuentes realizadas por los usuarios:

<mark style="color:red;background-color:orange;">ATUALIZAR IMAGENS</mark>

<figure><img src="../.gitbook/assets/image (179).png" alt=""><figcaption></figcaption></figure>

Al hacer clic en "Más información", nos dirigiremos a la siguiente pantalla, donde es posible realizar una búsqueda a través del campo de escritura libre o bien filtrar por categoría.

<figure><img src="../.gitbook/assets/image (53).png" alt=""><figcaption></figcaption></figure>
