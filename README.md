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

Model: KNN  
Accuracy: 81.62878787878788  
Precision: 81.31150462841005  
F1 score: 0.8077480844867615  
Recall: 0.8162878787878788  
------------------------------
Model: Decision Tree Classifier  
Accuracy: 91.47727272727273  
Precision: 91.48493372320604  
F1 score: 0.9144768408140569  
Recall: 0.9147727272727273  
------------------------------
Model: Random Forest Classifier  
Accuracy: 94.31818181818183  
Precision: 94.5775231254653  
F1 score: 0.9437697615967486  
Recall: 0.9431818181818182  
------------------------------
Model: Gradient Boosting Classfifier  
Accuracy: 94.31818181818183  
Precision: 94.34135706862978  
F1 score: 0.942974610547896  
Recall: 0.9431818181818182  
------------------------------
Model: Ada Boost Classifier  
Accuracy: 47.53787878787879  
Precision: 45.00560058227326  
F1 score: 0.396619356012694  
Recall: 0.4753787878787879  
------------------------------
Model: Logistic Regresion  
Accuracy: 85.79545454545455  
Precision: 86.09079597466408  
F1 score: 0.8536082687270117  
Recall: 0.8579545454545454  
------------------------------
Resultados: Los resultados muestran que Gradient Boosting Classifier y Random Forest Classifier tienen el mejor rendimiento en general, con valores altos de accuracy, precision y recall.

![image](https://github.com/user-attachments/assets/9fb00f28-bf33-476d-a7df-6255f3410b73)


El análisis de datos y la construcción de modelos de Machine Learning en este notebook sugieren que se puede predecir el nivel de obesidad con un buen nivel de precisión utilizando los datos disponibles. Los modelos Gradient Boosting Classifier y Random Forest Classifier son los que presentan un mejor rendimiento para esta tarea. Sin embargo, es recomendable seguir explorando los datos y probando otros modelos o técnicas para mejorar aún más la precisión de las predicciones.
