# Análisis del Perfil de Riesgo Sistemático de Yelp, Inc. (NYSE: YELP)
> **Trabajo de Fin de Grado (TFG)** · Alba Quintero Huertas · CUNEF Universidad | Facultad de Empresa, Economía y Derecho

Este repositorio contiene el desarrollo empírico y econométrico de un análisis sobre el perfil de riesgo sistemático de Yelp durante el período 2015–2025, utilizando el índice Russell 2000 como referencia de mercado.

El estudio combina herramientas de econometría financiera y análisis de series temporales para evaluar la relación entre las rentabilidades de Yelp y el mercado, así como la estabilidad de dicha relación a lo largo del tiempo.

## Resumen del estudio
El objetivo principal del trabajo es caracterizar la exposición de Yelp al riesgo sistemático mediante la estimación del modelo CAPM y técnicas complementarias de análisis econométrico.

En particular, el estudio busca:
- Estimar el coeficiente beta de Yelp frente al mercado.
- Analizar la estabilidad temporal de la relación riesgo-rentabilidad.
- Detectar posibles cambios estructurales en el comportamiento de la serie.
- Evaluar la robustez del modelo mediante diagnóstico econométrico y tratamiento de valores atípicos.

El análisis se realiza sobre rentabilidades logarítmicas mensuales correspondientes al período enero de 2015 – diciembre de 2025.

## Estructura del Notebook
El análisis se divide en las etapas desarrolladas en el archivo principal:
* **S01**: Carga de datos de Yelp y del índice de referencia Russell 2000.
* **S02**: Construcción de primas de riesgo y estimación del CAPM básico.
* **S03**: Diagnóstico de los residuos (normalidad, heterocedasticidad, autocorrelación).
* **S04**: Identificación y tratamiento de valores atípicos.
* **S05**: Análisis de cambio estructural y selección del modelo final.
* **S06**: Estudio de la estabilidad paramétrica del modelo.

## Herramientas
* **Librerías:** `statsmodels` (regresiones robustas), `pandas`, `matplotlib`, `seaborn`,`yfinance` .

