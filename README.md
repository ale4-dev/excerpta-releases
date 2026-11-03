# Excerpta para instalar

Aplicativo pessoal de biblioteca de citações. Use a página **Releases** para baixar os instaladores. O código-fonte fica em outro repositório.

## Baixar

1. Abra [a versão mais recente em Releases](https://github.com/ale4-dev/excerpta-releases/releases/latest).
2. Na lista **Assets**, baixe o arquivo correspondente ao seu aparelho:

   - `Excerpta-android.apk` para celulares Android.
   - `excerpta-desktop_X.Y.Z_amd64.deb` para Linux de 64 bits.
   - `Excerpta-Setup-X.Y.Z.exe` para Windows de 64 bits.

3. Siga as instruções de instalação descritas nas notas da Release.

O Excerpta não será distribuído pela Play Store. A disponibilidade de APKs para instalação direta depende das configurações de segurança e das regras Android em vigor no aparelho.

## Citações e privacidade

Os instaladores contêm o aplicativo e os recursos necessários para executá-lo. Eles não contêm citações, documentos, notas, contas, senhas ou cópias do Firestore.

Quando online, a biblioteca continua sincronizada com o Firebase e usa a conta autorizada. Offline, o app conserva as alterações no dispositivo até haver conexão para sincronizar. Instalar pelo GitHub não torna os dados do Firebase públicos.

## Atualizações

Windows e Linux verificam atualizações ao abrir e a cada 12 horas, baixam em segundo plano e oferecem reiniciar para aplicar. Android não tem atualização dentro do app nesta versão; é necessário baixar o APK novo e confirmar a instalação no sistema.

O atualizador desktop depende de uma Release publicada com todos os arquivos e manifestos indicados nas notas da versão. O fluxo Android e os requisitos de sideload podem mudar; veja as notas atuais de cada Release.
