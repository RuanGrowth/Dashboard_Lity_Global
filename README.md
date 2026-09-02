# Dashboard Lity Global — Bursty

Dashboard de performance (Meta Ads, Google Ads, Instagram e Operações/Jira)
do cliente **Lity Global**, em arquivo único (`index.html`).

Lê os dados no navegador, direto das planilhas do Google Sheets publicadas em CSV
(base geral da Bursty), filtrando pelo Lity. O `server.js` só entrega o HTML.

> IMPORTANTE: todos os arquivos precisam ficar na RAIZ do repositório.

## Publicar no Railway
1. New Project -> Deploy from GitHub repo -> selecione o repositório.
2. O Railway usa o Dockerfile e roda node server.js.
3. Settings -> Networking -> Generate Domain.
