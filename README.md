# TelecomX_LATAM
# Análisis de Evasión de Clientes – Telecom X

Este proyecto analiza la evasión (churn) de clientes en la empresa **Telecom X**, con el objetivo de identificar factores críticos que contribuyen a la pérdida de usuarios. Utilizando Python y técnicas de análisis de datos, se procesó y visualizó un conjunto de datos reales de clientes para generar insights accionables y recomendaciones estratégicas.

---

## Objetivo

Identificar patrones y variables asociadas a la cancelación del servicio por parte de los clientes, permitiendo a la empresa tomar decisiones informadas para mejorar la retención.

---

## Herramientas Utilizadas

- Python 3 (Google Colab)
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## Estructura del Proyecto

- `dataset/`: Contiene los datos utilizados en archivo JSON adjunto.
- `notebooks/`: Cuadernos de análisis en Google Colab.
- `visualizaciones/`: Gráficos generados durante el análisis.
- `README.md`: Este archivo con resumen del proyecto.
- `informe_final`: Informe detallado con análisis, gráficos y conclusiones.

---

## Etapas del Proyecto

### 1. Limpieza y Preparación de Datos

- Normalización de variables anidadas y tipado correcto.
- Eliminación y tratamiento de valores nulos o inconsistentes.
- Conversión de columnas relevantes y creación de nuevas variables (e.g., `Cuentas_Diarias`).
- Chequeo de duplicados y revisión de categorías.

### 2. Análisis Exploratorio

- Distribución de clientes que evaden vs. no evaden.
- Comparación entre variables categóricas (contrato, método de pago, soporte técnico).
- Análisis de variables numéricas (tenure, cargos mensuales y totales).
- Identificación de correlaciones significativas.

### 3. Análisis de Correlación

- Mapa de calor entre tipo de contrato e internet.
- Cálculo de Cramér's V para variables categóricas.

---

## Principales Hallazgos

- **Los clientes con contrato mensual y fibra óptica presentan mayor evasión.**
- **Clientes con menor antigüedad y mayores cargos mensuales son más propensos a cancelar.**
- **El uso de cheques como método de pago se asocia con mayor churn.**
- **La falta de soporte técnico y presencia de dependientes también influyen negativamente.**

---

## Recomendaciones

- Incentivar contratos de largo plazo mediante beneficios.
- Modernizar métodos de pago, eliminando gradualmente el pago por cheque.
- Mejorar el soporte técnico para clientes nuevos y de riesgo.
- Implementar estrategias de fidelización para clientes con alta antigüedad o cargos totales.

---

## Realizado por:

**Nombre:** Ronald J.Varela M. 
**Correo:** ronaldvarela852@gmail.com  
**Fecha:** Junio 2025

---
