# Predicción de demanda de taxis por hora 🚕

Este proyecto lo hice como parte del Sprint 15 de mi formación en ciencia de datos. El objetivo principal fue predecir cuántos pedidos de taxi se hacen por hora, usando modelos de series temporales. Aunque al inicio tuve varias dudas sobre cómo manejar los datos por hora, al final logré una predicción bastante decente, cumpliendo con el objetivo de mantener un RECM (RMSE) menor a 48.

---

## 📌 Descripción

Trabajé con un dataset de pedidos históricos de taxis. La idea fue construir un modelo que permita anticipar la demanda por hora y así optimizar la disponibilidad de vehículos. Usé técnicas como descomposición de series, evaluación de estacionariedad y diferentes modelos, como XGBoost, Prophet y SARIMA.

Aprendí bastante sobre cómo preparar datos temporales, y sobre todo cómo evaluar si un modelo está funcionando bien o no. También me topé con errores en el camino, pero eso me ayudó a entender mejor el flujo completo.

---

## 🛠 Tecnologías utilizadas

- Python 3.10  
- Pandas  
- Numpy  
- Matplotlib / Seaborn  
- Statsmodels  
- Prophet  
- XGBoost  
- Scikit-learn  
- Jupyter Notebook  

---

## 📂 Estructura del proyecto
TaxisTempSeries/
├── data/ # Datos originales
├── notebooks/ # Análisis, exploración y modelos
├── README.md # Este archivo :)
└── requirements.txt # Librerías necesarias.


---

## 📈 Resultados

Logré una RECM menor a 48, que era la métrica objetivo del sprint. El modelo que mejor se comportó fue **XGBoost**, aunque **SARIMA** también tuvo buen rendimiento en ciertos tramos de la serie.

---

## 🧠 Lecciones aprendidas

- La importancia de transformar bien la variable temporal (resamplear por hora fue clave)
- Cómo detectar estacionalidad y tendencias en una serie
- XGBoost puede adaptarse a series temporales con la ingeniería de features adecuada
- Prophet facilita el manejo de estacionalidad múltiple

---

## 👤 Autor

**Pablo Sebastián Morán**  
📫 psmoran01@gmail.com  
🌐 [Mi GitHub](https://github.com/PSMORAN01)  
🔗 [LinkedIn](https://www.linkedin.com/in/psmoran01) ← Revisa que el link esté correcto

