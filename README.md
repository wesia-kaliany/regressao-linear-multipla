# Regressão Linear Múltipla

Este projeto reúne exercícios de regressão linear múltipla desenvolvidos no Google Colab com Python, usando as bibliotecas `pandas`, `numpy` e `statsmodels`. O objetivo é praticar a construção de modelos estatísticos que estimam uma variável quantitativa (y) a partir de duas ou mais variáveis explicativas (x), além de aprender a interpretar os resultados e usar o modelo para fazer previsões.

## Sobre os exercícios

O projeto traz dois casos práticos, baseados em situações reais de negócio:

- **Vendas de videogame:** uma empresa que produz jogos deseja estimar o volume de vendas em diferentes cidades a partir do número de clientes menores de 16 anos e da renda per capita de cada cidade.
- **Faturamento de um cinema:** o proprietário de um cinema (Showtime Movie Theater, Inc.) quer estimar o faturamento bruto semanal com base nos gastos em publicidade, divididos entre anúncios de televisão e de jornal.

## O que foi feito

Em cada caso, o notebook segue as mesmas etapas:

1. Organização dos dados em um `DataFrame` com o pandas.
2. Ajuste do modelo de regressão linear múltipla pelo método dos mínimos quadrados (OLS).
3. Análise dos resultados: coeficientes, R², R² ajustado e demais métricas do `summary()`.
4. Aplicação do modelo a um exemplo de previsão, mostrando na prática como a equação estima o valor de y.


