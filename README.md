# 📊 Telecom X – Predicción de Cancelación de Clientes (Churn)

## 📌 Descripción del proyecto

Este proyecto corresponde a la **Parte 2 del Desafío Telecom X**, cuyo objetivo es desarrollar modelos predictivos capaces de identificar clientes con alta probabilidad de cancelación (*churn*), utilizando técnicas de **Machine Learning** y **análisis estadístico**.

A partir de los datos previamente tratados en la Parte 1 del desafío, se construyó un pipeline completo de modelado, desde el preprocesamiento de los datos hasta la interpretación de los resultados y la generación de recomendaciones estratégicas para el negocio.

---

## 🎯 Objetivos

* Preparar los datos para el modelado predictivo.
* Analizar la correlación y seleccionar variables relevantes.
* Entrenar y evaluar distintos modelos de clasificación.
* Comparar el desempeño de los modelos mediante métricas.
* Interpretar la importancia de las variables.
* Proponer estrategias de retención basadas en los resultados.

---

## 🧠 Modelos implementados

Se entrenaron y evaluaron los siguientes modelos:

* **Regresión Logística** (con estandarización)
* **Árbol de Decisión**
* **Random Forest**

Cada modelo fue evaluado utilizando métricas como:

* Exactitud (Accuracy)
* Precisión
* Recall
* F1-score
* Matriz de confusión

---

## 📊 Principales hallazgos

El análisis permitió identificar los factores más influyentes en la cancelación de clientes:

* **Antigüedad del cliente (tenure)**: menor antigüedad implica mayor riesgo de churn.
* **Tipo de contrato**: los contratos mensuales presentan mayor tasa de cancelación.
* **Cargos mensuales elevados**: asociados a una mayor probabilidad de churn.
* **Servicios de internet (fibra óptica)**: factor relevante en la cancelación.
* **Servicios de soporte y seguridad**: su ausencia incrementa el riesgo de cancelación.

---

## 🧩 Recomendaciones estratégicas

A partir de los resultados obtenidos, se proponen las siguientes acciones:

* Implementar estrategias de retención temprana para clientes nuevos.
* Incentivar contratos de mayor duración.
* Revisar planes con cargos mensuales elevados.
* Fortalecer y comunicar mejor los servicios de soporte y seguridad.
* Utilizar modelos predictivos para segmentar clientes según riesgo de cancelación.

---

## 🛠️ Herramientas y tecnologías utilizadas

* **Python**
* **Pandas & NumPy**
* **Matplotlib & Seaborn**
* **Scikit-learn**
* **Jupyter Notebook**

---

## 📁 Estructura del repositorio

```
📦 telecom-x-churn-parte-2
├── notebooks/
│   └── Telecom_X_Parte_2.ipynb
├── data/
│   └── datos_tratados.csv
├── README.md
```

---

## 🚀 Conclusión

Este proyecto demuestra cómo la ciencia de datos y el aprendizaje automático pueden ser utilizados para resolver problemas reales de negocio, permitiendo anticipar la cancelación de clientes y apoyar la toma de decisiones estratégicas orientadas a la retención.

---

✍️ *Proyecto desarrollado como parte del programa de formación en Data Science – Alura Latam.*

