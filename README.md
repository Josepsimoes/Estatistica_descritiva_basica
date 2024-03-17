
# Análise Básica de Retornos Financeiros

Este é um projeto simples que demonstra como baixar dados financeiros do Yahoo Finance usando a biblioteca yfinance, calcular estatísticas descritivas básicas e visualizar os resultados por meio de gráficos interativos usando as bibliotecas matplotlib e plotly.

## Funcionalidades

- **download_data**: Função para baixar dados históricos de preços de ações do Yahoo Finance para um determinado ticker e intervalo de datas.
  
- **descriptive_statistics**: Função para calcular estatísticas descritivas básicas dos retornos financeiros, como média, mediana, desvio padrão, percentis, assimetria, curtose e p-valor do teste de Shapiro-Wilk para normalidade.

- **statistics_basic_view**: Função principal que encapsula o processo de baixar os dados, calcular estatísticas e visualizar os resultados através de gráficos interativos.

## Utilização

Para utilizar este projeto, basta chamar a função `statistics_basic_view()` com o ticker desejado e as datas de início e fim para obter uma análise básica dos retornos financeiros e visualizar os gráficos interativos.

```python
statistics_basic_view(ticker='AAPL', start_date='2020-01-01', end_date='2021-01-01')
```

## Requisitos

- Python 3.x
- Bibliotecas: yfinance, pandas, numpy, matplotlib, scipy, plotly, seaborn

## Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para abrir uma issue para relatar bugs ou sugerir novas funcionalidades. Pull requests também são encorajados.

