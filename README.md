# Desafio-Ecommerce-DIO-SQL

### Projeto proposto pela professora Julia Mascarenhas da DIO.
Modelo conceitual de um banco de dados representando um E-Commerce, suas entidades e seus devidos relacionamentos.

#### Cliente

Representa o usuário que realiza compras no e-commerce.

Possui informações como nome, endereço e identificação.

Pode estar associado a um cadastro de Pessoa Física (PF) ou Pessoa Jurídica (PJ).

#### Cadastro (PF e PJ)

Armazena dados específicos para clientes que são Pessoa Física (CPF) ou Pessoa Jurídica (CNPJ).

Inclui informações como email e documentos de identificação.

#### Pedido

Representa uma compra feita pelo cliente.

Contém informações como status do pedido, descrição e o cliente responsável.

Está associado a produtos por meio da relação produto/pedido.

#### Pagamento

Contém os dados de pagamento do cliente, incluindo número do cartão e data de validade.

#### Entrega

Relaciona-se ao pedido e armazena informações sobre o status da entrega e código de rastreamento.

##### Produto

Representa um item disponível para compra.

Possui atributos como categoria, descrição, valor e identificação única.

#### Fornecedor

Empresa responsável pelo fornecimento de produtos.

Cada fornecedor pode disponibilizar vários produtos para venda.

#### Terceiro - Vendedor

Representa vendedores terceiros que oferecem produtos na plataforma.

Cada vendedor possui uma razão social e localização.

#### Estoque

Local onde os produtos estão armazenados.

Relaciona-se com produtos para controlar a quantidade disponível.

![Image](https://github.com/user-attachments/assets/490c1dec-c8c7-4a41-9fad-53857c60b862)
