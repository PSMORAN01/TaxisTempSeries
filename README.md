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
