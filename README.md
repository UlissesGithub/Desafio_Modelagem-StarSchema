# Desafio_Modelagem-StarSchema
Desafio_Modelagem StarSchema

- Modificações Feitas
- Adicionado Tabelas Dimensoões "D_Produtos", "D_Descontos", "D_Categoria", "D_Produtos_Detalhes", "D_Detalhes" e D_Calendário
- Criando tabela fato "F_Vendas"
- Em "D_Produtos", adicionado Índice (para referenciar ID_Produto) e criado agrupamento com Média de Unidades Vendidas, Médias do valor de vendas, Mediana do valor de vendas, Valor máximo de Venda e Valor mínimo de Venda
  
- Em "D_Descontos" removida colunas "Segment", "Country", "Units Sold", "Manufacturing Price", "Sale Price", "Gross Sales", " Sales", "COGS", "Profit", "Date", "Month Number", "Month Name" e "Year". Diplicatas removidas
  
- Em "D_Categoria" removida colunas "Product", "Discount Band", "Units Sold", "Manufacturing Price", "Sale Price", "Gross Sales", "Discounts", " Sales", "COGS", "Profit", "Date", "Month Number", "Month Name" e "Year"

- Em "D_Produtos_Detalhes"  adicionado Índice (para referenciar ID_Produto) e removida colunas "ID_Produto", "Product", "Discount Band", "Units Sold", "Manufacturing Price" e "Sale Price"

- Em "D_Detalhes" removida colunas "Segment", "Country", "Discount Band", "Units Sold", "Manufacturing Price", "Sale Price", "Discounts", "Date", "Month Number", "Month Name" e "Year"

- Em D_Calendário, foi criado a partir do DAX
