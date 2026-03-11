# Challege_Telecom_X_parte_2

# 📊 Telecom X – Predicción de Cancelación de Clientes (Churn)

## 📌 Descripción del proyecto

Este proyecto tiene como objetivo analizar los factores que influyen en la **cancelación de clientes (Churn)** en la empresa ficticia **Telecom X** y construir modelos de machine learning capaces de predecir qué clientes tienen mayor probabilidad de abandonar el servicio.

El análisis combina técnicas de **limpieza de datos, análisis exploratorio y modelos predictivos**, permitiendo identificar patrones relevantes en el comportamiento de los clientes y proponer estrategias para mejorar la retención.

---

# 🎯 Objetivos del proyecto

- Analizar los datos de clientes para identificar patrones asociados a la cancelación.
- Preparar y transformar los datos para su uso en modelos de machine learning.
- Entrenar y evaluar modelos predictivos para identificar clientes con alto riesgo de churn.
- Analizar las variables más influyentes en la cancelación.
- Proponer estrategias de retención basadas en los resultados del análisis.

---

# 📂 Estructura del proyecto
Challege_Telecom_X_parte_2
│
├── Challege_Telecom_X_parte_2.ipynb # Notebook principal del análisis
├── README.md # Documentación del proyecto
├── datos_tratados_csv



---

# 🧹 Preparación de datos

Se realizaron varias etapas de limpieza y transformación del dataset:

- Eliminación de columnas irrelevantes como `id_cliente`.
- Tratamiento de valores faltantes.
- Conversión de variables categóricas mediante **One Hot Encoding**.
- Análisis del balance de clases en la variable objetivo (`cancelacion`).
- Creación de variables derivadas relevantes para el análisis.

---

# 📊 Análisis exploratorio de datos

Durante el análisis exploratorio se identificaron patrones importantes en el comportamiento de los clientes:

- Relación entre **antigüedad del cliente y cancelación**.
- Relación entre **cargos mensuales y churn**.
- Impacto del **tipo de contrato** en la retención de clientes.
- Identificación de correlaciones entre variables relevantes.

Se utilizaron visualizaciones como:

- Boxplots
- Scatter plots
- Matriz de correlación
- Gráficos de distribución

---

# 🤖 Modelos de Machine Learning

Se implementaron dos modelos de clasificación para predecir la cancelación de clientes.

## 1️⃣ Regresión Logística

Modelo lineal utilizado para estimar la probabilidad de cancelación.

Características:

- Requiere **normalización de datos**
- Permite interpretar la influencia de cada variable mediante coeficientes

## 2️⃣ Random Forest

Modelo basado en múltiples árboles de decisión.

Características:

- No requiere normalización
- Captura relaciones complejas entre variables
- Permite analizar la **importancia de variables**

---

# 📈 Evaluación de modelos

Los modelos fueron evaluados utilizando métricas estándar de clasificación:

- **Accuracy**
- **Precision**
- **Recall**
- **F1-score**
- **Matriz de confusión**

En problemas de churn, el **recall** es una métrica especialmente importante, ya que permite identificar la mayor cantidad posible de clientes con riesgo de cancelación.

---

# 🔍 Factores que más influyen en la cancelación

El análisis de los modelos permitió identificar varios factores clave asociados al churn:

- Clientes con **contratos mes a mes** tienen mayor probabilidad de cancelar.
- Clientes con **baja antigüedad** presentan mayor riesgo de abandono.
- **Cargos mensuales elevados** están asociados a mayor churn.
- Los clientes con **servicios adicionales** tienden a permanecer más tiempo en la empresa.

---

# 💡 Estrategias de retención propuestas

Basado en los resultados del análisis, se proponen algunas estrategias para reducir la cancelación de clientes:

- Incentivar **contratos de largo plazo** mediante promociones o descuentos.
- Implementar programas de fidelización para **clientes nuevos**.
- Revisar la **estructura de precios** para mejorar la percepción de valor.
- Promover **servicios adicionales** que aumenten la satisfacción del cliente.
- Implementar modelos predictivos para **detectar clientes con alto riesgo de cancelación**.

---

# 🛠 Tecnologías utilizadas

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

---

# 🚀 Posibles mejoras futuras

- Optimización de hiperparámetros de los modelos.
- Implementación de modelos adicionales como **Gradient Boosting o XGBoost**.
- Desarrollo de un sistema de predicción de churn en tiempo real.
- Implementación de dashboards para monitoreo de clientes en riesgo.

---

# 👩‍💻 Autora

**Gisell Patiño Hoyos**

Proyecto desarrollado como parte del **Challenge Telecom X – Análisis de evasión de clientes**.

---
