# Desafio_TelecomX_Alura1
# 📊 Telecom X – Análisis de Evasión de Clientes (Churn)

## 📌 Descripción del proyecto

Este proyecto forma parte del desafío **Telecom X – Análisis de Evasión de Clientes**, propuesto por Alura Latam dentro del programa ONE.  
El objetivo es realizar un análisis exploratorio de datos (EDA) para comprender los factores asociados a la cancelación de clientes (churn) en una empresa de telecomunicaciones.

A través del uso de Python y la biblioteca Pandas, se aplicaron conceptos de **ETL (Extracción, Transformación y Carga)**, limpieza de datos y visualización, con el fin de generar insights que puedan servir como base para futuras estrategias de retención.

---

## 🎯 Objetivo del análisis

- Analizar la distribución de la evasión de clientes.
- Identificar patrones asociados a variables categóricas y numéricas.
- Explorar qué factores podrían estar relacionados con una mayor probabilidad de churn.
- Generar conclusiones e insights descriptivos orientados a la toma de decisiones.

---

## 🧩 Estructura del proyecto

El análisis se desarrolla en un único notebook de Google Colab, organizado en las siguientes secciones:

1. **Extracción de datos**  
   - Obtención de los datos desde una API en formato JSON.

2. **Transformación y limpieza de datos**  
   - Normalización de estructuras anidadas.
   - Revisión de tipos de datos.
   - Identificación y tratamiento de valores nulos e inconsistencias.

3. **Análisis Exploratorio de Datos (EDA)**  
   - Análisis de la distribución del churn.
   - Exploración de variables categóricas (tipo de contrato, método de pago, servicios).
   - Exploración de variables numéricas (tiempo de contrato y cargos mensuales).
   - Visualizaciones para facilitar la interpretación de patrones.

4. **Conclusiones e insights**  
   - Síntesis de los principales hallazgos del análisis.

5. **Recomendaciones**  
   - Propuestas generales basadas en los patrones observados.

---

## 🛠️ Tecnologías y bibliotecas utilizadas

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Requests  

El análisis fue realizado en **Google Colab** y posteriormente versionado en **GitHub**.

---

## 📈 Principales insights

- El tipo de contrato muestra una relación clara con la evasión, concentrándose principalmente en contratos mensuales.
- El método de pago evidencia diferencias relevantes, destacándose una mayor evasión en clientes que utilizan cheque electrónico.
- Los clientes que cancelan presentan, en promedio, menor antigüedad y diferencias en los cargos mensuales.
- Algunas variables, como la cantidad de líneas telefónicas, no mostraron una asociación fuerte con el churn.

---

## 🚀 Recomendaciones

- Evaluar estrategias de retención para clientes con contratos mensuales, incentivando la migración a contratos de mayor duración.
- Analizar posibles fricciones en determinados métodos de pago, especialmente el cheque electrónico.
- Utilizar estos resultados como base para futuros análisis predictivos y modelos de churn más avanzados.

---

## 📄 Cómo ejecutar el proyecto

1. Abrir el archivo `.ipynb` en Google Colab o Jupyter Notebook.
2. Ejecutar las celdas en orden, desde la extracción de datos hasta el informe final.
3. No es necesario descargar los datos localmente, ya que se accede a ellos directamente desde la API.

---

## ✨ Notas finales

Este proyecto tiene un enfoque **exploratorio y descriptivo**, orientado al aprendizaje y a la comprensión del problema de evasión de clientes.  
Las conclusiones no implican causalidad, sino que buscan identificar patrones que ayuden a orientar análisis futuros.

---
