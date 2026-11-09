# BESSA AI TRADER V2.0

## Novidades
- Radar com dados públicos de criptoativos via CoinGecko API.
- Busca por nome/símbolo, ordenação e paginação (até 250 ativos por consulta).
- Exibição em BRL (saldo virtual e preços na mesma moeda).
- Trading continua 100% simulado; saldo fictício em BRL.
- Posições e histórico armazenados localmente no navegador.

## Publicação pelo GitHub Pages
Substitua os arquivos `index.html`, `manifest.webmanifest`, `sw.js` e `icon.svg` na raiz do repositório. `README.md` é opcional. Faça Commit changes. O GitHub Pages republicará automaticamente.

## Limitações e segurança
- A API pública pode limitar ou recusar consultas (por exemplo, HTTP 429). Aguarde antes de tentar novamente.
- “Todos” significa o universo disponibilizado pela API e carregado em páginas; use Carregar mais para avançar. Não é uma lista literalmente ilimitada.
- Dados dependem do provedor, podem atrasar e não são garantidos.
- A aplicação não contém agentes de IA reais, não envia ordens a corretoras e não executa tarefas em segundo plano.
- O saldo virtual é local a este navegador e não sincroniza entre dispositivos.
- Nunca inclua chaves privadas/API secretas em JavaScript publicado publicamente.

## Fonte de dados
CoinGecko API: https://docs.coingecko.com/reference/coins-markets
