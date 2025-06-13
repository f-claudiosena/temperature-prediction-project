# Weather Prediction Project 🌦️

Este projeto tem como objetivo prever a temperatura (em graus Celsius) com base em dados meteorológicos históricos. Utiliza-se análise exploratória, engenharia de atributos e modelos de Aprendizado de Máquina para construir predições robustas.

This project aims to predict temperature (in Celsius) based on historical weather data. EDA (Exploratory Data Analysis), feature engineering, and Machine Learning models are used to create robust predictions.

## Dataset
- Fonte: https://www.kaggle.com/datasets/muthuj7/weather-dataset?resource=download
- Variáveis: Formatted Date, Summary, Precip Type, Temperature (C), Apparent Temperature (C), Humidity, Wind Speed (km/h), Wind Bearing (degrees), Visibility (km), Loud Cover, Pressure (millibars), Daily Summary

## Tecnologias
- Jupyter Notebook, Python, Pandas, NumPy, Seaborn, Scikit-learn, Matplotlib

## Etapas
1. Análise Exploratória (EDA)
2. Pré-processamento
3. Modelagem com Regressão e Árvores
4. Avaliação e Conclusão

## Resultados
- Melhor modelo: Random Forest com R² = 0.9999639040310524
- Previsão de temperatura com MAE de 0.013685990086403319°C

Para fins comparativos, resultados do modelo Linear Regression:
- MAE: 0.7361419767448404
- R²: 0.9903127264263686
