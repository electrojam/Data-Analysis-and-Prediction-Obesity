📊 Análisis y Predicción de Nivel de obesisdad con Machine Learning

📌 Descripción del Proyecto
Analizaremos un dataset que muestra los niveles de obesidad de personas, basados en los hábitos de alimentación y actividad física.  Se tomó como referencia proyecto realizado en Kaggle "Obesity Prediction" (https://www.kaggle.com/code/madhuraatmarambhagat/obesity-prediction-accuracy-96/notebook).

En el proyecto, se desarrolló un análisis del dataset, y se implementaron varios modelos de Machine Learning para escoger el de mejor precisión. 

Los principales objeticos del análisis de datos son:

📌 Analizar la correlación de las varables del dataset
📌 Implementación de varios modelos de ML de clasificación para predecir la variable de interés.
📌 Evaluación del desempeño de los modelos, mediante el cálculo de métricas accuracy, precision, recall.

🚀 Tecnologías Utilizadas
* Python, Jupyter notebooks (Colab).
* Librerías: pandas, numpy, matplotlib, sickit-learn, seaborn.
* Modelos empleados: KNN, decision tree clasifier, random forest classifier, gradient boosting classifier, ada boost classifier, logistic regresion.

📊 Exploratory Data Analysis (EDA)

✅ Valores Nulos: El dataset no contiene valores nulos, lo que facilita el análisis y la construcción de modelos sin necesidad de imputación.
✅ Datos Duplicados: Se encontraron y eliminaron datos duplicados, asegurando la integridad del análisis.
✅ Variables Categóricas: Las variables categóricas fueron codificadas numéricamente mediante codificación ordinal (OrdinalEncoder) para poder ser utilizadas en los modelos de Machine Learning.
✅ Correlación: La matriz de correlación muestra las relaciones entre las variables numéricas, lo cual puede ser útil para la selección de características o para identificar multicolinealidad.
✅ Distribución de Datos: Los histogramas muestran la distribución de los datos para cada variable, lo cual ayuda a entender la naturaleza de los datos y detectar posibles sesgos o patrones.

📊 Modelos de Machine Learning

Comparación de Modelos: Se evaluaron seis modelos de Machine Learning: KNN, Decision Tree Classifier, Random Forest Classifier, Gradient Boosting Classifier, Ada Boost Classifier y Logistic Regression.
Métricas de Evaluación: Se utilizaron las métricas de accuracy, precision y recall para evaluar el rendimiento de los modelos.

Modelo: KNN
Accuracy: 81.65869218500798
Precision: 81.67993645818241
Recall: 81.65869218500798
==============================
Modelo: Decision Tree Classifier
Accuracy: 96.96969696969697
Precision: 97.14454752360135
Recall: 96.96969696969697
==============================
Modelo: Random Forest Classifier
Accuracy: 99.20255183413079
Precision: 99.22777037165635
Recall: 99.20255183413079
==============================
Modelo: Gradient Boosting Classfifier
Accuracy: 97.4481658692185
Precision: 97.60283747119537
Recall: 97.4481658692185
==============================
Modelo: Ada Boost Classifier
Accuracy: 77.35247208931419
Precision: 74.43367771542005
Recall: 77.35247208931419
==============================
Modelo: Logistic Regresion
Accuracy: 86.60287081339713
Precision: 86.97306961104438
Recall: 86.60287081339713 
------------------------------
Resultados: Los resultados muestran que Gradient Boosting Classifier y Random Forest Classifier tienen el mejor rendimiento en general, con valores altos de accuracy, precision y recall.

![image](https://github.com/user-attachments/assets/9fb00f28-bf33-476d-a7df-6255f3410b73)


El análisis de datos y la construcción de modelos de Machine Learning en este notebook sugieren que se puede predecir el nivel de obesidad con un buen nivel de precisión utilizando los datos disponibles. Los modelos Gradient Boosting Classifier y Random Forest Classifier son los que presentan un mejor rendimiento para esta tarea. Sin embargo, es recomendable seguir explorando los datos y probando otros modelos o técnicas para mejorar aún más la precisión de las predicciones.
