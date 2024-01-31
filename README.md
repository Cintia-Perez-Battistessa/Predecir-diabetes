# Predecir la diabetes

<a name="repository_4_readme"></a>
## Table of Contents
* [1. Sobre el proyecto](#A_r4)
* [2. Colaboradores](#B_r4) 
* [3. Licencia](#C_r4)
* [4. ¡Dale una estrella!](#D_r4)


<a name="A_r4"></a>
## 1. Sobre el proyecto 

El propósito de este proyecto es determinar si una persona tiene diabetes o no, utilizando un modelo predictivo entrenado con datos de Estados Unidos. Los datos presentaban un desbalance, ya que había una mayor cantidad de casos negativos (sin diabetes). Para abordar este desbalance, se exploraron dos métodos, SMOTE (oversampling y undersampling), con el objetivo de lograr un equilibrio en los datos.

Posteriormente, se evaluaron varios modelos predictivos mediante métricas específicas, y se seleccionó el modelo que mejor se ajustaba a los datos. Los modelos analizados incluyeron:

'Logistic Regression'
'Decision Tree'
'Random Forest'
'SVM'
'KNN'
'Nearest Centroid Classifier'
'Gaussian Naive Bayes Classifier'
El modelo seleccionado fue Random Forest. Luego, se redujo la dimensionalidad del conjunto de datos, identificando y eliminando parámetros con poca variabilidad que no influyeron significativamente en la predicción.

Finalmente, se volvió a entrenar el modelo con Random Forest y se realizó un ajuste fino (tuning) para validar y mejorar la efectividad del modelo.

<a name="B_r4"></a>
## 2. Colaboradores

Este proyecto fue creado en grupo en un Bootcamp de Data Scientist. Mis compañeros fueron: Javier Serna Gálvez, Miriam Lamas y Manuel Ruiz.

<a name="C_r4"></a>
## 3. Licencia ⭐

Este proyecto está bajo la licencia Apache. Eche un vistazo al archivo de LICENCIA para obtener más información.

<a nombre="D_r4"></a>
## 4. ¡Dale una estrella! ⭐

Si esto le resulta útil, dale amor al proyecto. ¡Gracias!
