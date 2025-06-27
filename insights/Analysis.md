# Limpeza dos Dados

## ✅ Limpeza – Diagnóstico Inicial

**Sem valores nulos: Todas as colunas têm dados completos.**

## Tipos de dados a ajustar:

- date e buyer_birth_date estão como texto e precisam ser convertidos para datetime.

## To-Do:

- Converter essas colunas para o tipo datetime.

**Adicionar colunas derivadas úteis:**

- year, month da data de venda.

- buyer_age: idade do comprador no momento da compra.

**Conversão de datas:**

       pd.to_datetime(df['date'], errors='coerce')
       
**Criação de colunas derivadas:**

      df['month'] = df['date'].dt.month
      df['year'] = df['date'].dt.year


## Dados prontos para análise com as seguintes melhorias:

**✅ Datas convertidas corretamente (date, buyer_birth_date).**

**🗓️ Colunas derivadas:**

- year: ano da venda.

- month: mês da venda.

- 👤 buyer_age: idade estimada do comprador no momento da compra.

## 📊 Análises Exploratórias:

1. Produtos mais vendidos (por SKU, nome).

2. Países com maior volume de vendas.

3. Marketplace mais ativo.

4. Perfil dos compradores (idade, país).

5. Impacto dos cupons e descontos.

## 🛠️ Tecnologias e Bibliotecas Utilizadas

- Linguagem: Python

**Bibliotecas:**

- pandas – para manipulação e análise de dados tabulares.

- datetime – para cálculo de idade.

- ace_tools.display_dataframe_to_user() – usado pela IA para apresentar as tabelas de forma interativa na interface.
