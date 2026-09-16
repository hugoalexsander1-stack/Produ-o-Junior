# Controle de Produção V2

PWA para GitHub Pages.

## Estrutura
- index.html
- manifest.webmanifest
- sw.js
- icons/icon-192.png
- icons/icon-512.png

## Publicação
1. Crie um repositório público no GitHub.
2. Envie todos os arquivos, mantendo a pasta `icons`.
3. Em Settings > Pages, selecione Deploy from a branch, branch `main` e pasta `/ (root)`.
4. Abra a URL do GitHub Pages em HTTPS.
5. No celular, escolha Adicionar à tela inicial / Instalar aplicativo.

Abrir o HTML diretamente como `file://` não ativa Service Worker; o comportamento PWA completo ocorre no GitHub Pages/HTTPS.
