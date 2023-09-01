# Previsão de Preços de Combustíveis: Análise e Estimativa Futura

## Objetivo

Bem-vindo ao projeto "Previsão de Preços de Combustíveis: Análise e Estimativa Futura". Nosso objetivo neste projeto é desenvolver modelos de previsão de preços de combustíveis com base em dados históricos. Por meio da análise exploratória e da aplicação de técnicas de séries temporais e regressão, buscamos criar modelos que estimem com precisão os preços futuros dos combustíveis. A avaliação e ajuste desses modelos permitirão entender as tendências de mercado e melhorar a capacidade de planejamento financeiro.

## Roteiro

### 1. Carregamento e Pré-processamento dos Dados

Nesta etapa, realizamos o carregamento dos dados e aplicamos o pré-processamento necessário para preparar os dados para análise. Isso inclui a importação de bibliotecas, a eliminação de colunas irrelevantes e o tratamento de valores nulos. Além disso, convertemos a coluna de data para o formato apropriado.

### 2. Análise Exploratória de Dados

Conduzimos uma análise exploratória de dados para responder a várias perguntas, como a variação dos preços dos combustíveis ao longo do tempo, a distribuição dos combustíveis na amostra, diferenças de preço por região e o estado com o preço médio mais alto de gasolina.

### 3. Preparação dos Dados para Previsão, Divisão em Conjuntos de Treinamento e Teste e Treinamento do Modelo

Nesta fase, preparamos os dados para a previsão, dividindo-os em conjuntos de treinamento e teste. Utilizamos um modelo ARIMA (Autoregressive Integrated Moving Average) para realizar previsões de seis meses dos preços dos combustíveis. Calculamos métricas como RMSE (Root Mean Squared Error), MAE (Mean Absolute Error) e MAPE (Mean Absolute Percentage Error) para avaliar o desempenho do modelo.

### 4. Avaliação do Modelo

Avaliamos o desempenho dos modelos de previsão usando métricas como RMSE, MAE e MAPE. Isso nos ajuda a entender o quão bem nossos modelos estão se saindo e a identificar áreas de melhoria.

---

## Resultados

Após a análise e a previsão, obtivemos os seguintes resultados:

- Diesel: Redução de -3.5%
- Diesel S10: Redução de -3.7%
- Etanol: Redução de -2.6%
- Gasolina: Redução de -9.3%
- GNV: Redução de -9.3%

É importante observar que essas previsões foram feitas com base em dados até 2022 e que as condições de mercado podem ter mudado desde então. Comparando as previsões com dados reais de 2023, vemos algumas variações.

- Diesel: R$ 6,40 (09/2022) -> R$ 6,15 (04/2023) -> R$ 6,18 (previsão)
- Diesel S10: R$ 6,53 (09/2022) -> R$ 6,25 (04/2023) -> R$ 6,29 (previsão)
- Etanol: R$ 4,01 (10/2022) -> R$ 4,58 (04/2023) -> R$ 3,90 (previsão)
- Gasolina: R$ 4,96 (08/2022) -> R$ 5,08 (02/2023) -> R$ 4,50 (previsão)
- GNV: R$ 4,96 (10/2022) -> R$ 4,48 (04/2023) -> R$ 4,80 (previsão)

---

## Avaliação do Modelo

Analisando as métricas de desempenho do modelo, podemos observar o seguinte:

- Produto: Diesel
  
  - RMSE: 0.67
  - MAE: 0.59
  - MAPE: 8.42%

- Produto: Diesel S10
  
  - RMSE: 0.67
  - MAE: 0.59
  - MAPE: 8.31%

- Produto: Etanol
  
  - RMSE: 0.33
  - MAE: 0.24
  - MAPE: 5.52%

- Produto: Gasolina
  
  - RMSE: 0.71
  - MAE: 0.65
  - MAPE: 12.02%

- Produto: GNV
  
  - RMSE: 0.24
  - MAE: 0.22
  - MAPE: 4.33%

Observamos que o modelo teve melhor desempenho para Etanol e GNV, enquanto os demais produtos tiveram um desempenho mediano de acordo com as métricas.

---

Este projeto fornece insights valiosos sobre a previsão de preços de combustíveis e pode ser útil para o planejamento financeiro e estratégico. Fique à vontade para explorar os dados e modelos em detalhes e contribuir para melhorias.

Para mais informações ou dúvidas, entre em contato:

- Nome: Miguel Freire
- E-mail: [miguelsilvafreire@hotmail.com](mailto:miguelsilvafreire@hotmail.com)
- LinkedIn: https://www.linkedin.com/in/miguel-freire99/
