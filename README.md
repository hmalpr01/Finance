# Finance
Este repositorio contiene una serie de proyectos desarrollados en Python enfocados en el análisis del mercado de valores, la segmentación de activos y la predicción de tendencias mediante algoritmos de Machine Learning.

El objetivo principal es aplicar herramientas cuantitativas para la toma de decisiones financieras informadas.

---

## 🚀 Proyectos Incluidos

### 1. Segmentación y Agrupación de Acciones (Clustering)
En este proyecto se analizó un portafolio diversificado de 10 acciones (incluyendo tecnológicas como **NVDA, TSLA, MSFT** y de consumo como **KO**). 
* **Objetivo:** Agrupar activos con comportamientos similares basándose en métricas de riesgo y retorno.
* **Metodología:** * Extracción de datos con `yfinance`.
    * Cálculo de indicadores clave: **Rendimiento Anual, Volatilidad, Beta y Correlación** con el mercado (S&P 500).
    * Implementación del algoritmo **K-Means** con escalamiento de datos (`StandardScaler`).
* **Valor agregado:** Permite identificar la diversificación real de un portafolio y detectar qué activos se mueven en sintonía.

### 2. Predicción de Tendencia de Precios (Clasificación)
Desarrollo de un modelo predictivo para determinar si el precio de cierre de una acción (**GOOGL**) subirá o bajará en la siguiente sesión.
* **Objetivo:** Clasificar el movimiento del mercado basándose en indicadores técnicos.
* **Metodología:**
    * Ingeniería de variables (Feature Engineering) usando la librería **TA-Lib**.
    * Indicadores calculados: **RSI, Bandas de Bollinger, Medias Móviles (SMA) y Williams %R**.
    * Modelo de clasificación con evaluación de rendimiento mediante matrices de confusión y métricas de precisión.

---

## 🛠️ Stack Tecnológico
* **Lenguaje:** Python 3.x
* **Análisis de Datos:** `Pandas`, `NumPy`.
* **Visualización:** `Matplotlib`, `Seaborn`.
* **Machine Learning:** `Scikit-learn`.
* **Finanzas:** `yfinance`, `TA-Lib`.
