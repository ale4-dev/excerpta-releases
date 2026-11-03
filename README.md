# Excerpta para instalar

Aplicativo de biblioteca pessoal de citações. Este repositório contém somente a página de downloads e os instaladores. O código-fonte permanece no repositório privado separado.

## Baixar

1. Abra a [lista pública de Releases](https://github.com/ale4-dev/excerpta-releases/releases) e escolha a versão desejada.
2. Na lista **Assets**, baixe o arquivo correspondente ao seu aparelho:

   - `Excerpta-android.apk` para celulares Android.
   - `excerpta-desktop_X.Y.Z_amd64.deb` para Linux de 64 bits.
   - `Excerpta-Setup-X.Y.Z.exe` para Windows de 64 bits.

3. Siga as instruções de instalação descritas nas notas da Release.

O Excerpta não será distribuído pela Play Store. Qualquer pessoa poderá baixar os instaladores desta página. A disponibilidade de APKs para instalação direta depende das configurações de segurança e das regras Android em vigor no aparelho.

## Citações e privacidade

Os instaladores contêm o aplicativo e os recursos necessários para executá-lo. Eles não contêm citações, documentos, notas, contas, senhas ou cópias do Firestore.

Quando online, a biblioteca continua sincronizada com o Firebase e usa a conta autorizada. Offline, o app conserva as alterações no dispositivo até haver conexão para sincronizar. Instalar pelo GitHub não torna os dados do Firebase públicos.

## Atualizações

Windows e Linux verificam atualizações ao abrir e a cada 12 horas, baixam em segundo plano e oferecem reiniciar para aplicar. A partir do Android 1.0.5, o Excerpta verifica atualizações ao abrir, oferece o botão “Verificar atualizações” em Configurações e pode baixar o APK. Na transição da versão 1.0.4 para a 1.0.5, instale o APK manualmente uma vez. O instalador Android ainda pede confirmação do usuário.

O atualizador desktop depende de uma Release publicada com todos os arquivos e manifestos indicados nas notas da versão. O fluxo Android e os requisitos de sideload podem mudar; veja as notas atuais de cada Release.
