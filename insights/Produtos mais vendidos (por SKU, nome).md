# 💲 Avaliação de Vendas:

## Os produtos mais vendidos ordenados por quantidade total:

🥇 NEW MEGANIUM RG 40XXV (SKU-40XXV01) lidera com 41 unidades vendidas.

🥈 Empate técnico entre:

- NEW MEGANIUM RG28XX

- NEW MEGANIUM RG35XX

- NEW MEGANIUM RG CubeXX

Cada um com 36 unidades.

🥉 MEGANIUM RG353M vendeu 29 unidades.


##📊 Análises e Fórmulas

**1️⃣ Produto mais vendido**

Processo:

    df.groupby(['SKU', 'product_sold'])['quantity'].sum().sort_values(ascending=False)

*O que faz:*

- Agrupa os dados por produto e SKU.

- Soma a quantidade vendida (quantity) para cada grupo.

- Ordena do maior para o menor.

