# Gráficos do e-commerce

Atividade do curso de Análise de Dados da EBAC. Peguei a base de produtos de e-commerce dos exercícios anteriores e montei alguns gráficos para entender melhor como estão os preços, os descontos, as avaliações e as vendas.

## O que tem na pasta

- `analise_graficos_ecommerce.ipynb`: o notebook com o código e os gráficos
- `ecommerce_estatistica.csv`: a base de dados (295 produtos)

## Gráficos que fiz

- Histograma dos preços
- Dispersão de preço x desconto
- Mapa de calor com a correlação entre as variáveis numéricas
- Barras com as 10 marcas que mais têm produtos
- Pizza com a divisão por gênero
- Densidade do preço de produtos masculinos e femininos
- Regressão de número de avaliações x quantidade vendida

## O que deu pra perceber

- A maioria dos produtos custa entre R$ 50 e R$ 200, e os preços se juntam em dois grupos: um perto de R$ 60 e outro perto de R$ 130.
- O desconto quase não tem relação com o preço (correlação de uns 0,16).
- Quem tem mais avaliações vende mais (correlação de uns 0,91). Isso mostra que as duas coisas andam juntas, mas não que uma causa a outra.
- A Lupo é a marca com mais produtos no catálogo.
- Os produtos masculinos são mais caros em média: cerca de R$ 155, contra R$ 105 dos femininos.

## Como rodar

Precisa ter Python instalado. Depois:

```
pip install pandas numpy matplotlib seaborn jupyter
jupyter notebook analise_graficos_ecommerce.ipynb
```

É só executar as células em ordem. O CSV tem que ficar na mesma pasta do notebook.

Feito com Python, pandas, numpy, matplotlib e seaborn.
