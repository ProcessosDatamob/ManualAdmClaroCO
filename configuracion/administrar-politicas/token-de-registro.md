# Token de Registro

Como se ve en la sección anterior, puede acceder al token de registro de dispositivos desde el menú "Configuración" en la opción "Administrar Políticas". La pantalla del token de registro se muestra a continuación.

<figure><img src="../../.gitbook/assets/Captura de tela 2024-05-16 161844 (1).png" alt=""><figcaption></figcaption></figure>

<mark style="color:red;">Os itens disponíveis nesta tela são descritos abaixo:</mark>&#x20;

1. <mark style="color:red;">O Token de Registro da política pode ser copiado e enviado.</mark>
2. <mark style="color:red;">A configuração Zero Touch da política pode ser copiada para ser inserida no painel Zero Touch.</mark>&#x20;
3. <mark style="color:red;">O sistema apresentará um campo para a seleção da 'Rede Wi-Fi'. Nessa tela, será possível escolher uma das redes Wi-Fi previamente configuradas na seção 'Gerenciar Redes Wi-Fi'. Ao selecionar, será incluso no QR Code todas as configurações possíveis com os seguintes tipos de segurança:</mark>
   * <mark style="color:red;">WPA/WPA 2</mark>
   * <mark style="color:red;">WEP</mark>
   * <mark style="color:red;">Nenhuma</mark>

<mark style="color:red;">Ao realizar o registro utilizando o QR Code, o dispositivo será conectado automaticamente à rede configurada.</mark>

4. <mark style="color:red;">A opção “Habilitar Aplicativos de Sistema" permite habilitar todos os aplicativos de sistema nativos do dispositivo.  Quando esta opção é ativada, o sistema atualizará a imagem do QRCode incluindo a informação para habilitar os aplicativos de sistema.</mark>
5. <mark style="color:red;">Ao ativar o campo "Pular Criptografia", será inclusa a seguinte informação no QRCode: "</mark>_<mark style="color:red;">android.app.extra.PROVISIONING\_SKIP\_ENCRYPTION</mark>_<mark style="color:red;">". O sistema também atualizará a imagem do QRCode com a nova configuração e atualizará a configuração do Zero Touch. Após realizar o enroll com o QRCode, o dispositivo ignorará a criptografia do sistema.</mark>
6. <mark style="color:red;">Ao ativar a opção "Usar Dados Móveis" do sistema operacional (SO), será incluída a seguinte informação no QRCode: “</mark>_<mark style="color:red;">android.app.extra.PROVISIONING\_USE\_MOBILE\_DATA</mark>_<mark style="color:red;">". E o sistema atualizará a imagem do QRCode com a nova configuração.  Após realizar o enroll com o QRCode, o dispositivo utilizará os dados móveis durante o processo de configuração.</mark>
7. <mark style="color:red;">Ao concluir as configurações, o sistema permitirá salvar ou cancelar o salvamento das configurações, armazenando-as ao finalizar o processo de salvamento.</mark>
8. <mark style="color:red;">O QR Code da política pode ser lido na tela para o processo de registro de dispositivos ou pode ser copiado e enviado para os usuários dos dispositivos, basta clicar com o botão direito do mouse que aparecem as opções.</mark>
