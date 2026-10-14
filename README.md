# Práctica de Machine Learning: Clasificación y Regresión

Este repositorio contiene una práctica de revisión de Machine Learning desarrollada en un notebook de Jupyter. El objetivo es conocer y comparar diferentes modelos, interpretar sus resultados y comprender la diferencia entre clasificación y regresión.

## Objetivos

- Explorar los datasets Iris y Diabetes incluidos en scikit-learn.
- Entrenar y comparar modelos de clasificación y regresión.
- Evaluar el rendimiento con diferentes métricas.
- Ajustar hiperparámetros utilizando datos de validación.
- Analizar predicciones, errores y resultados obtenidos.

## Datasets y modelos

### Iris: clasificación

El dataset Iris contiene 150 flores, tres especies y cuatro características relacionadas con las medidas de sépalos y pétalos.

Se comparan siete clasificadores:

- Gaussian Naive Bayes
- Regresión logística
- SVM lineal
- Árbol de decisión
- Random Forest
- Gradient Boosting
- MLP (red neuronal)

Para evaluarlos se utilizan **Accuracy**, **F1 macro** y matrices de confusión.

### Diabetes: regresión

El dataset Diabetes contiene 442 registros, diez características y un objetivo numérico relacionado con la progresión de la enfermedad.

Se comparan ocho modelos de regresión:

- Regresión lineal
- Ridge
- Lasso
- kNN de regresión
- Árbol de regresión
- Random Forest Regressor
- Gradient Boosting Regressor
- MLPRegressor

Para evaluarlos se utilizan **MAE**, **RMSE** y **R²**. También se analizan gráficos de predicciones y residuos.

## Herramientas utilizadas

- Python
- Jupyter Notebook
- scikit-learn
- pandas
- NumPy
- Matplotlib

## Cómo ejecutar el notebook

1. Descarga o clona este repositorio y abre la carpeta en Visual Studio Code.
2. Instala las dependencias necesarias:

   ```bash
   python -m pip install notebook ipykernel scikit-learn pandas numpy matplotlib
   ```

3. Abre `01_revml_entrega_ajustada.ipynb` en VS Code (o el archivo `.ipynb` que esté en el repositorio).
4. Selecciona el intérprete de Python correspondiente y ejecuta las celdas en orden.

Los datasets se cargan directamente desde `scikit-learn`, por lo que no es necesario descargarlos por separado.

## Metodología

Los datos se dividen en conjuntos de **entrenamiento, validación y prueba**. Las transformaciones se ajustan utilizando entrenamiento, los hiperparámetros se seleccionan con validación y las métricas finales se calculan sobre prueba.

## Autor

Christian Ayala  
Ingeniería en Ciencias de la Computación
