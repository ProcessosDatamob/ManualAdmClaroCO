# Modo Quiosco

Esta configuración tiene como objetivo permitir la creación de un entorno en el que el usuario del dispositivo solo pueda acceder a las aplicaciones previamente autorizadas por el administrador, es decir, solo se mostrarán los íconos de las aplicaciones seleccionadas en la pantalla del dispositivo.

Para acceder a la configuración del "**Modo Quiosco**", siga estos pasos:&#x20;

1. En la pantalla "[Editar política](./)", seleccione la pestaña "**Modo Quiosco**".&#x20;
2. Active el modo quiosco haciendo clic en el botón de activación.

<figure><img src="../../.gitbook/assets/Captura de tela 2024-01-11 135757.png" alt=""><figcaption></figcaption></figure>

3. En la pantalla se mostrará un mensaje de confirmación. Confirme haciendo clic en el botón "Activar".

<figure><img src="../../.gitbook/assets/image (19).png" alt=""><figcaption></figcaption></figure>

4. Al activar el Modo Quiosco en la política y aprovisionar un dispositivo con esta política, la aplicación Kiosk Launcher Manager se instalará automáticamente en el dispositivo.

<mark style="color:red;">Quando o dispositivo instalar o aplicativo Kiosk, o aplicativo capturará a lista de todos os aplicativos instalados no dispositivo enviará esta lista para o Portal. Além disto enviará as seguintes configurações gerenciadas para o portal.  E alterará a launcher do Dispositivo para a launcher do aplicativo Kiosk, não permitirá que o usuário altere a launcher no dispositivo e manterá a configuração de Modo Quiosque recebida na politica.</mark>

### <mark style="color:red;">Opções de configuração do Quiosque</mark>

<mark style="color:red;">Estando o modo quiosque ativado, as seguintes opções de configuração estarão disponíveis:</mark>&#x20;

<figure><img src="../../.gitbook/assets/image (48).png" alt=""><figcaption></figcaption></figure>

* <mark style="color:red;">**Botões de navegação**</mark><mark style="color:red;">: permite definir os botões de navegação do dispositivo como "Ativo", "Bloqueado" ou "Apenas botão Home";</mark>
* <mark style="color:red;">**Botão "Power"**</mark><mark style="color:red;">:  permite definir o botão power do dispositivo como "Disponível" ou "Bloqueado";</mark>
* <mark style="color:red;">**Exibir Mensagens de Erro**</mark><mark style="color:red;">: permite definir a exibição de mensagens de erro como "Ativo" ou "Silenciado";</mark>
* <mark style="color:red;">**Informações Exibidas na Barra de Status**</mark><mark style="color:red;">: permite definir as informações que serão exibidas na barra de status do dispositivo.  Pode ser definido como "Notificações e informações do sistema", "Apenas informações do sistema" ou "Nenhuma";</mark>
* <mark style="color:red;">**Acesso à Configurações**</mark><mark style="color:red;">: permite definir como "Liberado" ou "Bloqueado";</mark>
* <mark style="color:red;">**Serviços Adicionais de Telefonia**</mark><mark style="color:red;">: permite definir os serviços de telefonia como "Ativo" ou "Definido pelo dispositivo".  Ao definir como "Ativo" e salvar a política, o sistema enviará na política e no quiosque os pacotes dos serviços de telefonia para o dispositivo, e permitirá receber e realizar ligações no dispositivo que provisionar a política. E ao definir como "Definido pelo Dispositivo", o dispositivo funcionará de acordo com a sua configuração padrão, tendo ou não os serviços.</mark>
* **Fondo de pantalla** - Es posible cargar una imagen para el fondo de pantalla en la política y establecer la orientación de la pantalla, la cual se enviará a la aplicación.
* **Color de fuente de los iconos** - Permite configurar el color del texto de los iconos en la pantalla de inicio.
* **Orientación de pantalla** - Permite seleccionar la orientación de pantalla para el dispositivo, y el valor predeterminado es 'Definido por el usuario'."
* **Tamaño de iconos y fuentes** - Permite seleccionar las siguientes opciones de tamaño de pantalla: Estándar del sistema (predeterminado), Pequeño (75%) y Grande (125%).
* **Ordenación de los iconos** - Permite realizar la ordenación de los iconos por orden alfabético o por fecha de inclusión.
* **Posicionamiento de la imagen** - Permite seleccionar la posición de la imagen del fondo de pantalla en la pantalla de inicio del dispositivo.

Las aplicaciones que se mostrarán en el dispositivo se establecerán mediante la política, es decir, solo las aplicaciones autorizadas en la política se mostrarán en el quiosco.
