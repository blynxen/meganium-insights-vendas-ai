# 🎯 Avaliação de Público Alvo:

## O perfil dos compradores por país, com base nas vendas:

- As idades médias variam entre ~35 e ~44 anos, indicando um público majoritariamente adulto.

- Canadá teve a maior quantidade de vendas, com compradores entre 19 e 48 anos.

- França, Inglaterra, Japão e Austrália também apresentam idades médias acima dos 40 anos.

## 📊 Análises e Fórmulas

**4️⃣ Perfil dos compradores (idade)**

Processo:
 
  🧓 Fórmula de Idade:

    df['buyer_age'] = df['date'].dt.year - df['buyer_birth_date'].dt.year
  
  🔍 Análise

    df['buyer_age'] = df['date'].dt.year - df['buyer_birth_date'].dt.year

*O que faz:*

- Agrupa por país.

- Calcula: total de vendas, idade média, mínima e máxima.
