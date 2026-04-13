# Análisis Estratégico de Importaciones de Montacargas - Zona Norte Colombia 📈

Elaborado por: **Yesid del Cristo García Sierra**

**Key Account Manager North Zone – Zoomlion Heavy Industry Colombia SAS**

Este repositorio contiene el análisis exhaustivo del mercado de importaciones de montacargas en Colombia, con un enfoque especializado en la **Zona Norte**, desarrollado para potenciar la posición competitiva de **Zoomlion Heavy Industry Colombia SAS**.

## 📋 Resumen Ejecutivo

El estudio analiza las dinámicas de comercio exterior entre **2023 y 2025**, utilizando datos verificables de **Sicex.com**. El objetivo principal es transformar datos complejos en estrategias accionables de ventas y marketing para liderar el segmento de montacargas en la región.

### 🔍 Alcance del Proyecto
* **Tendencias de Mercado:** Análisis de volúmenes y valores (US$ CIF) de importación anual.
* **Segmentación Tecnológica:** Identificación de demanda por fuente de energía (Eléctricos vs. Diésel/Gasolina).
* **Actores Clave:** Mapeo de los principales importadores y competidores a nivel nacional y regional.
* **Propuesta de Valor:** Enfoque en el Costo Total de Propiedad (TCO), garantías extendidas y disponibilidad de repuestos.

## 📊 Hallazgos Clave (Data Insights)

El conjunto de datos comprende registros con un valor total superior a los **US$ 5.7 millones CIF**.

| Métrica | Valor Promedio | Máximo Registrado |
| :--- | :--- | :--- |
| **Valor US$ CIF** | $4,533.75 | $16,441.99 |
| **Cantidad** | 8.59 unidades | 1,414 unidades |
| **Peso Neto** | 2,079.59 kg | 37,146.86 kg |

### 🌍 Principales Orígenes
China lidera el mercado como el principal exportador, validando la competitividad de la tecnología de Zoomlion:
1.  **China:** $2,838,511.72 US$ CIF.
2.  **Estados Unidos:** $1,331,965.98 US$ CIF.
3.  **Alemania:** $910,088.93 US$ CIF.

## 🛠️ Stack Tecnológico
El análisis se ejecutó mediante un entorno de **Jupyter Notebook** (`.ipynb`) empleando las siguientes herramientas:

```python
import pandas as pd
import numpy as np
import plotly.express as px
import seaborn as sns
from sklearn.cluster import KMeans
from xgboost import XGBClassifier
