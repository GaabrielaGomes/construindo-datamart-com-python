# 📊 Building a Datamart with Python

Project developed in the **Data Engineering III** course, during my **Specialization in Artificial Intelligence & Analytics** at **UNIRP Rio Preto**, with the objective of building a **Datamart (star schema)** using Python and Kaggle data.

Projeto desenvolvido na disciplina de **Engenharia de Dados III**, da minha **pós-graduação em Inteligência Artificial & Analytics** na **UNIRP Rio Preto**, com o objetivo de construir um **Datamart (modelo estrela)** utilizando Python e dados do Kaggle.

---

## 📁 Dataset

Source: https://www.kaggle.com/datasets/isaaclopgu/share-of-population-living-in-extreme-poverty  

The dataset contains extreme poverty indicators such as: headcount ratio, poverty gap, severity, Gini index, mean income, median income, and Watts index.

Os dados contêm indicadores de extrema pobreza como: taxa de incidência (headcount), gap de pobreza, severidade, índice de Gini, média, mediana e índice de Watts.

---

## 🛠 Technologies

- Python  
- Pandas  
- KaggleHub  
- SQLite  
- Google Colab  

---

## 🧱 Data Modeling

Dimensional model (star schema) composed of:

Modelo dimensional (modelo estrela) composto por:

### Dimensions
- `dim_country`
- `dim_year`
- `dim_welfare`
- `dim_comparability`

### Fact Table
- `fact_poverty` (poverty indicators linked to dimensions - indicadores de pobreza vinculados às dimensões)
