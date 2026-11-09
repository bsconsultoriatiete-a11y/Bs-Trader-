# BESSA AI TRADER V3.0

## V3.0 — Estratégias automáticas em paper trading
- Radar CoinGecko em BRL e USD.
- Módulos determinísticos: momentum/tendência, correção, liquidez, score, estratégia, risco e auditoria.
- Perfil equilibrado inicial.
- Execução automática opcional: análise imediata e ciclo de 15 minutos enquanto a página estiver aberta.
- Compra e venda exclusivamente simuladas.
- Gestão simulada: stop 3,5%, alvo 7%, exposição máxima 45%, até 5 posições, risco de alocação por posição limitado a 7% do patrimônio, limite diário 1,5%.
- Dados locais no navegador; saldo fictício de R$ 10.000.

## Importante
Os "agentes" são módulos algorítmicos determinísticos baseados em regras, não agentes de IA generativa nem modelos treinados. Os sinais são heurísticas ilustrativas, não estratégias comprovadas nem recomendação de investimento. Não há backtesting rigoroso, execução real, autenticação, servidor, sincronização ou monitoramento garantido 24/7.
A automação só roda enquanto a página está aberta e o navegador não suspende a aba. Em celular, o sistema operacional pode pausar a execução.
O feed público pode sofrer atraso, indisponibilidade e limites HTTP 429. O radar mostra ativos carregados (páginas de 250); o motor analisa os ativos atualmente carregados e prioriza até rank 500 quando disponíveis.
Nunca publique chaves secretas em JavaScript ou repositório público.

## Atualizar GitHub Pages
No repositório, substitua `index.html` e `sw.js` pelos arquivos desta versão; opcionalmente substitua `README.md`, `manifest.webmanifest` e `icon.svg`. Faça Commit changes e abra o site com `?v=3` para evitar cache. O service worker usa cache versionado V3.
