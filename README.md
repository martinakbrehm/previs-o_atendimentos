# Previsão de atendimentos individuais

Este projeto tem como objetivo prever o volume de atendimentos médicos individuais na cidade de Florianópolis, utilizando dados históricos e técnicas de modelagem de séries temporais. Com base em uma série histórica de 60 meses, abrangendo o período de 2019 a 2023, aplicamos os modelos ARIMA e SARIMA para prever os atendimentos médicos no ano de 2024.

## Metodologia
Para a construção dos modelos, utilizamos o algoritmo auto_arima, que automatiza o processo de seleção dos melhores hiperparâmetros para os modelos ARIMA e SARIMA. A seguir estão os hiperparâmetros selecionados:

Modelo ARIMA: (1,1,0)
Modelo SARIMA: (0,1,0)(0,1,1)[12]

## Dados
Os dados utilizados neste projeto consistem em uma série temporal de atendimentos médicos mensais, totalizando 60 meses de registros, de 2019 a 2023

## Modelos Utilizados
ARIMA (AutoRegressive Integrated Moving Average): Um modelo de série temporal utilizado para capturar a autocorrelação entre os dados ao longo do tempo

SARIMA (Seasonal ARIMA): Um modelo ARIMA expandido para incluir padrões sazonais, especialmente útil em séries temporais com comportamento periódico
