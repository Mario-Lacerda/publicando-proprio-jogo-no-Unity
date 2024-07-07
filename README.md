# Desafio Dio Publicando o seu Próprio Jogo no Unity



##### Publicando o seu Próprio Jogo no Unity

**Projeto completo e abrangente com mais códigos para publicar seu próprio jogo no Unity:**

**Objetivo:** Publicar um jogo desenvolvido com o Unity em várias plataformas.



**Recursos:**



- **Unity Editor**

- **Contas nas plataformas de publicação**

- **Arquivos do jogo**

  

**Passos:**



**1. Crie seu jogo no Unity.**



**2. Escolha as plataformas nas quais deseja publicar seu jogo.**



**3. Crie contas nas plataformas de publicação escolhidas.**



**4. Configure as configurações de publicação do Unity para cada plataforma.**



**5. Construa o seu jogo para cada plataforma.**



**6. Envie seu jogo para as plataformas de publicação.**

**7. Aguarde a aprovação do seu jogo.**



**8. Publique seu jogo.**



**Códigos e aplicabilidade:**



**Configuração das configurações de publicação do Unity:**

plaintext



```plaintext
Edit > Project Settings > Player
```



**Construindo o seu jogo:**

plaintext



```plaintext
File > Build Settings
```



**Envio do seu jogo para as plataformas de publicação:**



- **Google Play:** Console do Google Play
- **Apple App Store:** App Store Connect
- **Steam:** Steamworks



**Códigos adicionais:**



**Exemplo de código para construir o seu jogo para o Google Play:**

plaintext



```plaintext
BuildPipeline.BuildPlayer(scenes, "path/to/apk", BuildTarget.Android, BuildOptions.None);
```



**Exemplo de código para enviar o seu jogo para a App Store da Apple:**

plaintext



```plaintext
xcrun altool --upload-app -f "path/to/ipa" -u "appleid" -p "password"
```



**Exemplo de código para enviar o seu jogo para o Steam:**

plaintext



```plaintext
steamcmd +login "username" "password" +app_build_upload_start 480 +app_build_upload_init 480 "path/to/build" +app_build_upload_finish 480
```



**Recursos adicionais:**

- Documentação da Unity sobre publicação
- Tutorial da Unity sobre como publicar no Google Play
- Tutorial da Unity sobre como publicar na Apple App Store
- Tutorial da Unity sobre como publicar no Steam







**Mais códigos para publicar seu próprio jogo no Unity:**



**Código para assinar seu APK do Android:**

plaintext



```plaintext
jarsigner -verbose -sigalg SHA1withRSA -digestalg SHA1 -keystore "path/to/keystore.jks" "path/to/apk" "alias"
```



**Código para alinhar seu APK do Android:**

plaintext



```plaintext
zipalign -v 4 "path/to/unsigned.apk" "path/to/aligned.apk"
```



**Código para criar um bundle do iOS:**

plaintext



```plaintext
xcodebuild -project "path/to/project.xcodeproj" -scheme "scheme-name" -configuration "Release" -archivePath "path/to/archive.xcarchive"
```



**Código para exportar um bundle do iOS:**

plaintext



```plaintext
xcodebuild -exportArchive -archivePath "path/to/archive.xcarchive" -exportPath "path/to/ipa" -exportOptionsPlist "path/to/exportOptions.plist"
```



**Código para enviar um bundle do iOS para a App Store:**

plaintext



```plaintext
altool --upload-app -f "path/to/ipa" -u "appleid" -p "password"
```



**Código para criar um pacote do Steam:**

plaintext



```plaintext
steamcmd +login "username" "password" +app_build_upload_start 480 +app_build_upload_init 480 "path/to/build" +app_build_upload_finish 480
```



**Recursos adicionais:**



- Documentação da Unity sobre publicação
- Tutorial da Unity sobre como publicar no Google Play
- Tutorial da Unity sobre como publicar na Apple App Store
- Tutorial da Unity sobre como publicar no Steam





## Exemplo de Código



Aqui está um exemplo simples de como carregar o jogo no HTML:

```
<!DOCTYPE html>
<html>
<head>
    <title>Meu Jogo Incrível</title>
</head>
<body>
    <h1>Bem-vindo ao Meu Jogo!</h1>
    <iframe src="link_do_seu_jogo_aqui" width="800" height="600"></iframe>
</body>
</html>
```
