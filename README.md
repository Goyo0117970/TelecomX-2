# 📉 Análisis de Churn en Telecom X

Este proyecto analiza la pérdida de clientes (churn) en Telecom X mediante técnicas de machine learning e interpretabilidad. El objetivo es identificar los factores clave detrás de la fuga de clientes y proponer estrategias accionables para mejorar la retención.

## 🎯 Objetivo

Detectar patrones y causas de churn utilizando datos estructurados y modelos predictivos, con foco en:

- Tipo de servicio (ej. fibra óptica)
- Flexibilidad contractual
- Antigüedad del cliente
- Interpretabilidad del modelo (SHAP)

## 🧠 Principales Hallazgos

- El servicio de **fibra óptica** está fuertemente asociado al churn, especialmente en los primeros meses.
- Los clientes con **contratos mes a mes** tienen mayor probabilidad de abandonar.
- El análisis con SHAP revela que `customer.tenure`, `Contract_Two year` e `InternetService_Fiber optic` son los principales predictores.

## ⚠️ Posibles Causas

- Promesas excesivas sobre los beneficios del servicio de fibra óptica.
- Problemas técnicos o soporte deficiente en la etapa de onboarding.
- Ausencia de programas de fidelización temprana.
- Alta flexibilidad contractual sin incentivos de permanencia.
- Seguimiento postventa débil.

## ✅ Recomendaciones

- Revisar y alinear las expectativas del servicio de fibra óptica con su entrega real.
- Lanzar campañas de retención dirigidas a clientes nuevos.
- Implementar encuestas de satisfacción dentro de los primeros 90 días.
- Mejorar el soporte técnico para clientes con contratos mensuales.
- Introducir beneficios para migrar a contratos de largo plazo.
- **Aprovechar la Gobernanza de Datos** para auditar reclamos relacionados con fibra óptica y detectar problemas operativos más profundos.

## 📊 Métodos Utilizados

- Regresión Logística, Random Forest, Arbol de decisiones
- SHAP para interpretabilidad
- Ingeniería de variables y ajuste de umbrales
- Segmentación por riesgo de churn
- Visualizaciones con Seaborn y Matplotlib
