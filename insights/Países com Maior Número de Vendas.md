# Avaliação de Vendas:

## Países com Maior Número de Vendas:

Esses são os principais países por volume de vendas:

🔴 Canadá lidera com 46 unidades.

⚪ França vem em seguida com 36.

🔵 Austrália, ⚪ Japão e ⚫ Alemanha também se destacam.


## 📊 Análises e Fórmulas

**2️⃣ Países com Maior Número de Vendas**

Processo:

    df.groupby('delivery_country')['quantity'].sum().sort_values(ascending=False)

*O que faz:*

- Agrupa por país de entrega.

- Soma a quantidade vendida por país.

- Ordena os países que mais compraram.
