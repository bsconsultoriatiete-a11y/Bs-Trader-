# BESSA AI TRADER V3.1

## Correções
- Migra a carteira local V3 existente sem apagar saldo, posições ou histórico.
- Não religa a automação sozinha após recarregar.
- Exibe preço de entrada com até 10 casas decimais, evitando mostrar PEPE como R$ 0,00.
- Exibe resultado não realizado por posição.
- Registra preço e taxa fictícia por operação.
- Taxa simulada: 0,10% por lado.
- Calcula preço de entrada incluindo taxa simulada de compra.
- Ao atingir limite diário, bloqueia novas compras, mas continua avaliando e gerenciando posições abertas.
- Stop e alvo são avaliados quando uma nova consulta de mercado ocorre; não são garantidos em tempo real.
- Carteira e histórico ficam no armazenamento local do navegador.

## Limitações
O sistema continua sendo paper trading, sem corretora, sem ordens reais e sem IA generativa. O motor usa regras determinísticas e preços públicos CoinGecko. Automação apenas enquanto a página está aberta e o navegador não suspende a aba. Sem garantia de execução 24/7.
A taxa de 0,10% é uma hipótese configurável no código, não representa a taxa de uma corretora específica. Slippage e spread não são modelados nesta versão.
