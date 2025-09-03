# 📊 Proyectos de Análisis de Datos

Este repositorio reúne proyectos, ejercicios y casos de estudios desarrollados durante mi participación en el **Bootcamp "Fundamentos de Análisis de Datos"** (Mayo – Agosto 2025), impartido por **Edutecno** y **Talento Digital para Chile**. Donde se puso en práctica el procesamiento, limpieza y preparación de datos para análisis, la realizacion de análisis exploratorios y estadisticos, descripción y relaciones entre variable, visualización y aplicación de pruebas estadísticas, modelos probabilíticos, intervalos de confianzas y modelos predictivos. 

## 🛠️ Proyectos y ejercicios desarrollandos en Python

La carpeta ejercicios_en_python contiene ejercicios, proyectos y casos de estudio que ponen en práctica diferentes técnicas de análisis orientadas a la toma de decisiones basadas en datos.

Esta carpeta se organiza en cuatro subcarpetas principales:

- analisis_descriptivos/ → ejercicios de estadística descriptiva y visualización de datos.

- pruebas_estadisticas/ → tests de hipótesis y procedimientos de inferencia estadística.

- calculos_probabilisticos/ → ejercicios con distribuciones de probabilidad (normal, Poisson, muestral).

- modelos_de_regresion/ → casos de estudio aplicando regresión lineal y multivariada.

### 📌 Instalación de dependencias 

Para ejecutar los ejercicios, instalar las dependencias con:

```bash
pip install -r requirements.txt
```

## 📂 calculos_probabilisticos

### 📊 Cálculo de probabilidades utilizando la Distribución Normal y Poisson

El siguiente ejercicio se basa en la aplicación de distribuciones de probabilidad para analizar dos aspectos en una empresa de atención al cliente: los tiempos de atención telefónica y la cantidad de llamadas recibidas en una hora.

🔹 **Distribución Normal (tiempos de atención al cliente):**
Se modeló el tiempo de atención asumiendo una distribución normal con media de 10 minutos y desviación estándar de 2 minutos. A partir de la función de distribución acumulada (CDF), se calcularon probabilidades de distintos escenarios (atención menor a 8 min, entre 8–12 min y mayor a 14 min). Además, se generó un gráfico que permitió visualizar las áreas bajo la curva asociadas a cada caso.

🔹 **Distribución de Poisson (llamadas por hora):**
Se modeló la cantidad de llamadas recibidas por hora, asumiendo una distribución de Poisson con media de 15 llamadas. Se calcularon probabilidades puntuales y acumuladas para distintos escenarios (exactamente 15 llamadas, menos de 10 y más de 20). Posteriormente, se simuló un experimento de 10 000 horas, comparando la distribución empírica obtenida con la teórica, verificando visualmente la adecuación del modelo.

**Conclusión:** Ambos ejercicios ilustran cómo las distribuciones de probabilidad permiten estimar y contrastar escenarios reales, así como validar los modelos teóricos mediante simulaciones empíricas.

📎 **Enlace:** [Probabilidades con Distribución Normal y Poisson](https://github.com/JuanAlbornoz32/Proyectos_Bootcamp_Analisis_de_Datos/blob/main/python/calculo_de_probabilidades.ipynb)

## 📂 pruebas_estadisticas

### 📈 Aplicación de prueba estadística con datos simulados: Consumo de pan y peso corporal.

Este proyecto corresponde a la realización de una prueba estadística cuyo objetivo fue evaluar el efecto del tipo de pan consumido (marraqueta vs. pan integral) sobre el cambio de peso corporal en un grupo de participantes. El conjunto de datos utilizado es simulado y fue creado únicamente con fines de aprendizaje y práctica.

🔹 **Diseño (simulado):** dos grupos independientes (control y experimental). 

🔹 **Prueba estadística:** t de Student para muestras independientes.

🔹 **Herramientas de análisis:** pandas, matplotlib, seaborn, scipy.stats.


**Resultados principales:**

  - Diferencia promedio de 1.82 kg entre los grupos.
  - Grupo control: +0.44 kg en promedio de aumento de peso corporal.
  - Grupo que comsumio pan integral: –1.38 kg en promedio de de baja de peso corporal.
  - Diferencia estadísticamente significativa con un p-valor menor a 0.001 en base a prueba t de student.

**Análisis complementario:** mapas de correlación con variables adicionales (edad, ingesta calórica, pasos diarios, adherencia a la dieta), que no mostraron asociación relevante con el cambio de peso.

**Conclusión:** En este ejercicio, los datos simulados muestran diferencias significativas en el cambio de peso corporal entre quienes consumieron pan integral y quienes consumieron marraqueta. Aunque los resultados no corresponden a un estudio real, ilustran adecuadamente el uso de la prueba t de Student en un diseño de dos grupos independientes.

📎 **Enlace:** [Análisis Experimental: Consumo de Pan y Cambio de Peso](https://github.com/JuanAlbornoz32/Proyectos_Bootcamp_Analisis_de_Datos/blob/main/analisis_experimental/dise%C3%B1o_experimental.ipynb)

## ✨ Autor

Juan Albornoz Carrillo | Analista de Datos | Sociologo 

📌 [Linkedin](https://www.linkedin.com/in/juan-albornoz-carrillo/)
📌 [Github](https://github.com/JuanAlbornoz32)


