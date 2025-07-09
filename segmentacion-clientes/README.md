# 🧠 Análisis de Personalidad del Cliente  
**Caso práctico sobre Segmentación de Clientes**  
**Asignatura:** Marketing basado en datos  
**Autor:** Xavier Jácome Piñeiros, MSc.

---

## 📘 Contexto

El **Análisis de Personalidad del Cliente** permite comprender en profundidad las características, comportamientos y preferencias de los clientes de una empresa. Esta comprensión es esencial para:

- Diseñar estrategias de marketing personalizadas.
- Adaptar productos y servicios a segmentos específicos.
- Optimizar los recursos comerciales y mejorar la rentabilidad.

En lugar de realizar campañas generalizadas, las empresas pueden identificar los **segmentos más propensos a comprar ciertos productos** y dirigir los esfuerzos exclusivamente hacia esos grupos, **aumentando la efectividad y reduciendo costos**.

---

## 🧩 Planteamiento del Problema

**Empresa:** *Delizia Market*  
**Sector:** Retail - supermercado premium con canales físicos, online y catálogo

**Escenario empresarial:**  
Delizia Market ha identificado los siguientes desafíos:

- Alta desigualdad en los niveles de gasto entre clientes.
- Bajo retorno en campañas promocionales masivas.
- Deserción de clientes premium que no se sienten bien atendidos.
- Campañas efectivas en un canal que no se replican en otros.

---

## 💼 Necesidad del negocio

La gerencia de marketing solicita un análisis profundo de la personalidad comercial de sus clientes para:

1. Descubrir segmentos naturales de clientes según perfil y comportamiento.
2. Entender hábitos por canal (web, catálogo, tienda física).
3. Diseñar estrategias personalizadas para clientes digitales, sensibles al precio o de perfil gourmet.
4. Orientar el presupuesto publicitario solo a segmentos con alta receptividad.
5. Mejorar la retención de clientes valiosos mediante acciones adaptadas.

---

## 🧪 Rol del Científico de Datos

Tu rol es desarrollar un modelo de **clustering no supervisado** para segmentar a los clientes de forma significativa. Deberás utilizar variables relacionadas con:

- Perfil sociodemográfico: edad, ingresos, educación, composición familiar.
- Comportamiento de compra: gasto por tipo de producto.
- Participación en campañas anteriores.
- Uso de canales (web, catálogo, tienda).
- Recencia y antigüedad como cliente.

A partir del análisis, se espera:

- Generar insights y fichas por segmento.
- Responder preguntas como:
  - ¿Quiénes son los clientes silenciosos pero leales?
  - ¿Qué segmento responde mejor a campañas por catálogo?
  - ¿Quiénes tienen alto gasto pero bajo engagement digital?
  - ¿Qué tipo de cliente no aporta valor y no debe ser priorizado?
- Formular estrategias de marketing diferenciadas y basadas en datos.

---

## 📊 Contenido del Dataset

El dataset contiene información detallada sobre personas, comportamiento de compra, respuesta a campañas promocionales y uso de canales. Las variables están agrupadas así:

### 👥 Personas
- `ID`: Identificador único.
- `Year_Birth`: Año de nacimiento.
- `Education`: Nivel educativo.
- `Marital_Status`: Estado civil.
- `Income`: Ingreso anual del hogar.
- `Kidhome`: Nº de niños en el hogar.
- `Teenhome`: Nº de adolescentes en el hogar.
- `Dt_Customer`: Fecha de registro.
- `Recency`: Días desde la última compra.
- `Complain`: Queja registrada (1 = sí, 0 = no).

### 🛒 Productos (gasto en los últimos 2 años)
- `MntWines`, `MntFruits`, `MntMeatProducts`, `MntFishProducts`, `MntSweetProducts`, `MntGoldProds`.

### 📣 Promociones y campañas
- `NumDealsPurchases`: Compras con descuento.
- `AcceptedCmp1` a `AcceptedCmp5`: Respuesta a campañas anteriores.
- `Response`: Aceptación de la última campaña.

### 📍 Canal de compra
- `NumWebPurchases`: Compras web.
- `NumCatalogPurchases`: Compras por catálogo.
- `NumStorePurchases`: Compras en tienda.
- `NumWebVisitsMonth`: Visitas al sitio web el último mes.

---

## 🎯 Variable Objetivo

Este proyecto **no utiliza una variable objetivo supervisada**.  
El objetivo es aplicar algoritmos de **clustering no supervisado** para descubrir segmentos de clientes con patrones similares, lo que permitirá:

- Generar estrategias de marketing segmentadas.
- Tomar decisiones comerciales más precisas.
- Maximizar el valor del cliente a través de personalización basada en datos.
