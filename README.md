# Proyectos de Machine Learning en Python

Este repositorio contiene tres proyectos de aprendizaje automático desarrollados en Jupyter Notebooks. Cada notebook aborda una tarea diferente y demuestra la aplicación de diversos algoritmos y técnicas, desde los fundamentos hasta flujos de trabajo más avanzados, cabe mencionar que se realizaron otros dos proyectos relacionados con la regresión y las anomalías sin embargo estos se realizaron en clase y por lo tanto no dispongo de ese material.

---

## 📂 Contenido del Repositorio

### 1. `clasificacion.ipynb` - Comparativa de Algoritmos de Clasificación
* **Tarea**: Clasificación Supervisada.
* **Objetivo**: Comparar el rendimiento de cuatro algoritmos de clasificación para predecir la aceptabilidad de un automóvil.
* **Dataset**: Car Evaluation de UCI.
* **Conceptos**: Preprocesamiento de datos categóricos, entrenamiento de modelos y evaluación basada en la métrica de exactitud (accuracy).
* **Algoritmos**: Perceptrón, Regresión Logística, K-Vecinos más Cercanos (KNN) y XGBoost.

### 2. `agrupamientos.ipynb` - Comparativa de Algoritmos de Clustering
* **Tarea**: Aprendizaje No Supervisado (Clustering).
* **Objetivo**: Identificar el número óptimo de grupos en el dataset Iris y comparar la calidad de los clústeres resultantes de tres algoritmos diferentes.
* **Dataset**: Iris de Scikit-learn.
* **Conceptos**: Normalización de datos, Método del Codo, Dendrogramas, Criterios AIC/BIC y evaluación con el Coeficiente de Silueta.
* **Algoritmos**: K-Means, Clustering Aglomerativo y Modelos de Mezcla Gaussiana (GMM).

### 3. `pipelines.ipynb` - Flujos de Trabajo con Pipelines y GridSearchCV
* **Tarea**: Clasificación Binaria y Evaluación Robusta de Modelos.
* **Objetivo**: Construir un flujo de trabajo sistemático para preprocesar, entrenar, optimizar y evaluar modelos de clasificación para el diagnóstico de cáncer de mama.
* **Dataset**: Wisconsin Breast Cancer de UCI.
* **Conceptos**: `Pipelines` para encapsular flujos de trabajo, `GridSearchCV` para la búsqueda de hiperparámetros y **Validación Cruzada Anidada** para una evaluación imparcial del rendimiento.
* **Algoritmos**: Regresión Logística, Máquinas de Vectores de Soporte (SVC) y XGBoost.

---

## 🔧 Requisitos

Para ejecutar estos notebooks, necesitarás tener las siguientes librerías de Python instaladas:

* `numpy`
* `pandas`
* `matplotlib`
* `scikit-learn`
* `xgboost`
* `yellowbrick` (para el notebook de agrupamientos)

Puedes instalarlas usando pip:
```bash
pip install numpy pandas matplotlib scikit-learn xgboost yellowbrick
```

## 🚀 Cómo Ejecutar
### 1.Clona o descarga este repositorio.
### 2. Abre una terminal y navega al directorio del proyecto.
### 3.Inicia Jupyter Notebook o Jupyter Lab:
`jupyter notebook`
### 4.Desde la interfaz de Jupyter en tu navegador, abre el notebook que desees explorar y ejecuta las celdas.
