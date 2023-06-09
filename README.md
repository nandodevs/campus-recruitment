# Modelo de Predição de desempenho para contratação de candidatos
Este é um projeto de aprendizado de máquina em que o objetivo é criar um modelo capaz de prever se um candidato (aluno de uma instituição de ensino) será contratado por uma empresa com base em vários recursos, como educação, notas e assim por diante.

### Conjunto de dados
Os dados utilizados neste projeto podem ser encontrados no arquivo campus.csv. Este conjunto de dados contém informações sobre vários candidatos, sendo os principais nível escolar, como ensino fundamental, médio, superior e especialização.

### Pré-processamento dos dados
Os dados brutos foram pré-processados para a remoção de valores ausentes e a codificação das variáveis categóricas (como gênero e educação) em variáveis numéricas. Além disso, os dados foram divididos em conjuntos de treino e teste, com 70% dos dados utilizados para treinamento e 30% dos dados para teste.

### Modelos
Foram testados vários modelos de aprendizado de máquina neste projeto, incluindo Regressão Logística, Árvore de Decisão e Random Forest. Os modelos foram ajustados com o conjunto de treinamento e avaliados com o conjunto de teste.

### Avaliação do modelo
A avaliação do modelo foi realizada com base em várias métricas, incluindo acurácia, precisão, recall e F1-score. O modelo com melhor desempenho foi selecionado com base nessas métricas e utilizado para realizar previsões no conjunto de teste.

### Contribuições
Contribuições são bem-vindas! Sinta-se à vontade para abrir um pull request ou uma issue com sugestões de melhorias ou correções.