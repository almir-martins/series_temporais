# Previsão de Demanda com Séries Temporais

## Contexto
Uma empresa de distribuidora de medicamentos deseja melhorar suas previsões de demanda de produtos para otimizar seus estoques e reduzir custos operacionais. Atualmente, as previsões são feitas de forma manual e não têm sido eficazes, resultando tanto em excesso de estoque quanto em falta de produtos. Como Cientista de Dados Pleno, você foi convidado para desenvolver um modelo de previsão de demanda utilizando séries temporais.

## Objetivo
Desenvolver um modelo de previsão de demanda para os próximos 12 meses, com base nos dados históricos de vendas de um produto específico.

Você deve utilizar técnicas de séries temporais para criar esse modelo, focando na escolha apropriada de métricas de erro e na análise crítica do desempenho do modelo em relação ao conjunto de dados de validação. Além disso, você deve considerar fatores como tendências, sazonalidade e possíveis anomalias.

## Instruções

### EDA - Exploração Inicial dos Dados
Realize uma extensa análise exploratória dos dados, identificando padrões.

### Modelagem
Utilize pelo menos 2 métodos de modelagem para prever a demanda futura. Recomendamos considerar:

- Modelos tradicionais de séries temporais (como ARIMA, SARIMA, ou ETS, etc).
- Modelos baseados em aprendizado de máquina (como LSTM, Prophet ou outros).
- Modelos de séries temporais hierárquicas (top-down, bottom-up, etc).

### Validação Cruzada
Justifique porque você escolheu tal método em vez de outro (levando em consideração as particularidades de séries temporais, como Time Series Split). Caso use validação cruzada no fine-tuning, justifique também.

### Métricas de Avaliação
Avalie o desempenho do seu modelo utilizando as seguintes métricas de erro:

- MAE (Mean Absolute Error)
- MSE (Mean Squared Error)
- RMSE (Root Mean Squared Error)
- MAPE (Mean Absolute Percentage Error)
- WMAPE (Weighted Mean Absolute Percentage Error)

Explique qual métrica você considera mais adequada para este tipo de problema e por quê. Foque nas métricas de erro, mas não exclua as outras.

### Ajuste de Hiperparâmetros
Descreva o processo de ajuste de hiperparâmetros, se aplicável, e porque usou tal método em vez de outro.

### Análise de Resíduos
Avalie os resíduos do modelo e o cumprimento ou não dos pressupostos estatísticos e seus respectivos p-values.

## Entrega
Um notebook Jupyter contendo:

- Análise Exploratória dos Dados (EDA).
- Explicação detalhada dos modelos escolhidos e das etapas de validação.
- Discussão das métricas, principalmente de erros, resíduos e interpretação dos resultados.
- Conclusões sobre a eficácia dos modelos.
- Código bem estruturado e extensamente comentado, pronto para ser executado.

Caso queira, sinta-se à vontade para propor novos insights ou métodos além do solicitado.

## Critérios de Avaliação

### Qualidade da Análise Exploratória
Identificação adequada de padrões nas séries temporais (tendência, sazonalidade, etc.).

### Adequação do Modelo
Capacidade de escolher modelos apropriados para a tarefa.

### Explicação das Métricas (principalmente de Erro)
Clareza e precisão ao explicar as métricas utilizadas, e justificativa para a métrica escolhida como principal.

### Interpretação do Resultado
Capacidade de interpretar os resultados e oferecer insights úteis para o negócio.

### Qualidade do Código
Organização, clareza, uso adequado de comentários e eficiência.

### Profundidade Técnica
Demonstração de conhecimento avançado em séries temporais, modelos, métricas, e análise de resíduos.

### Diferenciais Bônus
- Se um dos modelos escolhidos for de série temporal hierárquica.
- Demonstrar profundidade no uso do WMAPE.
- Consideração de variáveis exógenas coletadas de datasets públicos.
- Uso do mlflow.

## Base de dados
[Link para a base de dados](https://drive.google.com/file/d/16poKfYRxBaYwlFCp6x621M4TgBQGgvXf