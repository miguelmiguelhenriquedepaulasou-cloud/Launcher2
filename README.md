# VOID LAUNCHER — projeto Android para gerar APK

Este projeto empacota a interface HTML do protótipo em um aplicativo Android WebView. **Não executa Minecraft Java**; é apenas o app instalável com a interface.

## Gerar APK pelo celular usando GitHub Actions
1. Crie uma conta/entre no GitHub e crie um repositório novo.
2. Envie todos os arquivos e pastas deste projeto para o repositório (inclua `.github/workflows/build-apk.yml`).
3. Abra a aba **Actions**, escolha **Build VOID Launcher APK**, e toque **Run workflow** (ou o workflow executa ao enviar para `main`).
4. Quando terminar com sucesso, abra a execução e baixe o artifact **VOID-Launcher-debug-apk**.
5. Extraia o artifact e instale `app-debug.apk` no Android. Talvez seja necessário permitir instalação de apps dessa fonte.

O projeto usa Gradle/Android SDK no GitHub Actions; o APK não foi compilado/testado nesta entrega.
