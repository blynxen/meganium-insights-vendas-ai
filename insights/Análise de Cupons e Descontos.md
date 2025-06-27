# 🎟️ Análise de Cupons de Desconto

## Todos os cupons foram utilizados uma única vez, o que indica que:

- São cupons únicos e personalizados (talvez gerados por campanhas específicas ou influenciadores).

- O valor do desconto varia bastante, indo de poucos até mais de 130 unidades monetárias.

## 📊 Análises e Fórmulas

**5️⃣ Análise de Cupons e Descontos**

Processo:
 
    df.groupby('discount_coupon').agg( total_uso=('discount_coupon', 'count'), total_desconto=('discount_value', 'sum') )

*O que faz:*

- Agrupa por cupom de desconto.

- Conta quantas vezes cada cupom foi usado.

- Soma o valor total concedido em desconto.
