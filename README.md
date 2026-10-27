# Painel SH · app para celular

App web instalável do Painel Financeiro da Ser Humano. Esta pasta guarda só a "casca" do app: ícone, tela de abertura e configuração. Os dados continuam vindo ao vivo do Apps Script, protegidos pela senha do painel.

## Publicar no GitHub Pages
1. Em github.com, clique em **New repository**, dê o nome `painel-sh`, deixe **Public** e crie.
2. Clique em **uploading an existing file**, arraste todo o conteúdo desta pasta (index.html, manifest.webmanifest, sw.js, README.md) e clique em **Commit changes**.
3. Vá em **Settings › Pages**. Em *Branch*, escolha **main** e **/ (root)** e clique em **Save**.
4. Em 1 ou 2 minutos o endereço aparece no topo da página: `https://SEU-USUARIO.github.io/painel-sh/`.

## Instalar no celular
- **iPhone (Safari):** abra o endereço › botão Compartilhar › **Adicionar à Tela de Início** › Adicionar.
- **Android (Chrome):** abra o endereço › menu ⋮ › **Instalar app** (ou "Adicionar à tela inicial").

## Se o link do Apps Script mudar
Abra `index.html`, troque o endereço em `PAINEL_URL` e envie o arquivo de novo no GitHub. Se você só publicar uma *nova versão* da mesma implantação, o link continua o mesmo e nada precisa mudar aqui.
