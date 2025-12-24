# SafeSport
Projeto focado na predição do risco de lesões esportivas utilizando aprendizado de máquina, considerando duração do treino, frequência cardíaca, percepção subjetiva de esforço, distância percorrida e histórico de lesões.
🏃‍♂️ Predição de Risco de Lesão Esportiva com Machine Learning
📌 Introdução

Lesões esportivas representam um dos principais fatores de afastamento e queda de desempenho de atletas, tanto em níveis amadores quanto profissionais. A identificação precoce de atletas em risco possibilita intervenções preventivas, reduzindo custos médicos e melhorando a performance esportiva.

Este projeto tem como objetivo predizer o risco de lesão esportiva utilizando técnicas de Machine Learning, com base em dados de carga de treino e variáveis fisiológicas. O estudo foi desenvolvido com foco acadêmico, podendo ser aplicado em contextos reais de monitoramento esportivo.

🎯 Objetivo

Desenvolver um modelo preditivo capaz de estimar a probabilidade de ocorrência de lesão em atletas a partir de variáveis relacionadas ao treinamento e ao histórico físico.

🧪 Metodologia
🔹 Coleta e Variáveis Utilizadas

O modelo utiliza as seguintes variáveis de entrada:

Duração do treino (minutos)

Frequência cardíaca média

Percepção Subjetiva de Esforço (PSE)

Distância percorrida (km)

Dias desde a última lesão

A variável alvo é:

Ocorrência de lesão (sim/não)

🔹 Pré-processamento dos Dados

As seguintes etapas foram realizadas:

Análise exploratória dos dados

Normalização das variáveis numéricas

Separação do conjunto de dados em treino e teste

Balanceamento de classes (quando necessário)

🤖 Modelos de Machine Learning

Foram implementados e avaliados diferentes algoritmos de aprendizado de máquina:

Decision Tree

Random Forest

Bagging

Gradient Boosting

Esses modelos foram escolhidos por sua eficiência em problemas de classificação e boa interpretabilidade.

📊 Métricas de Avaliação

Para avaliar o desempenho dos modelos, foram utilizadas as seguintes métricas:

Acurácia

Precision

Recall

F1-score

AUC (Area Under the ROC Curve)

Essas métricas permitem uma análise equilibrada entre acertos gerais e a capacidade do modelo em identificar corretamente atletas com risco de lesão.

📈 Resultados

Os resultados indicaram que os modelos baseados em ensemble learning (Random Forest e Gradient Boosting) apresentaram melhor desempenho geral, especialmente nas métricas de Recall e AUC, fundamentais em contextos onde é prioritário identificar corretamente atletas em risco.

O modelo final demonstra potencial para aplicação em sistemas de apoio à decisão no esporte, auxiliando profissionais da área na prevenção de lesões.

🛠️ Tecnologias e Bibliotecas Utilizadas

Python

NumPy

Pandas

Scikit-learn

Matplotlib / Seaborn

Jupyter Notebook

🚀 Possíveis Melhorias Futuras

Inclusão de dados reais provenientes de sensores vestíveis

Implementação de modelos de Deep Learning

Otimização de hiperparâmetros

Avaliação em diferentes modalidades esportivas

Deploy do modelo como API ou aplicação web

📚 Contexto Acadêmico

Este projeto pode ser utilizado como base para trabalhos acadêmicos, estudos científicos ou projetos aplicados na área de Ciência de Dados aplicada ao Esporte.

👨‍💻 Autor

Lucas Resende
Analista de Dados
