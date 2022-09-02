# DIO Desafio MySQL E-Commerce EER
Repositório para entrega do desafio.

## Contexto do Desafio.
Criar um modelo conceitual de modelagem de banco de dados para um E-commerce.

### Produtos
* Os produtos são vendidos em uma única plataforma on-line, contudo
podem ter vendedores distintos (terceiros).
* Cada produto possui um fornecedor.
* Um ou mais produtos podem compor um pedido.

### Cliente
* O cliente pode ser pessoa Física ou Jurídica.
* O endereço do cliente determinará o valor do frete.
* Um cliente pode fazer mais de um pedido, o mesmo tem um 
período de carência para devolução do produto.
* Cada cliente pode ter mais de cartão como forma de pagamento.

### Pedidos
* Os pedidos são criados por clientes e possuem irformações de compra,
endereço e estatus da entrega.
* Um produto ou mais compoem o pedido.
* O pedido pode ser cancelado.

### Fornecedor
* Um ou mais produtos podem ser fornecidos por um ou mais fornecedores.
* Vendedores terceiros fornecem seus próprios produtos.
