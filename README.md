# Copa 2026 • Executive Match Center

## Publicar no GitHub Pages

1. Crie um repositório público, por exemplo: `copa-2026-app`.
2. Envie todos os arquivos desta pasta para a raiz do repositório.
3. Abra **Settings** > **Pages**.
4. Em **Build and deployment**, selecione:
   - Source: **Deploy from a branch**
   - Branch: **main**
   - Folder: **/(root)**
5. Clique em **Save**.
6. O endereço ficará semelhante a:
   `https://SEU-USUARIO.github.io/copa-2026-app/`

## Instalar como aplicativo

### iPhone / iPad
Abra o endereço no Safari, toque em **Compartilhar** e depois em **Adicionar à Tela de Início**.

### Android
Abra no Chrome, toque no menu e escolha **Instalar app** ou **Adicionar à tela inicial**.

### Windows / macOS
Abra no Chrome ou Edge e clique no ícone de instalação na barra de endereço.

## Atualizações futuras

Substitua o arquivo `index.html` e mantenha:
- `manifest.webmanifest`
- `service-worker.js`
- pasta `icons`
- `.nojekyll`

Após uma atualização relevante, altere em `service-worker.js`:
`const CACHE_NAME = "copa-2026-v1";`
para `v2`, `v3` e assim por diante.
