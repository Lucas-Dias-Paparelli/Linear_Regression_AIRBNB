# Linear_Regression_AIRBNB

1. Introdução
   
1.1. Contexto
O Airbnb é uma plataforma global que conecta anfitriões e viajantes. Em Nova York, a quantidade e a diversidade de ofertas são vastas, tornando os dados dessa plataforma um excelente caso de estudo para análise de preços e características dos imóveis.

1.2. Objetivo

O objetivo deste projeto é analisar o impacto de diferentes características dos imóveis (como tipo de quarto, localização e número de avaliações) sobre os preços dos imóveis no Airbnb em Nova York. Buscaremos criar um modelo preditivo de regressão linear para prever os preços com base nessas características.

1.3. Justificativa

Compreender os fatores que influenciam os preços pode auxiliar anfitriões a ajustar suas ofertas e fornecer insights valiosos para potenciais hóspedes e investidores. Além disso, esse estudo servirá para aprimorar habilidades em análise de dados e modelagem preditiva.

2. Metodologia
   
2.1. Coleta e Preparação dos Dados
Os dados foram obtidos do conjunto AB_NYC_2019.csv, que contém informações sobre listagens de imóveis no Airbnb em Nova York.

Passos:

Importação dos Dados: Carregamos o conjunto de dados e examinamos as primeiras linhas para familiarização.
Limpeza dos Dados: Tratamos valores nulos e removemos colunas irrelevantes para garantir que os dados estivessem prontos para análise.
Exploração dos Dados: Realizamos uma análise descritiva para entender a distribuição dos preços e das características dos imóveis.

2.2. Análise Exploratória

Gráficos e Insights:

Distribuição dos Preços: Utilizamos histogramas e boxplots para visualizar a distribuição dos preços e identificar possíveis outliers.
Distribuição das Variáveis Categóricas: Analisamos a frequência dos diferentes tipos de quartos e grupos de vizinhança para identificar padrões.

2.3. Modelagem Preditiva

Modelo de Regressão Linear:

Preparação dos Dados: Convertendo variáveis categóricas em numéricas usando One-Hot Encoding e dividindo os dados em conjuntos de treino e teste.
Treinamento do Modelo: Aplicamos a regressão linear para prever os preços dos imóveis com base nas características selecionadas.
Avaliação: Utilizamos métricas como o Erro Quadrático Médio (MSE) e o Coeficiente de Determinação (R²) para avaliar o desempenho do modelo.

3. Resultados e Discussão

3.1. Resultados do Modelo

Os resultados da regressão linear mostraram como diferentes variáveis influenciam o preço dos imóveis. A análise revelou quais características têm maior impacto no preço e a eficácia do modelo em prever os valores.

3.2. Interpretação dos Resultados

Impacto das Características: O modelo indicou que fatores como o tipo de quarto e a localização são determinantes significativos dos preços.
Precisão do Modelo: A análise das métricas de avaliação forneceu uma visão sobre a precisão do modelo e as áreas onde ele pode ser melhorado.

4. Conclusão

4.1. Principais Descobertas

O estudo identificou que as características dos imóveis têm uma influência substancial sobre os preços no Airbnb. A regressão linear foi capaz de capturar essas relações, proporcionando um modelo útil para prever preços futuros.

4.2. Limitações e Trabalhos Futuros

Limitações:

Dados limitados a um único ano e localização específica.
Outras variáveis que poderiam influenciar os preços não foram incluídas.

Trabalhos Futuros:

Expansão do modelo para incluir mais dados e variáveis.
Experimentação com modelos de aprendizado de máquina mais avançados para melhorar a precisão das previsões.

Contato

Para mais informações, entre em contato através do paparellilucas1@gmail.com
