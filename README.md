# 📊 Alura Store BR — Análise de Desempenho das Lojas

Este projeto realiza uma análise de dados das lojas da rede **Alura Store Brasil**, com o objetivo de avaliar seu desempenho e oferecer uma recomendação estratégica sobre qual unidade deve ser vendida para otimizar os resultados da empresa.

A análise foi desenvolvida em um notebook Jupyter utilizando **Python** e a biblioteca **Pandas** para tratamento e visualização dos dados.

---

## 🎯 Objetivo

Analisar, a partir de dados reais das lojas, diferentes métricas de desempenho, como:

* Faturamento total
* Vendas por categoria
* Média de avaliação dos clientes
* Custo médio do frete

Com base nesses dados, é feita uma recomendação final sobre qual loja apresenta o **menor desempenho geral**.

---

## 📁 Estrutura do repositório

* `AluraStoreBr_LeticiaSFMachado.ipynb` — Notebook com toda a análise
* `README.md` — Descrição do projeto (este arquivo)

---

## 🧪 Etapas da análise

O projeto foi dividido nas seguintes etapas principais:

### ✅ 1. Importação dos dados

Foram utilizados arquivos CSV disponibilizados via URL, um para cada loja.

### ✅ 2. Análise do faturamento

Foi calculado e comparado o faturamento total de cada loja, além da visualização do percentual de contribuição de cada uma no total da rede.

### ✅ 3. Vendas por categoria

As categorias de produtos mais e menos vendidas em cada loja foram analisadas, destacando:

* **Mais vendidas**: Eletrônicos e Eletrodomésticos
* **Menos vendidas**: Brinquedos infantis

### ✅ 4. Média de avaliação dos clientes

Foi calculada a média de avaliação de cada loja com base nas avaliações dos consumidores.

### ✅ 5. Frete médio

O custo médio do frete por loja também foi analisado para verificar possíveis impactos no desempenho.

---

## 📌 Principais resultados

* As **Lojas 2 e 3** apresentam desempenho equilibrado e as **melhores avaliações**, não sendo consideradas para venda.
* A **Loja 1** possui o **maior faturamento**, porém tem a **menor média de satisfação dos clientes** e o **frete médio mais alto**.
* A **Loja 4** apresenta:

  * O **menor faturamento da rede**
  * A **segunda menor média de avaliação**

➡️ **Recomendação final:** Com base nos dados analisados, é recomendada a **venda da Loja 4**, pois ela apresenta o pior desempenho geral.

---

## 🛠️ Tecnologias utilizadas

* Python 3
* Pandas
* Matplotlib
* Jupyter Notebook

---





