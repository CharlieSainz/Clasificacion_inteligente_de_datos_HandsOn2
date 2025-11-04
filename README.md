# Clasificacion_inteligente_de_datos_HandsOn2
Assignments de la materia de Clasificacion inteligente de datos 

# Clasificador kNN (K-Nearest Neighbors)

Este proyecto es un tutorial en Python sobre la técnica de clasificación kNN, implementada con la librería scikit-learn.  
El objetivo es comprender cómo funciona el método de los k vecinos más cercanos y cómo aplicarlo paso a paso en un conjunto de datos real.

---

## Contenido
- Fundamentos teóricos del método kNN  
- Modelo matemático  
- Descripción de librerías y funciones utilizadas  
- Pipeline con las siguientes etapas:
  - Preprocesamiento  
  - Feature Engineering  
  - Prediction  
  - Model Evaluation (Matriz de confusión y Accuracy)  
- Conclusión general sobre los resultados

---

## Descripción general
El algoritmo kNN clasifica un nuevo patrón comparándolo con sus vecinos más cercanos en el espacio de características.  
No construye un modelo de aprendizaje como otros clasificadores, sino que se basa directamente en los datos de entrenamiento.

En este caso se utiliza el dataset **Iris**, que contiene tres tipos de flores y cuatro variables (largo y ancho de pétalos y sépalos).  
El modelo se entrena con una parte de los datos y se evalúa con el resto.

---

## Referencias
Géron, A. (2019). Hands-On Machine Learning with Scikit-Learn, Keras & TensorFlow. O’Reilly Media.
Cover, T., & Hart, P. (1967). Nearest Neighbor Pattern Classification. IEEE Transactions on Information Theory, 13(1), 21–27.
Scikit-learn Documentation. (2025). KNeighborsClassifier.
https://scikit-learn.org/stable/modules/generated/sklearn.neighbors.KNeighborsClassifier.html

---

## Requisitos
Para ejecutar el notebook se necesitan las siguientes librerías:
```bash
pip install scikit-learn matplotlib seaborn numpy pandas
