# Classificador Pluviometrico de Macapá
Objetivo do projeto é disponibilizar classificadores que possibilitam prever em cada 6h se não havera chuva ou se tiver dize se a chuva sera fraca, moderada, forte ou violenta.

# Abordagem utilizada 
As etapas do projeto passaram desde de analise exploratoria, testes estatisticos de normalidade, limpeza de dados, feature engineer e treinamento do modelo o para avaliar usamos a validação cruzada com k-fold para olhar de perto as metricas de classficação

# Modelos usados
- Regressão Logistica
- MLP
- Arvore de Decisão
- CatBoost
- XGBoost
- LightGBM

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
