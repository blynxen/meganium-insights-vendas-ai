# 🖥️ Avaliação de Vendas:

## Os marketplaces com maior volume de vendas são:

🥇 Shopee: 64 unidades.

🥈 AliExpress: 58 unidades.

🥉 Etsy: 56 unidades.

Apesar da diferença ser pequena, a Shopee lidera em volume.

## 📊 Análises e Fórmulas

**3️⃣ Marketplace mais ativo**

Processo:

    df.groupby('Marketplace')['quantity'].sum().sort_values(ascending=False)

*O que faz:*

- Agrupa por origem da venda (Shopee, Etsy, etc).

- Soma todas as quantidades vendidas por plataforma.
