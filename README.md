# 📊 Datamart com Python

Projeto desenvolvido na disciplina **Engenharia de Dados III**, da pós graduação em **Inteligência Artificial & Analytics** na **UNIRP Rio Preto**, com o objetivo de construir um **Datamart (modelo estrela)** utilizando Python e dados do Kaggle.

## 📁 Dataset

Fonte:  https://www.kaggle.com/datasets/isaaclopgu/share-of-population-living-in-extreme-poverty

Os dados contêm indicadores de extrema pobreza como: headcount, poverty gap, severity, gini, média, mediana e índice de Watts.

## 🛠 Tecnologias

- Python  
- Pandas  
- KaggleHub  
- SQLite  
- Google Colab

## 🧱 Modelagem

Modelo dimensional (estrela) composto por:

### Dimensões
- `dim_country`
- `dim_year`
- `dim_welfare`
- `dim_comparability`

### Tabela Fato
- `fact_poverty` (indicadores de pobreza vinculados às dimensões)

