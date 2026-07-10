# StatS — versão modular para GitHub

Esta versão mantém a aplicação com o mesmo aspeto e funcionamento, mas separa o ficheiro único em estrutura de projeto.

## Estrutura

- `index.html` — estrutura da página
- `css/style.css` — todo o design
- `js/app.js` — lógica principal original
- `js/modules/` — ficheiros preparados para futuras alterações específicas

## Como publicar no GitHub

1. Abre o ZIP.
2. Envia para o repositório todos os ficheiros e pastas.
3. O ficheiro principal continua a ser `index.html`.

## Como editar daqui para a frente

- Dashboard Individual → `js/modules/dashboardIndividual.js`
- Dashboard Coletivo → `js/modules/dashboardColetivo.js`
- Heat Map → `js/modules/heatmap.js`
- Minutos → `js/modules/minutos.js`
- Jogo/marcador/arena → `js/modules/jogo.js`
- Treino → `js/modules/treino.js`
- Visual/design → `css/style.css`

Nesta primeira fase, a lógica original foi mantida em `js/app.js` para garantir estabilidade.
