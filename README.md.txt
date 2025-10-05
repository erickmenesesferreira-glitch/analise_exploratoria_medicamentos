# Análise Exploratória de Dados de Medicamentos

Este projeto realiza uma análise exploratória (EDA) em um dataset com mais de 145 mil registros de medicamentos, utilizando Python e as bibliotecas Pandas, Matplotlib e Seaborn. O objetivo é extrair insights sobre os usos mais comuns, efeitos colaterais, classes terapêuticas e a relação com a indução de dependência.

## 📊 Principais Análises e Insights

- **Limpeza e Tratamento:** Os dados brutos foram processados para remover duplicatas, tratar valores ausentes e reestruturar as informações de efeitos colaterais e usos para uma análise mais eficaz.
- **Casos de Uso:** A condição mais tratada pelos medicamentos no dataset é a de **infecções bacterianas**, seguida por **alívio da dor**.
- **Classes Terapêuticas:** A classe terapêutica com mais medicamentos registrados é a de **Anti-infecciosos** (`ANTI INFECTIVES`), seguida por **Analgésicos** (`PAIN ANALGESICS`).
- **Efeitos Colaterais:** Os efeitos colaterais mais comuns relatados em todo o dataset são **Náusea**, **Diarreia** e **Vômito**.
- **Relação Classe x Dependência:** A análise mostrou que as classes **NEURO CNS** (medicamentos para o sistema nervoso central) e **PAIN ANALGESICS** (analgésicos) possuem a maior proporção de medicamentos que podem induzir dependência (`Habit Forming`).

## 🛠️ Tecnologias Utilizadas

- Python
- Pandas (para manipulação e tratamento dos dados)
- Matplotlib e Seaborn (para visualização de dados)
- Missingno (para análise de dados ausentes)
- Jupyter Notebook / Google Colab

## 📁 Estrutura do Repositório

O projeto está organizado da seguinte forma:

- **/data/raw**: Contém o dataset original (`medicine_dataset.csv`).
- **/data/processed**: Contém os datasets limpos e exportados após o tratamento.
- **analise_medicamentos.ipynb**: O notebook Jupyter com todo o código e as análises realizadas.

## 🚀 Como Executar

Para executar o projeto localmente, basta clonar este repositório e abrir o arquivo `analise_medicamentos.ipynb` em um ambiente com Jupyter Notebook. Todas as bibliotecas utilizadas são padrão no ecossistema de Data Science.

---
*Projeto desenvolvido por Erick Meneses Ferreira* - www.linkedin.com/in/erick-m-ferreira