# keylug

Versões do `keylug`, o [Keylug](https://keylug.com) na linha de comando, para você e para agentes de IA.

Este repositório só guarda as [versões](https://github.com/Dangus-Box/keylug-cli/releases): um executável por sistema e o `SHA256SUMS` de cada uma. O código do keylug não fica aqui.

## Instalar

Com Node 20 ou mais novo:

```sh
npx @keylug/cli@latest login
```

Ou baixe o executável do seu sistema na [última versão](https://github.com/Dangus-Box/keylug-cli/releases/latest) (`keylug-linux-x64`, `keylug-darwin-arm64`, `keylug-windows-x64.exe`…). Confira a soma com `sha256sum --check SHA256SUMS --ignore-missing`, dê permissão de execução (`chmod +x`) e coloque-o no seu `PATH`. Ele não precisa de Node nem de Bun.

Quem já tem o keylug instalado atualiza com `keylug update`.

No macOS, os executáveis não são assinados. Se o Gatekeeper reclamar de um baixado pelo navegador, rode `xattr -d com.apple.quarantine keylug`.

Copyright © Keylug. Todos os direitos reservados.
