# Proyectos de Machine Learning en Python

Este repositorio contiene cuatro proyectos de aprendizaje automático desarrollados en Jupyter Notebooks. Cada notebook aborda una tarea diferente y demuestra la aplicación de diversos algoritmos y técnicas, desde los fundamentos hasta flujos de trabajo más avanzados, cabe mencionar que se realizó otro proyecto relacionado con las anomalías sin embargo este se realizó en clase y por lo tanto no dispongo de ese material.

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

### 4. `regresión.ipynb` - Comparativa de Modelos de Regresión
El objetivo principal es aplicar un flujo de trabajo de machine learning para un problema de regresión. El proceso incluye:
1.  Carga y preparación del dataset **California Housing**.
2.  Selección de un subconjunto de características para el modelo.
3.  División de los datos en conjuntos de entrenamiento y prueba.
4.  Entrenamiento y evaluación de tres modelos distintos.
5.  Comparación de su rendimiento utilizando métricas estándar.

## ✨ Modelos y Métricas

### Modelos Evaluados
Se implementan y comparan los siguientes algoritmos de regresión:
* **Regresión Lineal**: Como modelo base.
* **K-Vecinos más Cercanos (KNN)**: Un enfoque no paramétrico.
* **XGBoost**: Un modelo avanzado de ensamblaje (ensemble).

### Métricas de Evaluación
El rendimiento de cada modelo se mide con:
* **Coeficiente de Determinación (R²)**: Para medir la proporción de la varianza explicada por el modelo.
* **Raíz del Error Cuadrático Medio (RMSE)**: Para medir la magnitud del error de predicción.

## ⚠️ Nota Importante sobre la Calificación Automática

Este notebook de `regresión.ipynb` incluye celdas con una función de calificación automática (`quiz.eval_numeric`) que pueden mostrar un `AssertionError`. **Estos errores deben ser ignorados**. Según las indicaciones del instructor, los valores esperados por el calificador automático son incorrectos, mientras que los resultados calculados por el código del notebook son los correctos.

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
