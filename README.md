# Série temporal de Risco de Fogo no Brasil 

Análise da série temporal da média de riscos de fogos diariamente no Brasil no ano de 2024. O cálculo do Risco de Fogo leva em conta os seguintes fatores:
- Quantidade de dias seguidos sem chuva.
- Os efeitos do tipo e do ciclo natural de desfolhamento da vegetação.
- Temperatura máxima e umidade relativa mínima do ar diárias.
- Presença de fogo no local de interesse.

No processo de modelagem foram utilizados os modelos SARIMA, SARIMAX e Redes Neurais Long short-term memory (LSTM).
Os dados foram disponibilizados pelo Instituto Nacional de Pesquisas Espaciais (INPE) e podem ser acessados na seguinte fonte: **https://www.kaggle.com/datasets/mayaravalliero/fire-watch-brazil-2024**.

Caso queira editar diretamente o notebook é possível acessar pela plataforma Kaggle no seguinte link: https://www.kaggle.com/code/jairsouza/serie_temp_fogos
