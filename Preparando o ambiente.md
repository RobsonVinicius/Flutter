<div align="center">

## Preparando o ambiente

</div>

O Flutter está disponível para [download em sua página oficial](https://flutter.dev/docs/get-started/install), escolha o sistema operacional que está utilizando e siga as instruções de instalação.

Após finalizar a configuração que adiciona o Flutter na variável de ambiente `PATH`, que permite usar o Flutter em qualquer diretório via prompt ou terminal, execute o comando `flutter doctor` no terminal ou prompt, deve apresentar um resultado similar a este:

```
[-] Android toolchain - develop for Android devices
    • Android SDK at /Users/obiwan/Library/Android/sdk
    ✗ Android SDK is missing command line tools; download from https://goo.gl/XxQghQ
    • Try re-installing or updating your Android SDK,
      visit https://flutter.dev/setup/#android-setup for detailed instructions.
```

Essa resposta é uma abordagem comum no comando `doctor` que avalia se o ambiente está corretamente configurado, caso tiver alguma divergências, é apresentado o que falta e em alguns casos a mensagem de alerta sugere a execução de comandos para resolver o problema.

> A mensagem final do `flutter doctor` varia de acordo com o que você tem instalado no seu computador.

## Instalando o Android Studio e Android SDK

Após instalar o Flutter, [baixe](https://developer.android.com/studio) e [instale](https://developer.android.com/studio/install) o Android Studio para acessar o Android SDK e criar um emulador Android que será utilizado durante o curso.

## Criando o emulador

Ao finalizar o processo de instalação, vai aparecer a launcher do Android Studio, clique na opção **Configure** na parte inferior à direita e escolha a opção AVD Manager, siga as [instruções para criar um emulador](https://developer.android.com/studio/run/managing-avds#createavd). Na documentação do Flutter também apresenta [tutorial de instalação do emulador](https://developer.android.com/studio/run/managing-avds#createavd).

> No curso utilize a versão 3.5 do Android Studio e o emulador da API 28 Android P. Se no momento que estiver fazendo o curso tiver uma mais recente, fique à vontade em utilizá-la.

## Escolhendo o editor/IDE para desenvolvimento

Por fim, precisamos configurar a ferramenta que vai nos auxiliar na escrita de código. No momento que o curso foi gravado a documentação do Flutter apresentou como sugestão as seguintes ferramentas:

- [Android Studio](https://developer.android.com/studio/?gclid=CjwKCAjwnf7qBRAtEiwAseBO_BobM1iO9FF-eUZvu8v2W8sswy17Xpowwpl2dfQ1kWxA-0tX02yuHhoCeb0QAvD_BwE);
- [VSCode](https://code.visualstudio.com/);
- [IntelliJ](https://www.jetbrains.com/idea/download/).

Você pode escolher a ferramenta da sua preferência, as configurações necessárias são descritas na [página oficial do Flutter que sugere a instalação de plugins tanto para o Flutter como para o Dart](https://flutter.dev/docs/get-started/editor).

Durante o curso utilizaremos o IntelliJ, sendo assim, você pode escolher entre o Android Studio ou o IntelliJ para manter um ambiente similar ao que será apresentado no curso. 

> O Android Studio é um IntelliJ Community personalizado com tudo o que você precisa para desenvolver com o Flutter, segundo a documentação. Portanto, você pode baixar apenas o Android Studio e utilizá-lo como IDE também!

Após realizar todas as configurações, você pode verificar se o ambiente configurado está correto com `flutter doctor` e se tudo der certo, podemos prosseguir com a próxima atividade.

Caso tenha algum problema, entre em contato com a gente por meio do fórum :)
