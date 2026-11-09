# BESSA AI TRADER — V1.0

Aplicativo web responsivo/PWA para painel e simulação local de operações.

## O que esta versão faz
- Dashboard mobile-first.
- Saldo virtual inicial de R$ 10.000.
- Simulador manual de compra e venda.
- Carteira e histórico salvos no navegador (`localStorage`).
- Interface conceitual para oito agentes.
- Instalação como atalho/aplicativo PWA em navegadores compatíveis.

## O que esta versão NÃO faz
- Não consulta preços reais.
- Não possui IA conectada.
- Não executa operações em corretoras.
- Não funciona como serviço garantido 24/7 em segundo plano.
- Não fornece recomendação de investimento.
- Não sincroniza automaticamente os dados entre aparelhos.

Os preços são ilustrativos e o saldo é fictício. Não use os resultados como previsão de retorno.

## Publicar gratuitamente pelo celular com GitHub Pages

1. Crie uma conta em https://github.com (se ainda não tiver).
2. Crie um repositório público chamado `bessa-ai-trader`.
3. Envie os arquivos desta pasta para a raiz do repositório:
   - `index.html`
   - `manifest.webmanifest`
   - `sw.js`
   - `icon.svg`
4. Abra **Settings → Pages** no repositório.
5. Em **Build and deployment**, selecione **Deploy from a branch**.
6. Escolha a branch `main` e a pasta `/ (root)`, depois salve.
7. Aguarde a publicação. O GitHub mostrará o endereço do site na página Pages.

## Instalar no Android
1. Abra o endereço publicado no Chrome.
2. Toque no menu de três pontos.
3. Escolha **Instalar app** ou **Adicionar à tela inicial**, se disponível.
4. Abra pelo ícone criado.

## Arquitetura planejada para versões futuras

- Frontend: PWA (HTML/CSS/JavaScript nesta primeira versão).
- Backend futuro: Python + FastAPI.
- Banco futuro: PostgreSQL.
- Processamento futuro: workers assíncronos.
- Dados futuros: APIs oficiais de provedores de mercado.
- IA futura: agentes separados para pesquisa, análise, estratégia, risco e auditoria.
- Execução futura: somente após backtesting, paper trading, revisão de segurança e validação regulatória.

## Segurança antes de qualquer integração financeira
- Nunca coloque chaves secretas de corretoras no código do navegador ou em repositório público.
- Não habilite permissão de saque em chaves de API.
- Não conecte esta versão a uma conta com dinheiro real.
- Mantenha execução real desabilitada por padrão.
