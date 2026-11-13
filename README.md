# Sorteador de Vôlei — Android

Projeto Android nativo em Kotlin + Jetpack Compose.

## Funcionalidades da versão 1.0
- 12 jogadores, 4 times com 3 jogadores cada.
- Configuração secreta: 3 jogadores reservados para um dos 4 times.
- Os outros 9 jogadores são embaralhados e distribuídos nos outros 3 times.
- Modo apresentação: revelação individual dos 12 jogadores.
- Resultado final por time.
- Acesso discreto ao organizador: toque cinco vezes no título da tela inicial.

## Como gerar o APK
1. Abra esta pasta no Android Studio (versão recente).
2. Aguarde a sincronização do Gradle e a instalação das dependências.
3. Se solicitado, instale o Android SDK Platform 35.
4. Use **Build > Build Bundle(s) / APK(s) > Build APK(s)**.
5. O APK de depuração ficará em `app/build/outputs/apk/debug/app-debug.apk`.

## Observação sobre o modo oculto
O acesso discreto por cinco toques esconde a configuração da apresentação casual, mas não é uma trava de segurança forte. Esta versão não usa senha e não criptografa os dados de configuração.
