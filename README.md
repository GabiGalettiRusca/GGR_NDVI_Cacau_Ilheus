🌿 NDVI_Cacau_Ilheus

Este repositório contém os códigos e dados utilizados para a análise da estabilidade interanual do NDVI em áreas de cultivo sombreado de cacau no município de Ilhéus (BA), no período de 2019 a 2023. A investigação busca compreender aspectos da resiliência ecológica dessas áreas frente a distúrbios ambientais e climáticos.

🛰️ Código 1 – Análise Interanual do NDVI em Cacau Sombreado (2019–2023)
Arquivo: NDVI_Ilheus_Cacau.ipynb

🎯 Objetivo
Avaliar a estabilidade interanual do índice NDVI em áreas classificadas como cacau sombreado no município de Ilhéus, como forma de inferir sobre a resiliência ecológica desses sistemas agroflorestais ao longo de cinco anos.

🗂️ Fonte dos Dados
MapBiomas Cacau (2019–2023): Delimitação das áreas de cultivo sombreado de cacau.

Sentinel-2 Surface Reflectance (COPERNICUS/S2_SR): Imagens orbitais nível 2A, via Google Earth Engine (GEE).

IBGE (shapefile): Delimitação municipal de Ilhéus, Bahia.

🔍 Etapas Principais
Definição da área de estudo (Ilhéus, BA);

Extração das áreas de cacau sombreado com base no MapBiomas Cacau;

Cálculo do NDVI médio por ano para o período seco (julho a outubro), com filtro de nuvens;

Geração de tabelas, gráficos e mapas temáticos para avaliação de tendência e variabilidade;

Aplicação de métricas: média, desvio padrão e coeficiente de variação (CV%).

📈 Resultados Esperados
Tabela com valores anuais de NDVI médio, desvio padrão e CV;

Gráfico de linha representando a estabilidade interanual da vegetação;

Mapas comparativos e individuais do NDVI anual com sobreposição das áreas de cacau sombreado.

🌎 Mapas e Visualizações
Mapas anuais do NDVI (2019, 2020, 2021, 2023) com contorno sutil das áreas de cacau sombreado;

Mapa comparativo (subplot) com os 4 anos lado a lado, destacando padrões espaciais;

Gráfico temporal com NDVI médio e faixa de desvio padrão.

🧠 Integração e Interpretação
A análise permite avaliar a persistência da cobertura vegetal em áreas de SAFs com cacau sombreado, identificando flutuações interanuais no vigor vegetativo e potenciais impactos de eventos climáticos. Essa abordagem contribui para o monitoramento de resiliência ecológica em paisagens produtivas da Mata Atlântica.

📚 Referências principais
Holling, C. S. (1973). Resilience and stability of ecological systems. Annual Review of Ecology and Systematics.

Pettorelli et al. (2005). Using NDVI to assess ecological responses. Trends in Ecology & Evolution.

MapBiomas Cacau (2020, 2023). Relatórios técnicos e mapeamento da cacauicultura sombreada.

Smith & Boers (2023); Ma et al. (2023); Yengoh et al. (2015).
