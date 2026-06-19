# UAH – De la Banca Tradicional a los Pagos Autónomos con IA

## De los Actuarios a los Agentes: La Evolución del Talento, la Analítica y la Inteligencia Artificial en la Banca

**Profesor:** Manoel Gadi
**Email:** [manoel.gadi@uah.es](mailto:manoel.gadi@uah.es)

---

## Descripción

Esta sesión explora la evolución de la banca, la analítica y la inteligencia artificial a través de cuatro grandes etapas:

### 5C del Crédito

* Character
* Capacity
* Capital
* Collateral
* Conditions

### 4R del Riesgo

* Risk Identification
* Risk Measurement
* Risk Management
* Risk Reporting

### 3V del Big Data

* Volume
* Velocity
* Variety

### 3A de la Inteligencia Artificial

* Autonomía
* Adaptabilidad
* Auditabilidad

La sesión combina historia de la banca, evolución del talento, técnicas analíticas, Machine Learning, Large Language Models (LLMs), sistemas autónomos y Agentic Payments.

---

# Objetivos de Aprendizaje

Al finalizar la sesión, los participantes podrán:

* Comprender la evolución histórica de la toma de decisiones en banca.
* Identificar cómo han evolucionado los perfiles profesionales desde actuarios hasta diseñadores de sistemas IA.
* Diferenciar técnicas de clasificación, regresión y simulación.
* Comprender métricas de evaluación para clasificación binaria y multiclase.
* Aplicar conceptos de Customer Lifetime Value y Stress Testing.
* Analizar el impacto de la IA en fraude, pagos y sistemas financieros.
* Desplegar aplicaciones basadas en IA utilizando herramientas modernas.

---

# Agenda

## Parte I – La Evolución del Talento

### La Era de las 5C

La banca tradicional basada en juicio experto.

Profesionales predominantes:

* Actuarios
* Economistas
* Analistas financieros
* Gestores comerciales

---

### La Era de las 4R

Nacimiento del riesgo cuantitativo.

Profesionales predominantes:

* Estadísticos
* Matemáticos
* Físicos
* Economistas cuantitativos

---

### La Era de las 3V

La revolución Fintech impulsada por Big Data.

Profesionales predominantes:

* Data Scientists
* Data Engineers
* Machine Learning Engineers

---

### La Era de las 3A

La revolución de la Inteligencia Artificial.

Profesionales predominantes:

* AI Engineers
* AI Product Managers
* Agent Designers
* AI Governance Specialists

---

# Parte II – Evolución de las Técnicas

## Clasificación Binaria

Preguntas típicas:

* ¿Pagará o no pagará?
* ¿Fraude o no fraude?
* ¿Aceptamos o rechazamos?

Técnicas:

* Logistic Regression
* Decision Trees
* Random Forest
* Gradient Boosting
* Neural Networks

---

## Métricas de Evaluación

### Accuracy

Adecuada para datos balanceados.

### F1 Score

Combina Precision y Recall.

### Gini

Tradicionalmente utilizada en banca.

### KS (Kolmogorov-Smirnov)

Especialmente útil en riesgo de crédito.

Jerarquía habitual en problemas bancarios:

```text
KS > Gini > F1 > Accuracy
```

---

## Clasificación Multiclase

Aplicaciones:

* Segmentación
* Tipologías de fraude
* Clasificación de riesgo
* Recomendación de productos

Métricas:

### Cohen Kappa

### Krippendorff Alpha Ordinal

### Gwet AC1

Librerías:

```python
pycm
krippendorff
```

---

# Parte III – Casos Prácticos

## Customer Lifetime Value (CLV)

Notebook:

```text
lifetime_value_modeling_banks.ipynb
```

Combinación de:

### Clasificación

* Churn
* Cross-Sell
* Upsell

### Regresión

* Ingresos
* Margen
* Valor futuro

Pregunta clave:

> ¿Cuál es el valor económico esperado de un cliente durante toda su relación con el banco?

---

## Stress Testing

Notebook:

```text
stress_testing_monte_carlo_banking.ipynb
```

Combinación de:

### Clasificación

Predicción de defaults.

### Regresión

Predicción de pérdidas.

### Monte Carlo

Generación de miles de escenarios económicos.

Variables:

* Inflación
* Tipos de interés
* Desempleo
* Mercado inmobiliario

Pregunta clave:

> ¿Cómo se comporta la cartera bajo escenarios extremos?

---

# Parte IV – Inteligencia Artificial

## Las 3A

### Autonomía

La IA toma decisiones.

### Adaptabilidad

La IA aprende continuamente.

### Auditabilidad

La IA puede explicarse, supervisarse y gobernarse.

---

## Del Machine Learning a los LLM

### Machine Learning

* Credit Scoring
* Fraud Detection
* Pricing
* Risk Models

### LLM

* Explicación
* Conversación
* Automatización
* Investigación

---

# Parte V – Fraude Autónomo

Notebook:

```text
ml_llm_fraud_detection_demo_v2.ipynb
```

Ciclo completo:

1. Prevención
2. Detección
3. Confirmación
4. Investigación
5. Recuperación

La IA:

* Ajusta cut-offs dinámicamente
* Decide el canal óptimo de autenticación
* Detecta fraude organizado
* Propone nuevas reglas de protección

---

# Parte VI – Agentic Payments

Presentación:

```text
agentic_payments_presentation.pptx
```

Conceptos:

* AI Agents
* Agent-to-Agent Commerce
* Agentic Payments
* Deepfakes
* Prompt Injection
* Cryptographic Intent
* Zero Trust Agents

Pregunta clave:

> ¿Quién realizará los pagos dentro de diez años?

---

# Taller Final

## Deploy de IMPACT

Repositorio:

```text
https://github.com/manoelgadi/IMPACT
```

Objetivos:

* Configurar el entorno
* Ejecutar la aplicación localmente
* Conectar modelos de IA
* Desplegar en la nube

Tecnologías:

* Python
* Streamlit
* OpenAI
* Hugging Face
* GitHub

---

# Pregunta Final

Durante la era de las 5C contratábamos actuarios.

Durante la era de las 4R contratábamos estadísticos.

Durante la era de las 3V contratábamos Data Scientists.

## ¿Qué tipo de profesional debemos contratar para competir en la era de las 3A?

¿Especialistas en IA?

¿Expertos en negocio?

¿Programadores?

¿O profesionales capaces de combinar los tres mundos?

---

## Contacto

**Manoel Gadi**
Universidad de Alcalá (UAH)
📧 [manoel.gadi@uah.es](mailto:manoel.gadi@uah.es)
