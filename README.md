# Radar de Criativos da Qive

Dashboard de criativos de mídia paga, em projeto independente do relatório Paid & Not Paid.

## Abrir

O dashboard está em `index.html`. Pode ser baixado e aberto em uma versão atual do Chrome, Edge ou Firefox. Dados e miniaturas incorporados funcionam sem servidor.

Para disponibilizar como site, configure Settings > Pages > Deploy from a branch > main > / (root).

## Dados e cobertura

- Base Meta consultada em 26/10/2026: 6.737 anúncios cadastrados, incluindo ativos, pausados, arquivados e excluídos.
- Histórico diário desde 01/01/2026 até 26/10/2026. O último dia estava em andamento.
- 6.528 anúncios com miniatura incorporada; 209 com recuperação pendente.
- Google e LinkedIn: importação manual. Nenhum total de conta é inferido dos dados importados.
- MQL, SQL, NB e NMRR exigem atribuição validada. Ausência de dado não representa zero.
- Diferenças de conciliação e limites da cobertura estão indicados no dashboard.

## Recursos

Filtros, mural paginado, tabela de métricas, comparação de períodos, importação de dados e miniaturas e exportação do HTML atualizado.

A rotina Meta percorre páginas e consulta o histórico. Novas consultas exigem credencial própria, utilizada apenas em memória. O HTML não inclui token e não atualiza em segundo plano.

## Formato

Arquivo HTML autônomo com imagens deduplicadas e dados comprimidos. A compactação preserva os registros e as imagens da base original.
