# first_flutter_deploy
First Flutter Deploy Google PlayStore

#Comando para gerar o arquivo my-key.jks. No meu caso eu utilizei o S.O. Windows
Windows
keytool -genkey -v -keystore C:\Users\USER_NAME\my-key.jks -storetype JKS -keyalg RSA -keysize 2048 -validity 10000 -alias my-key-alias

Linux/Mac
keytool -genkey -v -keystore ~/my-key.jks -keyalg RSA -keysize 2048 -validity 10000 -alias my-key-alias

#Estudos baseados nesse arquivo no site Medium
Obrigado Gabriel por compartilhar o seu exemplo que me ajudou bastante.
Segue abaixo a sequência 
https://medium.com/@bernes.dev/publicando-apps-flutter-na-playstore-28fc330679b1

# Aplicativo aplicado com sucesso.
