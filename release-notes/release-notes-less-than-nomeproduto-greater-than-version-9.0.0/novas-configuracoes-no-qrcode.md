# Novas Configurações no QRCode

<mark style="color:red;">Na tela de "Token de Registro" de uma política foram adicionados novos campos para facilitar o enroll do dispositivo, são eles:</mark>

* <mark style="color:red;">**Gerenciar Redes Wi-F**</mark><mark style="color:red;">i - é possível selecionar uma das redes Wi-Fi configuradas na tela "Gerenciar Redes Wi-fi". Ao selecionar uma rede, o sistema incluirá todas as configurações possíveis no QRCode, abrangendo os seguintes tipos de segurança: WPA/WPA 2, WEP e nenhuma segurança. Ao realizar o enroll com o QRCode, o dispositivo se conectará automaticamente à rede configurada, simplificando o processo de configuração inicial do dispositivo.</mark>
* <mark style="color:red;">**Pular Criptografia -**</mark> <mark style="color:red;"></mark><mark style="color:red;">Ao ativar essa opção, o sistema incluirá a seguinte informação no QRCode: "android.app.extra.PROVISIONING\_SKIP\_ENCRYPTION": (true/false - padrão “false"). Ao realizar o enroll com o QRCode, o dispositivo irá ignorar a criptografia do dispositivo durante o processo de configuração inicial.</mark>
* <mark style="color:red;">**Usar Dados Móveis**</mark> <mark style="color:red;"></mark><mark style="color:red;">- Ao ativar essa opção, o sistema incluirá a seguinte informação no QRCode:</mark> <mark style="color:red;"></mark>_<mark style="color:red;">“android.app.extra.PROVISIONING\_USE\_MOBILE\_DATA": (true/false - padrão “false"). A</mark>_<mark style="color:red;">o realizar o enroll com o QRCode, o dispositivo irá utilizar os dados móveis durante o processo de configuração inicial.</mark>

[Volver a la lista de Release Notes](./)
