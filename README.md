# Predição de índice Pluviometrico de Macapá
Predição de índices pluviométricos da cidade de Macapá é um dos modelos que usamos para um projeto um pouco maior e foi uma das abordagem usadas e que resolvi 
compartilhar.

# Abordagem utilizada 
Para prever o indice pluviometrico partimos usando abordagem de series temporais, modelos arvores e gradient boosting. Para isso usamos algumas métricas para avaliar o desempenho do modelo, como o: Score, RMSE e K-fold

# Modelos usados
- Random Forest
- XGBoost
- LightGBM

# Tecnologias
- Python 
- pandas e numpy
- matplotlib e seaborn
- Xgboost 
- Sklearn 
- Lightgbm

# Fontes de Dados
Os dados equivalem ao intervalo de 2000 a 2020 e estão disponiveis no portal do INMET: https://portal.inmet.gov.br/

# Descrição das features do dataset
data - 'Data',
hora - 'Hora (UTC)',
temperatura - 'Temp. [Hora] (C)', 
umidade - 'Umi. (%)',
pressao - 'Pressao (hPa)',
vel_vento - 'Vel. Vento (m/s)', 
direcao_vento - 'Dir. Vento (m/s)', 
nebulosidade - 'Nebulosidade (Decimos)',
insolacao - 'Insolacao (h)',
temp_max - 'Temp. Max. [Diaria] (h)',
temp_min -'Temp. Min. [Diaria] (h)',
precipitação - 'Chuva [Diaria] (mm)'
