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

📎 **Enlace a Notebook:** [Análisis Experimental: Consumo de Pan y Cambio de Peso](https://github.com/JuanAlbornoz32/Proyectos_Bootcamp_Analisis_de_Datos/blob/main/ejercicios_en_python/pruebas_estad%C3%ADsticas/experimento_pan_y_cambio_peso/prueba_t_de_student.ipynb)