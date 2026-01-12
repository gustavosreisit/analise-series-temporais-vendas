# analise-series-temporais-vendas
Análise de séries temporais de vendas usando SQL, Python e Power BI para identificação de tendências e sazonalidade.

# 📊 Análise de Séries Temporais de Vendas

## 📌 Descrição do Projeto

Este projeto tem como objetivo analisar a evolução das vendas ao longo do tempo, identificando **tendências**, **sazonalidades** e **padrões relevantes** que possam apoiar a tomada de decisão em um contexto de negócio.

A análise utiliza uma abordagem ponta a ponta, passando por **extração e tratamento de dados**, **consultas SQL**, **análise em Python** e **visualização em Power BI**, simulando um cenário real de trabalho para um Analista de Dados.

---

## 🎯 Problema de Negócio

Empresas precisam entender como suas vendas evoluem ao longo do tempo para:

* Identificar meses de alta e baixa performance
* Detectar tendências de crescimento ou queda
* Planejar estoque, campanhas e metas futuras

Este projeto responde perguntas como:

* As vendas estão crescendo ao longo do tempo?
* Existem padrões sazonais?
* Quais meses apresentam melhor e pior desempenho?

---

## 🗂️ Fonte dos Dados

* **Dataset:** Sample Superstore Sales Dataset (dados de vendas de uma empresa fictícia)
* **Origem:** Kaggle
* **Período analisado:** 2014 a 2017
* **Granularidade:** pedidos individuais com data de pedido

O dataset contém informações como:

* Data do pedido
* Categoria e subcategoria de produtos
* Região
* Quantidade vendida
* Vendas e lucro

> ⚠️ Observação: Os dados são públicos, amplamente utilizados para fins educacionais e representam um cenário fictício de negócio.

---

## 🛠️ Ferramentas Utilizadas

* **SQLite** — armazenamento e consultas SQL
* **Python** — análise de dados e séries temporais

  * pandas
  * numpy
  * matplotlib / seaborn
  * statsmodels *(opcional)*
* **Power BI** — visualização e storytelling
* **Git & GitHub** — versionamento e portfólio

---

## 🧱 Estrutura do Projeto

```text
analise-series-temporais-vendas/
│
├── data/
│   └── vendas.csv
│
├── sql/
│   └── consultas.sql
│
├── notebooks/
│   └── analise_series_temporais.ipynb
│
├── powerbi/
│   └── dashboard.pbix
│
└── README.md
```

---

## 🔎 Metodologia

### 1️⃣ Coleta e Preparação dos Dados

* Importação do dataset
* Tratamento de datas
* Verificação de valores nulos e inconsistências

### 2️⃣ Análise com SQL (SQLite)

* Agregação de vendas por mês
* Cálculo de métricas como:

  * Total de vendas
  * Média mensal
  * Crescimento mês a mês

### 3️⃣ Análise de Séries Temporais (Python)

* Conversão dos dados para frequência mensal
* Visualização da evolução das vendas
* Aplicação de médias móveis
* Identificação de tendência e sazonalidade

### 4️⃣ Visualização e Storytelling (Power BI)

* Dashboard interativo
* Comparação de períodos
* Destaques de performance

---

## 📈 Principais Análises Realizadas

* Evolução mensal das vendas ao longo do período analisado
* Identificação de tendência geral de crescimento ou queda
* Análise de sazonalidade ao longo dos anos
* Identificação dos meses com maior e menor volume de vendas
* Comparação de desempenho entre anos

*(Adicionar prints do notebook Python e do dashboard Power BI aqui)*

---

## 💡 Insights e Conclusões

* Observa-se uma **tendência geral de crescimento** nas vendas ao longo do período analisado
* Alguns meses apresentam **picos recorrentes de vendas**, indicando possível sazonalidade
* Determinados períodos do ano concentram quedas de desempenho, sugerindo oportunidades para campanhas ou ajustes estratégicos

Esses insights podem apoiar decisões como:

* Planejamento de campanhas promocionais em meses estratégicos
* Ajuste de metas comerciais com base em sazonalidade
* Melhor gestão de estoque e logística

---

## 📌 Próximos Passos

* Aplicar decomposição de séries temporais (tendência, sazonalidade e ruído)
* Criar previsões simples de vendas utilizando modelos estatísticos
* Aprofundar a análise por categoria ou região
* Comparar vendas mês a mês (MoM) e ano contra ano (YoY)

---

## 👤 Autor

**Gustavo Silva Reis**
Analista de Dados em formação
[LinkedIn](coloque-seu-link) | [GitHub](coloque-seu-link)

---

## 📄 Licença

Este projeto é de uso educacional e demonstrativo.
