# projeto-olist-harve

Esse projeto tem objetivo de realizar a analise de dados para o marketplace Olist e indentificar o motivo das quedras de suas vendas

# Perguntas de negócio que devem ser respodidas:

1 - Por que as vendas estão caindo?
2 - Quem são os melhores clientes?
3 - Entregas estão prejudicando satisfação e vendas?
4 - Quais categorias sustentam a receita?

# Hipóteses que foram levantadas para cada pergunta:
## 1 - Por que as vendas estão caindo?

# Tabelas do banco de dados
### Pedidos - olist_orders_dataset
- PK: order_id
- Campos de data: purchase, approved, delivered_customer_date
- Problemas encontrados: datas nulas, pedidos não entregues

### Itens do pedido - olist_order_items_dataset

### Pagamentos - olist_order_payments_dataset

### Avaliações dos pedidos - olist_order_reviews_dataset

### Clientes - olist_customers_dataset

### End entrega - olist_sellers_dataset

### Produtos - olist_products_dataset

### Geolocalização - olist_geolocation_dataset
