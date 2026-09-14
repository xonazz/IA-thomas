# Aluno

**Aluno:** Jonas Jeronimo Cirilo Silva
**Matrícula:** 20240026090
**Dataset:** [Human Digital Twin Dataset](https://www.kaggle.com/)

# Descrição

Este repositório contém a análise exploratória, o pré-processamento e a análise dos dados para a atividade da disciplina DCT1401 - Inteligência Artificial. O objetivo é preparar e analisar o dataset Human Digital Twin para a aplicação de técnicas de aprendizado de máquina envolvendo problemas de regressão e classificação.

# Estrutura

* `data/raw/`: Dataset original
* `data/processed/`: Datasets após limpeza e pré-processamento
* `notebooks/`: Notebooks com as análises
* `reports/figures/`: Gráficos e figuras gerados
* `src/`: Funções auxiliares

# Como Executar

1. Clone o repositório
2. Instale as dependências: `pip install -r requirements.txt`
3. Execute : analise_dataset.ipynb


# Principais Resultados

* Para regressão, a variável alvo analisada foi `Longevity_Score`, buscando identificar quais características apresentam maior relação com o índice de longevidade
* Para classificação, foram analisadas as variáveis `Burnout_Risk` e `AI_Recommendation`, sendo escolhida a mais adequada de acordo com os resultados obtidos durante a análise
* A variável `Digital_ID` foi removida das features por ser apenas um identificador
* As principais variáveis analisadas incluem `Wellness_Score`, `Biological_Age`, `Heart_Age`, `Fitness_Index` e `Mental_Wellbeing`
* Também foram analisados valores ausentes, outliers, distribuições das variáveis e correlações entre as características do dataset

# Contato

* **Email: jonas.silva.702@ufrn.edu.br
* **Matrícula:** 20240026090
