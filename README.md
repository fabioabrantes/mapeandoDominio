# mapeandoDominio
## Desafio: https://efficient-sloth-d85.notion.site/Atividade-Mapeando-o-dom-nio-38963358ffd74289b824ff73b187165d
### Quais entidades do Domínio?
Com base na conversa entre o desenvolvedor e o especialista de domínio sobre o sistema de gerenciamento de estoque, consegui identificar as seguintes entidades de domínio com suas possíveis propriedades: Caso contenha outros me informar como feedback.
- Produto: tem atributos como nome, descrição, tamanho, cor, e um número de identificação único.
- Registro de Estoque: contém informações como a quantidade, data e motivo da movimentação (por exemplo, venda, reposição de estoque).
- Limite Mínimo de Estoque: número mínimo de cada produto 
- Alerta de Estoque: contém um identificador gerado ando a quantidade de um produto no estoque fica abaixo do limite mínimo.
- Histórico de Vendas: contendo informações como quantidades vendidas, preços de venda e datas de venda.
- Pedido de compra dos produtos. Pode incluir informações como fornecedor, produtos a serem comprados e quantidades.
- Fornecedor: Pode incluir informações como nome, contato e detalhes de entrega.


### Quais as ações (casos de uso) que essa aplicação deve ter?
Consegui identificar os seguintes casos de uso (ações): : Caso contenha outros me informar como feedback.

-	Registrar Movimentação de Estoque
-	cadastrar o limite mínimo de estoque para cada produto.
-	Receber alertas quando a quantidade de um produto no estoque atingir ou ficar abaixo do limite mínimo definido. 
-	buscar relatório de vendas por período (por exemplo, diário, semanal, mensal).
-	buscar lucro gerado por produto.
-	buscar produtos mais vendidos em cada período.
-	buscar tendências de estoque ao longo do tempo.
-	Solicitar pedidos de compra automaticamente com base nos limites mínimos de estoque e nas tendências de vendas.
-	buscar e editar pedidos de compra existentes.
-	remover pedidos de compra.
-	Receber atualizações automáticas sobre prazos de entrega de novas remessas.
-	Sincronizar informações de produtos e estoque com os fornecedores.
-	Adicionar, editar e excluir informações de produtos.
-	Adicionar, editar e excluir informações de fornecedores.

