# 🐾 MACHINE LEARNING: CLASIFICACIÓN CON SCIKIT-LEARN

[![Python](https://img.shields.io/badge/Python-3670A0?style=flat&logo=python&logoColor=ffdd54)](https://www.python.org/)  
[![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)](https://scikit-learn.org/)  
[![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)](https://numpy.org/)

Este proyecto es una **introducción práctica a los Algoritmos de Clasificación** dentro del Machine Learning Supervisado, utilizando la librería estándar **Scikit-learn (SKLearn)**. El objetivo es comprender cómo funcionan los modelos de clasificación a través de un ejemplo didáctico de **clasificación binaria** (Perro vs. Gato) y el uso de **datasets reales** preexistentes en la librería.

---

## 🧠 Contenido del Proyecto

### 1️⃣ Conceptos Fundamentales de Clasificación
- **Problema de Clasificación Binaria:** Se introduce la clasificación binaria (dos posibles resultados) mediante la distinción entre **Perros y Gatos**.
- **Características (Features) y Etiquetas (Labels):**
    * **Features (X):** Características de entrada (ej. ¿Tiene pelo largo?, ¿Tiene las uñas afiladas?, ¿Hace miau?).
    * **Labels (Y):** Clase o etiqueta de salida (ej. 0 = Perro, 1 = Gato).
- **Modelos Utilizados:** Se utiliza el clasificador **Gaussian Naive Bayes** (`GaussianNB`) de Scikit-learn para el ejemplo inicial, conocido por su simplicidad y velocidad.

### 2️⃣ Entrenamiento, Predicción y Evaluación
- **Entrenamiento (Fit):** Se demuestra el proceso de **entrenamiento del modelo** pasando las features (`X`) y los labels (`Y`) al método `.fit()` del clasificador.
- **Predicción (Predict):** Se utiliza el modelo entrenado con `.predict()` para predecir la etiqueta de una nueva instancia de datos (ej. un animal con nuevas características).
- **Evaluación del Modelo:** La precisión del modelo se evalúa mediante el cálculo del **Accuracy** (o `score`), que indica el porcentaje de predicciones correctas.

### 3️⃣ Uso de Datasets de SKLearn
- **Datasets Integrados:** Se aprovechan los datasets de demostración que vienen con la librería, como el famoso dataset **Iris**.
- **Preprocesamiento:** Se demuestra el uso de utilidades de Scikit-learn para preprocesar los datos, como la función `train_test_split` para dividir el dataset en conjuntos de **entrenamiento y prueba**.
- **Diagrama del Proceso:** El flujo de trabajo se representa visualmente (a través de un diagrama de flujo) que resume los pasos: **Obtener Datos -> Separar Muestras -> Entrenar -> Predecir -> Evaluar**.

---

## 🛠️ Librerías Utilizadas

| Librería       | Uso principal                               |
|----------------|---------------------------------------------|
| **Scikit-learn**| Importación de datasets, Modelos de Clasificación (`GaussianNB`) y Métodos de Evaluación (`accuracy_score`)|
| **NumPy**      | Creación y manejo de *arrays* para Features y Labels|

---

## 🎯 Objetivo del Proyecto
El proyecto tiene como objetivo introducir el **paradigma de Machine Learning Supervisado (Clasificación)**, demostrando cómo se construye, entrena y evalúa un modelo de clasificación utilizando la sintaxis de **Scikit-learn**, preparando al usuario para problemas más complejos como la clasificación de texto o detección de fraude.

---

## 📈 Resultados Clave
- Se logra entrenar un modelo que puede distinguir entre un perro y un gato (clasificación binaria).
- Se obtiene una **métrica de precisión (Accuracy)** que cuantifica la efectividad del modelo.
- Se establece el flujo de trabajo estándar para cualquier problema de Machine Learning: **Separación de Datos, Entrenamiento y Evaluación**.

