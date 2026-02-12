# Laboratorio: Aprendizaje Supervisado (Regresión + Clasificación)

### Mario Fernando Rocha - 23501

### Juan Francisco Martínez - 23617

Notebook de laboratorio (scikit-learn) que resuelve **dos problemas**:
1) **Regresión** con *California Housing*  
2) **Clasificación binaria** con *Breast Cancer Wisconsin*

Todo el análisis y resultados están documentados dentro del notebook (Markdown + código).

## Contenido
- **Parte 1 – Regresión**
  - Modelos: `LinearRegression`, `DecisionTreeRegressor`, `RandomForestRegressor`
  - Métricas: **MAE**, **RMSE**, **R²**
  - Ajuste de hiperparámetros con **GridSearchCV** y validación cruzada

- **Parte 2 – Clasificación Binaria**
  - Modelos: `LogisticRegression`, `KNeighborsClassifier`, `RandomForestClassifier`
  - Escalamiento para modelos sensibles a escala (`StandardScaler` en pipelines)
  - Métricas: **Accuracy**, **Precision**, **Recall**, **F1-score**
  - **Matriz de confusión** + discusión de errores
  - Optimización con **GridSearchCV**

## Requisitos
- Python 3.9+ 
- Paquetes:
  - `numpy`, `pandas`
  - `matplotlib`, `seaborn`
  - `scikit-learn`

Instalación rápida:
```bash
pip install numpy pandas matplotlib seaborn scikit-learn
