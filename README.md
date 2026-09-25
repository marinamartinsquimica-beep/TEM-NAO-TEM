# Tem · Não Tem — Sala de Ovos

Painel HTML para comparar pedidos com o estoque embalado por SKU e data de postura.

## Como usar

1. Abra `index.html` no navegador.
2. Selecione a planilha de pedidos (aba **Resumo**) e a planilha de estoque (aba **Estoque**).
3. Clique em **Comparar pedidos e estoque**. O `+` abre as posturas máximas por SKU e os lotes reservados.
4. Se quiser, clique em **Baixar resultado em Excel**. A aba **A Produzir** contém as faltas por SKU e postura máxima.

Uma caixa atende ao pedido quando sua postura é igual ou posterior à data máxima exigida. O mesmo saldo não é reservado duas vezes. As planilhas são processadas no próprio navegador; o HTML inclui a biblioteca necessária para ler e exportar Excel e funciona sem conexão à internet.
