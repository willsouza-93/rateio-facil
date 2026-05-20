# Changelog

## v1.2.0 - 2026-05-20
- Adicionado tutorial guiado de primeiro acesso com destaque visual em 9 etapas.
- Adicionado botão discreto **Ver tutorial** para reabrir o guia a qualquer momento.
- Tutorial passa a ser exibido automaticamente apenas no primeiro acesso e salva estado no `localStorage`.
- Implementado fluxo de atualização de PWA com aviso de nova versão e ação de atualização.
- Service Worker atualizado para suportar mensagem `SKIP_WAITING`.
- Cache do PWA incrementado para `rateio-pwa-v9`.

## v1.1.0 - Histórico de PRs anteriores
- Melhorias incrementais na experiência de uso e estabilidade da interface.
- Ajustes de layout responsivo e refinamentos visuais.
- Evoluções na persistência local para manter os dados no navegador.

## v1.0.0 - Primeira versão
- Cadastro e gestão de pessoas participantes do rateio.
- Criação de notas/compras com indicação de quem pagou.
- Adição de itens por nota com suporte a item de rateio e item pessoal.
- Cálculo automático de totais e da parcela de cada pessoa.
- Geração de resumo com:
  - quem paga para quem;
  - quanto cada pessoa paga/recebe;
  - detalhamento dos itens por nota.
- Impressão de relatório consolidado.
- Aplicação como PWA com suporte offline e cache local.
- Persistência dos dados no `localStorage`.
