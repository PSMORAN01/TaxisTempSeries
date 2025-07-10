Predicción de demanda de taxis por hora
Este proyecto fue desarrollado como parte del Sprint 15 del bootcamp de ciencia de datos que estoy cursando. El objetivo principal era construir un modelo de predicción de series temporales que estimara la demanda de taxis por hora para la empresa ficticia "Sweet Lift Taxi", manteniendo un error cuadrático medio de predicción por debajo de 48.

Objetivo del proyecto
Predecir cuántos pedidos de taxis se esperan por hora, usando datos históricos.

Evaluar distintos modelos de predicción (SARIMAX, Prophet, regresiones, etc).

Elegir el modelo con mejor rendimiento en función del RECM (RMSE).

Cumplir con la métrica objetivo definida: RECM < 48.

Dataset
Los datos fueron proporcionados como parte del ejercicio del bootcamp. Contienen registros horarios con la cantidad de pedidos por hora, a lo largo de varias semanas. Se realizaron pasos básicos de limpieza y transformación antes del modelado.

Tecnologías utilizadas
Python

Pandas

Numpy

Scikit-learn

Prophet

Matplotlib / Seaborn

Statsmodels

Modelos implementados
Probé varios enfoques de modelado, incluyendo:

Regresión lineal simple

Regresión con variables categóricas y de tiempo

Prophet (modelo aditivo de Facebook)

SARIMAX (modelado clásico de series temporales)

Tras evaluar el rendimiento de cada uno, elegí el que presentaba mejor balance entre precisión y estabilidad.

Resultados
Logré construir un modelo que cumple con la condición de mantener un RECM menor a 48, que era el requerimiento del proyecto. Además, se visualizaron los errores y la predicción para validar que el comportamiento sea razonable a nivel temporal.

Reflexiones finales
Este proyecto me permitió afianzar muchos de los conceptos trabajados en el bootcamp, especialmente en cuanto al tratamiento de series temporales. Aún hay muchas cosas por mejorar, como el manejo de estacionalidades múltiples o el ajuste fino de hiperparámetros, pero estoy satisfecho con lo que logré en esta etapa del aprendizaje.