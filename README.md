# Análise Gráfica de Produtos de E-commerce

Projeto do curso de Análise de Dados (EBAC). O objetivo é criar gráficos a partir de um conjunto de dados de produtos de e-commerce para extrair informações úteis para o cliente.

## Conteúdo

| Arquivo | Descrição |
|---------|-----------|
| `analise_graficos_ecommerce.ipynb` | Notebook com a análise e os 7 gráficos |
| `ecommerce_estatistica.csv` | Base de dados (295 produtos, 24 colunas) |

## Gráficos criados

1. **Histograma**: distribuição dos preços
2. **Dispersão**: preço × desconto
3. **Mapa de calor**: correlação entre variáveis numéricas
4. **Barras**: top 10 marcas por quantidade de produtos
5. **Pizza**: participação por gênero
6. **Densidade**: preço de produtos masculinos × femininos
7. **Regressão**: número de avaliações × quantidade vendida

## Principais descobertas

- A maioria dos produtos custa entre R$ 50 e R$ 200.
- O desconto praticamente não depende do preço (correlação ≈ 0,16).
- Número de avaliações e quantidade vendida têm correlação muito forte (≈ 0,91).
- A marca Lupo é a que mais aparece no catálogo.
- Produtos masculinos têm preço médio maior que os femininos.

## Como executar

1. Instale as bibliotecas: `pip install pandas numpy matplotlib seaborn jupyter`
2. Abra o notebook: `jupyter notebook analise_graficos_ecommerce.ipynb`
3. Execute as células em ordem (Kernel → Restart & Run All).

> O arquivo CSV precisa estar na mesma pasta do notebook.

## Tecnologias

Python, pandas, numpy, matplotlib e seaborn.
