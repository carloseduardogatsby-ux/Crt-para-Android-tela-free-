# CRT Overlay para YouTube no Android

Este aplicativo Android adiciona uma camada de tubo CRT (scanlines + curvatura + fósforo) sobre **toda a tela do celular**.

## Como funciona:
1. Usa o serviço `OverlayService.kt` com a permissão `SYSTEM_ALERT_WINDOW`.
2. A tela do YouTube, vídeos e jogos continuam funcionando e recebendo toques normalmente (`FLAG_NOT_TOUCHABLE`).
3. O efeito fica visível por cima de qualquer app que você abrir!

## Como compilar o APK:
### Opção 1: GitHub Actions (Grátis na Nuvem)
Basta subir este repositório para o seu GitHub. A aba **Actions** compila o APK automaticamente em 2 minutos!

### Opção 2: Linha de comando com Gradle
```bash
./gradlew assembleDebug
```
O APK pronto estará em: `app/build/outputs/apk/debug/app-debug.apk`.
