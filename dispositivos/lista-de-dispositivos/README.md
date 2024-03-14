# Lista de Dispositivos

Para saber cómo administrar los dispositivos activos de la empresa, siga los pasos descritos a continuación.

1. Haga clic en el menú "Dispositivos" opción "Lista de dispositivos" para acceder a la pantalla.

<figure><img src="../../.gitbook/assets/Captura de tela 2023-11-03 103939.png" alt=""><figcaption></figcaption></figure>

2. En la parte superior de la pantalla, el sistema muestra la distribución de los dispositivos, separados por fabricantes.
3. Utilice los filtros Grupo, Política, Modelo y Fabricante para buscar los dispositivos si desea listar.
4. Utilice los Filtros Avanzados para buscar Modo de Administración y Fecha Inicial de Registro y Fecha Final de Registro (filtrará por la fecha de registro de los dispositivos que están en el período especificado) para acceder a la información deseada.
5. Para localizar un dispositivo específico, escriba el nombre de usuario, IMEI o ICCID del dispositivo en el campo "Buscar".
6. Para exportar el reporte de los dispositivos, haga clic en el botón "Excel".
7. Para copiar la información de los dispositivos, haga clic en el botón "Copiar".
8. <mark style="color:red;">Clique na opção de “Ações em lote" para aplicar uma ação em vários dispositivos de uma vez só. Para mais informações, acessar o conteúdo Ações em lote nesta página</mark>
9. La lista de dispositivos se muestra en la parte inferior de la pantalla.
10. Ordene la lista de dispositivos por las columnas en las flechas “ ![](<../../.gitbook/assets/1 (6).png>)”.
11. Haga clic en ">" para ver toda la información del dispositivo.
12. Utilice los tres puntos "..." para mostrar el menú de acciones y aplicar la acción deseada al dispositivo.

### <mark style="color:red;">Ações em lote</mark>

<mark style="color:red;">Ao clicar na opção “Ações em lote" o sistema exibirá uma tela contendo alguns campos para preenchimento, conforme pode ser visto na tela abaixo.</mark>&#x20;

<figure><img src="../../.gitbook/assets/image (49).png" alt=""><figcaption></figcaption></figure>

* <mark style="color:red;">Empresa: clique no campo empresa e no nome da empresa para enviar um camando para todos os dispositivos da empresa (ao selecionar a empresa, os campos de grupo e usuário ficaram desabilitado)</mark>
* <mark style="color:red;">Grupos: clique em grupo e escolha o grupo desejado</mark>
* <mark style="color:red;">Usuário de dispositivos: clique em usuário e escolha o usuário desejado.</mark>&#x20;
* <mark style="color:red;">Comandos: clique em comando e escolha o comando desejado (Desativar dispositivo, Ativar dispositivo, Desligar tela, Reiniciar dispositivo ou Remover dispositivo (Wipe))</mark>

<figure><img src="../../.gitbook/assets/image (50).png" alt=""><figcaption></figcaption></figure>

<mark style="color:red;">Após definir os dados da tela clique em "Enviar" para enviar o comando.  Antes de executar o envio, o sistema abrirá uma caixa de diálogo com os botões "Confirmar" e "Cancelar".</mark>&#x20;

### **Información del dispositivo**

La información del dispositivo que se muestra en la lista es:&#x20;

* Usuario - nombre del usuario registrado en el portal;&#x20;
* Identificación - Identificación registrada para el dispositivo;&#x20;
* Teléfono - número de teléfono;&#x20;
* IMEI - número interno y único en cada dispositivo. En Android 10 ya no es posible capturar esta información del dispositivo porque utilizamos otro método para recibir esta información con el Enriquecimiento de URL;&#x20;
* Modelo - modelo de dispositivo;&#x20;

Al hacer clic en el signo ">" junto al usuario, el sistema muestra más información como se puede ver en la imagen de abajo.

<figure><img src="../../.gitbook/assets/image (3) (1).png" alt=""><figcaption></figcaption></figure>

* Política - nombre de la política asignada al dispositivo;&#x20;
* Modo de administración - modo de administración asignado al dispositivo;
* Versión de la aplicación - versión de la aplicación **\<NomeProduto>** instalado en el dispositivo;&#x20;
* ICCID - número de chip SIM;&#x20;
* Fabricante - nombre del fabricante del dispositivo;&#x20;
* Sistema operativo - versión de Android;&#x20;
* Fecha de registro - fecha y hora de registro del dispositivo;&#x20;
* Grupo - grupo al que está asociado el dispositivo;&#x20;
* Fecha de la última comunicación - última comunicación del dispositivo;&#x20;
* Estado - indica el estado del dispositivo. Los estados que puede tener un dispositivo están en la tabla siguiente:

<table data-header-hidden><thead><tr><th width="229"></th><th></th></tr></thead><tbody><tr><td><strong>Estado</strong></td><td><strong>Descripción</strong></td></tr><tr><td>Activo</td><td>El dispositivo está activo.</td></tr><tr><td>Desactivado</td><td>El dispositivo está desactivado.</td></tr><tr><td>Eliminado</td><td>El dispositivo ha sido eliminado. Este estado se usa en el reporte de estado final cuando el dispositivo confirma la eliminación.</td></tr><tr><td>Aprovisionando</td><td>Se está aprovisionando el dispositivo. Los dispositivos recién registrados permanecen en ese estado hasta que se aplica una directiva.</td></tr></tbody></table>
