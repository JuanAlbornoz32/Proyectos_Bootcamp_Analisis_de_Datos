### 📈 Análisis de Consumo de Combustible (mpg)

Este proyecto tiene como objetivo analizar los factores que influyen en el consumo de combustible de automóviles (medido en millas por galón, mpg) a partir de un conjunto de variables técnicas y categóricas de los vehículos, y desarrollar un modelo de regresión que prediga el consumo de combustible. Se trata de un ejercicio práctico de modelado estadístico aplicado al análisis de datos.

🔎 **Descripción del Proyecto**

Se desarrollaron y evaluaron dos modelos de regresión lineal múltiple:

- **Modelo completo:** incluye todas las variables disponibles en el dataset.

- **Modelo reducido:** incluye un subconjunto de variables seleccionadas para mejorar la interpretabilidad y reducir la multicolinealidad.

El análisis incluye:

- Exploración inicial de los datos.

- Preparación y limpieza datos

- Análisis de variables y relaciones

- Construcción y evaluación de modelos.

- Cálculo de métricas de error (MAE, MSE, RMSE).

- Gráficos comparativos entre valores reales y predichos.

- Análisis de residuos para validar supuestos del modelo.

📊 **Resultados principales**

- El modelo completo alcanzó un R² = 0.863 y mostró mejor precisión predictiva (MAE = 2.12, RMSE = 2.88).

- El modelo reducido alcanzó un R² = 0.843, con métricas de error ligeramente peores (MAE = 2.30, RMSE = 3.09), pero ofrece mayor interpretabilidad y menor riesgo de multicolinealidad.

- Los análisis de residuos evidencian que ambos modelos cumplen razonablemente los supuestos de normalidad y homocedasticidad, aunque presentan ligeras desviaciones en colas.

📎 **Enlace al Notebook:** [Análisis de consumo de combustible (mpg)](https://github.com/JuanAlbornoz32/Proyectos_Bootcamp_Analisis_de_Datos/blob/main/ejercicios_en_python/modelos_de_regresion/regresion_multiple/ejercicio_millas_por_galon.ipynb)