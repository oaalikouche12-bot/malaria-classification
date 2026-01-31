# Malaria Classification

Este repositorio contiene el trabajo de clasificación realizado sobre el conjunto
de datos de Malaria proporcionado en eCampus (Hugging Face), como parte de la
asignatura de Aprendizaje Automático.

## Objetivo
Resolver un problema de clasificación supervisada para predecir el estado de
malaria de un paciente a partir de variables demográficas, clínicas y contextuales.

## Dataset
Se utiliza el dataset:
- `malaria_ssa_extra_large_10000.csv`

El conjunto de datos se divide en entrenamiento y test para evaluar el rendimiento
del modelo.

## Metodología
- Análisis exploratorio de datos (EDA)
- Preprocesamiento y feature engineering
- Entrenamiento de un modelo de clasificación (Árbol de decisión)
- Evaluación mediante accuracy, matriz de confusión, classification report y AUC-ROC

## Estructura
- `malaria_classification.ipynb`: notebook principal del trabajo
- `data/`: carpeta con el dataset utilizado
