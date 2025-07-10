<<<<<<< HEAD
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
=======
# Predicción de demanda de taxis por hora 🚕

Este proyecto lo hice como parte de mi formación en ciencia de datos. El objetivo principal fue predecir cuántos pedidos de taxi se hacen por hora usando modelos de series temporales. Aunque al inicio tuve varias dudas sobre cómo manejar los datos por hora, al final logré una predicción bastante decente.

## 📌 Descripción

Trabajé con un dataset de pedidos históricos de taxis. La idea fue construir un modelo que permita anticipar la demanda y así optimizar la disponibilidad de vehículos. Usé técnicas como descomposición, estacionariedad, y modelos como XGBoost y SARIMA.

Aprendí bastante sobre cómo preparar datos temporales y sobre todo cómo evaluar si un modelo está funcionando bien o no. También me topé con varios errores en el camino, pero eso me ayudó a entender mejor el flujo completo.

## 🛠 Tecnologías utilizadas

- Python 3.10
- Pandas
- Numpy
- Matplotlib y Seaborn
- Statsmodels
- XGBoost
- scikit-learn
- Jupyter Notebook

## 📂 Estructura del proyecto

TaxisTempSeries/
├── data/ # Datos originales
├── notebooks/ # Análisis, exploración y modelos
├── README.md # Este archivo :)
└── requirements.txt # Librerías necesarias


## 🚀 Cómo correr el proyecto

1. Clona el repo:
bash
git clone https://github.com/PSMORAN01/TaxisTempSeries.git
cd TaxisTempSeries


2. Crea un entorno virtual (opcional pero recomendado)
bash
Copiar
Editar
python -m venv venv
source venv/bin/activate  # En Linux/macOS
venv\Scripts\activate     # En Windows


3. Instala las dependencias:
bash
Copiar
Editar
pip install -r requirements.txt


4. Abre el notebook en Jupyter:
bash
Copiar
Editar
jupyter notebook notebooks/01_modelo_series_temporales.ipynb

📈 Resultados
Logré una RECM (RMSE) menor a 48, que fue el objetivo inicial del reto. El modelo que mejor se comportó fue XGBoost, aunque SARIMA también dio buenos resultados en ciertas ventanas.


Ejemplo de comparación entre predicción y realidad

Lecciones aprendidas
La importancia de transformar bien la variable temporal (resampling por hora fue clave)

Cómo detectar estacionalidad y tendencias

XGBoost también sirve para series temporales, aunque no sea su uso principal


👤 Autor
Pablo Sebastián Morán
📫 psmoran01@gmail.com
🌐 Mi GitHub
🔗 LinkedIn ← Recuerda cambiar esto por el correcto!
>>>>>>> 45e54a218ca5d7851c1a72faf47dec301d1a5276
