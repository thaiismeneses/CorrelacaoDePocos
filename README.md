# Analise de Correlação de Poços

## Introdução
Uma empresa especializada em perfuração e extração de petróleo. Diante da enorme quantidade de dados acumulados ao longo dos anos, a empresa decidiu iniciar um projeto de análise de dados. 

## Descrição do Projeto
O projeto visa desenvolver um modelo de correlações de poços. A ideia é identificar poços correlatos, ou seja, poços que compartilham características semelhantes entre si. Para isso, o projeto utiliza uma base de dados de poços existentes, extrai padrões desses dados e, em seguida, treina um modelo de aprendizado de máquina para encontrar poços correlatos com base nos dados fornecidos.

## Pacotes usados
```bash
pip install pandas pymysql scikit-learn mysql-connector-python 
```

## Características de um poço
- **Nome:** Identifica o projeto do poço.
- **Fase:** Número da fase do projeto. Um projeto é dividido em fases.
- **Tipo de Poço:** Existem dois tipos de poços: VERTICAL ou HORIZONTAL.
- **Lâmina D'Água (LDA):** Distância em metros entre a superfície do mar e o ponto de perfuração em poços subaquáticos.
- **Diâmetro da Fase:** Diâmetro da broca utilizado em polegadas para cada fase da perfuração.
- **Metragem:** Total perfurado em metros durante aquela fase.
- **Número de Fases (NFases):** Número total de fases que o projeto exigiu.
