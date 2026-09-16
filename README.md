# Controle de Produção V2.1

PWA para controle local de produção de técnico de telecom.

## PWA
- `manifest.webmanifest` configurado para instalação.
- `sw.js` registrado automaticamente pelo `index.html`.
- Cache offline do app shell.
- Ícones PNG 192x192 e 512x512.
- `display: standalone` para abrir como aplicativo.
- Funciona com GitHub Pages/HTTPS.

## Publicação no GitHub Pages
1. Envie todos os arquivos mantendo a pasta `icons/`.
2. GitHub → Settings → Pages.
3. Deploy from branch → `main` → `/ (root)`.
4. Abra a URL do Pages no Chrome.
5. Use “Adicionar à tela inicial”/“Instalar app”.
