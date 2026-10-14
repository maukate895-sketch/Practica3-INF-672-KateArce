# Practica3-INF-672-KateArce
# Práctica de Machine Learning: Regresión Polinomial y Lineal

Proyecto de exploración, limpieza de datos y modelado predictivo para analizar la relación entre la potencia del motor (`horsepower`) y el rendimiento de combustible (`mpg`) utilizando el dataset **Auto MPG**.

## 🛠️ Tecnologías y Librerías Utilizadas
* **Python** (Entorno Jupyter Notebook / Anaconda)
* **Pandas & NumPy** para manipulación de datos y cálculos vectoriales.
* **Scikit-Learn** para modelos de regresión lineal, polinomios, pipelines y validación cruzada.
* **Matplotlib & Seaborn** para visualización gráfica y análisis de residuos.

## 📊 Estructura y Fases del Proyecto
1. **Carga y Exploración:** Análisis dimensional y detección de valores faltantes (6 registros nulos en `horsepower`).
2. **Análisis de Correlación:** Identificación de variables predictoras clave.
3. **Limpieza de Datos:** Depuración y preparación del set de datos.
4. **Modelado Base:** Entrenamiento y evaluación de un modelo de **Regresión Lineal Simple**.
5. **Modelado Avanzado:** Implementación de **Regresión Polinomial (Grado óptimo 2)** mediante `Pipeline` y `StandardScaler`.
6. **Validación Cruzada:** Uso de `KFold` (10 pliegues) para evitar el sobreajuste (*overfitting*).
7. **Evaluación Final y Residuos:** Comparación de métricas ($RMSE$ y $R^2$) y análisis gráfico de los residuos.
8. **Conclusiones y Límites:** Análisis de la extrapolación y límites físicos del modelo.

## 🚀 Cómo ejecutar el proyecto
1. Clona este repositorio o descarga el archivo `.ipynb`.
2. Abre tu entorno de **Jupyter Notebook** (o Google Colab).
3. Asegúrate de tener instaladas las dependencias:
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn
