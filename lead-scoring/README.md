# 🎯 Conversión de Clientes - Stuffmart.com  
**Caso práctico sobre Clasificación de Leads**  
**Asignatura:** Marketing basado en datos  
**Autor:** Xavier Jácome Piñeiros, MSc.

---

## 📘 Contexto

La **Clasificación de Leads** es una técnica clave en el marketing digital y las ventas modernas, que permite identificar automáticamente cuáles clientes potenciales tienen mayor probabilidad de convertirse en clientes reales. Esta capacidad predictiva es fundamental para:

- Optimizar recursos comerciales,
- Priorizar esfuerzos de ventas,
- Diseñar estrategias de marketing más efectivas.

En lugar de realizar campañas generalizadas, las empresas pueden enfocar sus acciones exclusivamente en los leads con alta probabilidad de conversión, lo que **incrementa el ROI y mejora las tasas de cierre**.

---

## 🧩 Planteamiento del Problema

**Stuffmart.com** es una empresa emergente de e-commerce que comercializa productos electrónicos, hogar y estilo de vida a través de canales 100% digitales. Con presencia en mercados como Pakistán, India y Bangladesh, enfrenta los siguientes retos:

- Su tasa de conversión promedio es inferior al 5%.
- La inversión publicitaria presenta un bajo retorno.
- El equipo de marketing necesita mejorar la eficiencia en la gestión de leads.

### 🎯 Objetivo del Proyecto

Desarrollar una solución de analítica avanzada que permita:
- Construir un modelo supervisado que prediga si un lead se convertirá en cliente.
- Enfocar los esfuerzos comerciales en leads con alta probabilidad de conversión.
- Reducir los costos de adquisición de clientes (CAC).
- Personalizar estrategias de contacto y seguimiento.
- Mejorar la eficiencia general del equipo comercial.

Tu rol en este proyecto es el de **Científico de Datos**, encargado de diseñar y evaluar modelos de clasificación que ayuden a resolver este desafío.

---

## 🧠 Contenido del Dataset

El dataset incluye información relevante sobre leads, su comportamiento online, su historial de comunicación con la empresa y datos demográficos. Está estructurado en las siguientes secciones:

### 👤 Perfil del Lead
- `LeadID`: Identificador único.
- `Age`: Edad del lead.
- `Gender`: Género.
- `Location`: Ciudad desde donde se origina el lead.

### 🚪 Origen y Canal de Captación
- `LeadSource`: Canal de adquisición (ej. Social Media, Email, Referral).
- `ReferralSource`: Fuente específica (ej. Facebook, Google, Twitter).

### 💻 Comportamiento en el Sitio Web
- `TimeSpent`: Tiempo total en el sitio web (minutos).
- `PagesViewed`: Páginas vistas.
- `FormSubmissions`: Formularios completados.
- `Downloads`: Archivos descargados.
- `CTR_ProductPage`: Tasa de clics en páginas de producto.

### 📬 Comunicación y Seguimiento
- `EmailSent`: Correos enviados.
- `FollowUpEmails`: Correos de seguimiento.
- `ResponseTime`: Tiempo de respuesta en horas.
- `LeadStatus`: Estado del lead (Cold, Warm, Hot).

### 📱 Tecnología y Redes Sociales
- `DeviceType`: Tipo de dispositivo usado.
- `SocialMediaEngagement`: Nivel de interacción en redes sociales.

### 💳 Historial de Pago
- `PaymentHistory`: Estado del historial de pagos (Good, No Payment).

---

## 🎯 Variable Objetivo

- `Conversion`: Variable binaria que indica si el lead se convirtió en cliente (`1`) o no (`0`). Esta será utilizada como la **target variable** para entrenar y evaluar modelos de clasificación.

---

## 📊 Tecnologías sugeridas

- Python (Pandas, Scikit-learn, Matplotlib, Seaborn)
- Jupyter Notebook o Google Colab
- Métodos de clasificación: Regresión Logística, Árboles de Decisión, Random Forest, XGBoost
- Evaluación con métricas: Accuracy, F1 Score, Matriz de Confusión, Curvas de Lift

---

## ✅ Resultado Esperado

- Un modelo predictivo entrenado y validado.
- Análisis de interpretabilidad de variables clave.
- Recomendaciones para acciones comerciales dirigidas a leads con mayor probabilidad de conversión.

---

¡Este proyecto es una gran oportunidad para aplicar ciencia de datos al marketing y maximizar el impacto comercial mediante decisiones basadas en datos!
