
# 🎮 Meganium Games Insights

📦 Este projeto foi desenvolvido para consolidar e analisar os dados de vendas dos consoles portáteis da **Meganium Games** — uma fabricante fictícia.  
O objetivo principal é transformar dados transacionais recebidos de marketplaces parceiros em **insights acionáveis** para decisões de produção e logística.

---

## 🎯 Objetivos do Projeto

Consolidar as bases de dados das diferentes plataformas de vendas (**AliExpress, Etsy, Shopee**).

Analisar os dados de vendas para gerar insights relevantes para a fabricante.

**Identificar:**

- 🕹️ Produtos mais populares.
- 🌍 Regiões que mais compram.
- 📦 Possibilidades de otimização logística e de produção com base na demanda.

---

## 🧑‍💼 Público Alvo

- Manter uma estrutura clara entre dados brutos (`raw_data`) e dados processados (`processed_data`).
- Gerar insights objetivos e sem alucinação: **só com base no que existe nos dados.**

---

## 📁 Estrutura do Projeto

- `data/raw_data/` → Dados brutos recebidos dos marketplaces.
- `data/process_data/` → Dados tratados e consolidados.
- `insights/` → Relatórios e análises em Markdown.
- `prompts/` → Histórico de comandos e instruções usados com IA.

---

## 📌 Arquivos Relevantes

- 📄 [base_consolidada_vendas.xlsx](./data/process_data/base_consolidada_vendas.xlsx)
- 📊 [Analysis.md](./insights/Analysis.md)
- 🤖 [Prompts usados com IA](./prompts/GPT_DataSensei.md)

---

## 👨‍💻 Autor

Desenvolvido por **Brenda Lelis**  
Inspirado por boas práticas de **storytelling com dados** e pela abordagem prática defendida por **DJ Patil**.

---

![Status](https://img.shields.io/badge/Status-Conclu%C3%ADdo-green)
![Python](https://img.shields.io/badge/Python-3.9%2B-blue)
