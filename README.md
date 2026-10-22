# Alkance Resultados: site estático para a Vercel

Pasta pronta para publicar: `index.html` (site completo), `assets/` (imagens), `obrigado.html`, `vercel.json`.

## Publicar
1. Suba o conteúdo desta pasta em um repositório do GitHub (arquivos na raiz, sem pasta extra).
2. Na Vercel: Add New > Project > escolha o repositório.
3. Framework Preset: **Other**. Deixe Build Command e Output Directory em branco.
4. Deploy.

Rotas como `/blog/...` funcionam pelo `vercel.json` (todas as URLs caem no `index.html`, exceto `assets/`, `obrigado.html`, `favicon.ico` e `robots.txt`).
