# 📊 Predicción de Abandono de Clientes 

## 📖 Descripción

Este proyecto desarrolla un modelo de **Machine Learning** para predecir la probabilidad de que un cliente cancele su servicio en una empresa de telecomunicaciones.

El objetivo es identificar de forma anticipada a los clientes con mayor riesgo de abandono para que la empresa pueda implementar estrategias de retención, como promociones personalizadas, descuentos y planes especiales.

---

## 📂 Dataset

El proyecto utiliza información proveniente de cuatro archivos:

- **contract.csv** – Información del contrato del cliente.
- **personal.csv** – Datos demográficos del cliente.
- **internet.csv** – Servicios de Internet contratados.
- **phone.csv** – Servicios telefónicos contratados.

Todos los conjuntos de datos se integran mediante la columna **customerID**.

---

## 🎯 Objetivos

- Integrar múltiples fuentes de datos.
- Limpiar y preparar el conjunto de datos.
- Transformar variables categóricas mediante One-Hot Encoding.
- Entrenar diferentes modelos de clasificación.
- Evaluar el desempeño utilizando la métrica AUC-ROC.
- Seleccionar el modelo con mejor capacidad de predicción.

---

## 🛠️ Tecnologías utilizadas

| Herramienta | Uso |
|------------|------|
| Python | Desarrollo del proyecto |
| Pandas | Limpieza y manipulación de datos |
| NumPy | Operaciones numéricas |
| Matplotlib | Visualización |
| Scikit-learn | Modelado de Machine Learning |

---

## 🔄 Flujo del proyecto

### 📥 Preparación de datos

- Integración de los cuatro datasets.
- Limpieza de valores faltantes.
- Conversión de variables categóricas.
- One-Hot Encoding.
- División en conjuntos de entrenamiento, validación y prueba.

### 📊 Análisis Exploratorio

- Exploración de variables categóricas y numéricas.
- Distribución del abandono de clientes.
- Identificación de posibles patrones asociados al churn.

### 🤖 Modelos entrenados

- Regresión Logística
- Random Forest

### 📏 Evaluación

Los modelos fueron evaluados utilizando:

- AUC-ROC
- Accuracy
- Precision
- Recall
- F1-Score

---

## 🏆 Resultados

| Modelo | AUC-ROC |
|---------|---------:|
| Regresión Logística | **0.8356** |
| Random Forest | **0.8552** |

El modelo **Random Forest** obtuvo el mejor desempeño y fue seleccionado como modelo final.

---

## 📌 Conclusiones

Durante el desarrollo del proyecto se realizó la preparación del conjunto de datos mediante la integración de múltiples fuentes, limpieza de información y transformación de variables categóricas utilizando **One-Hot Encoding**.

Posteriormente se entrenaron dos modelos de clasificación para predecir el abandono de clientes.

La **Regresión Logística** obtuvo un AUC-ROC de **0.8356**, mostrando un buen desempeño como modelo base, aunque presentó limitaciones para capturar relaciones más complejas entre las variables.

El modelo **Random Forest** mejoró los resultados tras el ajuste de hiperparámetros, alcanzando un **AUC-ROC de 0.8552**, convirtiéndose en el modelo con mejor capacidad de clasificación y generalización.

En conclusión, **Random Forest** fue seleccionado como el modelo final, ya que permite identificar con mayor precisión a los clientes con riesgo de cancelar su servicio, convirtiéndose en una herramienta útil para apoyar estrategias de retención.

---

## 💼 Recomendaciones para el negocio

- Identificar clientes con alta probabilidad de abandono mediante el modelo predictivo.
- Implementar campañas de retención personalizadas con promociones y descuentos.
- Priorizar la atención proactiva de clientes en riesgo mediante soporte especializado.
- Analizar las variables más importantes del modelo para comprender las principales causas del abandono.
- Integrar el modelo en un proceso automatizado que permita monitorear continuamente el comportamiento de los clientes.

---

## 🚀 Habilidades demostradas

- Limpieza y preparación de datos
- Integración de múltiples fuentes de información
- Análisis Exploratorio de Datos (EDA)
- Feature Engineering
- One-Hot Encoding
- Machine Learning Supervisado
- Clasificación de datos
- Optimización de hiperparámetros
- Evaluación mediante AUC-ROC
- Interpretación de métricas de clasificación
- Python
- Pandas
- Scikit-learn

---

## 👨‍💻 Autor

**Eduardo Camarena León**

**Data Analyst | Junior Data Scientist**

📧 **Email:** eduardo.camarena2300@gmail.com

💼 **LinkedIn:** www.linkedin.com/in/eduardo-camarena-leon

🌐 **Portafolio:** https://ecamarena2300.github.io/Portfolio/
