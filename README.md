# Cabana TCH — Simulador de hospedagem

Calculadora de receita bruta mensal com seis modelos de chalés, quantidades de unidades, diárias editáveis e calendários independentes.

## App

Hospedado no GitHub Pages, com instalação como PWA em navegadores compatíveis. No iPhone, abra no Safari e escolha Compartilhar → Adicionar à Tela de Início.

Após o primeiro carregamento, aguarde a mensagem de disponibilidade offline. As seleções permanecem apenas durante a sessão; fechar ou recarregar reinicia a simulação. As fontes externas podem usar a fonte alternativa quando não houver conexão.

## Publicação

GitHub Pages publica a raiz da branch `main`. Alterações nessa branch geram uma nova publicação. O arquivo `.nojekyll` permite servir os arquivos estáticos diretamente.

- `index.html`: interface e marca.
- `style.css`: visual e responsividade.
- `app.js`: cálculos, fotos incorporadas e interações.
- `pwa.js`: instalação do aplicativo.
- `manifest.webmanifest`: identificação e ícones.
- `sw.js`: cache offline; aumente a versão de `CACHE` quando atualizar arquivos.

Não há dependências de compilação nem servidor de aplicação. Para desenvolvimento, sirva esta pasta por HTTP local; service workers exigem HTTPS ou localhost.

Os resultados não descontam despesas, taxas ou impostos e não representam lucro ou garantia de ocupação.
