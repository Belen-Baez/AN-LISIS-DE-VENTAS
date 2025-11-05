# LABORATORIO DE ANÁLISIS DE VENTAS

## Abrir y Ejecutar el Notebook en Google Colab

Este repositorio contiene la entrega final del Laboratorio de Análisis de Datos, que consiste en un proceso completo de análisis sobre un conjunto de datos de ventas.

Haz clic en el siguiente botón para abrir el *notebook* directamente en Google Colab. Una vez abierto, podrás ejecutar todas las celdas para replicar el proceso ETL, el EDA y las respuestas a las preguntas de negocio.

[![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/tu_usuario/tu_repo/blob/main/LABORATORIO_DE_ANÁLISIS_DE_VENTAS.ipynb)

---

##  Objetivo del Laboratorio

El objetivo principal de este proyecto es aplicar de manera integrada las competencias de la especialización para desarrollar un proceso completo de análisis de datos, desde la adquisición de la información hasta la generación de valor de negocio.

## Dataset

* **Tema:** Análisis de transacciones de ventas y métricas clave.

## Fases del Proyecto

El análisis se estructuró siguiendo las siguientes fases, documentadas paso a paso en el notebook:

### 1. ETL – Extracción, Transformación y Carga 
* **Extracción:** Importación del dataset.
* **Transformación:** Limpieza de valores nulos y duplicados, corrección de tipos de datos, y **generación de variables derivadas** clave (ej. `transaction_size`, `year_month`).
* **Carga:** Preparación del DataFrame final listo para la fase de análisis.

### 2. EDA – Análisis Exploratorio de Datos 
* Análisis de la estructura de datos (`info()`, `describe()`).
* Exploración de distribuciones (histogramas) y frecuencias (gráficos de conteo).
* Visualización de relaciones entre variables (diagramas de dispersión y correlación).
* **Interpretación textual** de los hallazgos más relevantes.

### 3. Preguntas de Negocio 
Se formularon y respondieron **tres preguntas de negocio** basadas en los hallazgos del dataset. Cada respuesta incluye la evidencia tabular y la interpretación analítica para la toma de decisiones.

## Requisitos Técnicos

* **Lenguaje:** Python
* **Entorno:** Google Colab
* **Librerías principales:**
    * `pandas` (Manipulación de datos)
    * `numpy` (Cálculo numérico)
    * `matplotlib` / `seaborn` (Visualización de datos)

---
**Desarrollado por:** [NOELIA BELEN BAEZ]
