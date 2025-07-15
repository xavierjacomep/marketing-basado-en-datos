# 🛒 Predicción de Propensión de Compra en E-commerce

## 📌 Descripción del Proyecto

Este proyecto tiene como objetivo construir un modelo de machine learning para predecir la probabilidad de conversión (compra) de los usuarios que visitan una plataforma de e-commerce. Utilizando datos de navegación, tipo de visitante, temporalidad y engagement, se desarrollan modelos de clasificación capaces de identificar leads con alta propensión de compra y así optimizar estrategias de targeting y marketing digital.

---

## 🎯 Objetivo de Negocio

Maximizar la tasa de conversión y el retorno sobre la inversión (ROI) de campañas digitales, enfocando los esfuerzos únicamente en usuarios con mayor probabilidad de comprar, reduciendo el desperdicio de recursos comerciales y mejorando la eficiencia de captación.

---

## 🧠 Proceso Analítico

### 1. 📊 Análisis Exploratorio (EDA)
- Análisis por tipo de visitante (`New`, `Returning`, `Other`)
- Evaluación de estacionalidad (meses y días)
- Detección de patrones de comportamiento y engagement

### 2. 📈 Pruebas Estadísticas
- Mann-Whitney U Test para variables numéricas
- Test de Chi-cuadrado para variables categóricas
- Cálculo de tamaño del efecto (effect size) para valorar relevancia práctica

### 3. 🏗 Feature Engineering
- Creación de variables de interacción, proporciones y binarizaciones
- Codificación categórica (`LabelEncoder`)
- Estandarización robusta (`RobustScaler`)

### 4. 🤖 Modelado Supervisado
- Modelos utilizados:
  - Regresión Logística
  - Random Forest (modelo final)
  - Gradient Boosting
  - Support Vector Machine
- Manejo de desbalanceo con SMOTE
- Validación cruzada estratificada
- Métricas: Accuracy, Precision, Recall, F1, ROC-AUC, Average Precision

### 5. 📈 Análisis de Lift y Deciles
- Evaluación de efectividad del targeting
- Cálculo de lift en top decil y captura acumulada

### 6. 💰 Evaluación Financiera
- Simulación de campañas con y sin modelo
- Cálculo de ROI y rentabilidad por targeting estratégico

---

## ✅ Resultados Clave

- **Modelo final:** Random Forest
- **F1-Score en test:** ~0.79
- **F1-Score en backtesting:** ~0.78
- **Lift en decil superior:** 4.63x
- **Captura en top 30%:** 87.4% de las conversiones
- **ROI sin modelo:** +674%
- **ROI con modelo:** +2163%

---

## 📌 Conclusiones y Recomendaciones

- Focalizar esfuerzos en segmentos con alta propensión (`PageValues`, `ExitRates`, `ProductRelated_Duration`)
- Priorizar campañas en fines de semana y meses como octubre y noviembre
- Segmentar audiencias según tipo de tráfico (`TrafficType`) y tipo de visitante
- Evaluar la posibilidad de integrar SHAP para interpretabilidad y calibración de probabilidades

---
