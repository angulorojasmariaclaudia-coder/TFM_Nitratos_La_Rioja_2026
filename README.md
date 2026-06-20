
# PROYECTO DE INVESTIGACIÓN 

# Tema: Clasificación del Riesgo de Contaminación por Nitratos mediante ML

Este repositorio contiene el desarrollo técnico del Trabajo de Fin de Máster orientado a la clasificación del riesgo de contaminación por nitratos en las aguas subterráneas de La Rioja durante el periodo 2015–2025.

## 📌 Descripción

El proyecto desarrolla y evalúa modelos de aprendizaje automático a partir de la integración de datos públicos sobre concentración de nitratos y variables climáticas, edáficas, agrícolas, territoriales y de vegetación.

Aunque no se plantea como un modelo espacio-temporal específico, incorpora la dimensión espacial y temporal mediante la localización de los puntos de monitoreo, las características territoriales y la evolución anual de las observaciones.

## 📊 Fuentes de datos

* Nitratos: redes RNIT y RBAS de la Confederación Hidrográfica del Ebro.
* Clima: precipitación y temperatura.
* Suelo: propiedades edáficas.
* Agricultura: información SIGPAC.
* Territorio: altitud, municipios, masas de agua y zonas vulnerables.
* Vegetación: índice NDVI.

## 🛠️ Tecnologías

* Python
* Jupyter Notebook
* Pandas y NumPy
* Scikit-learn y XGBoost
* GeoPandas y Folium
* Matplotlib
* Joblib

## 📂 Estructura del repositorio

```text
01_notebooks_proyecto/
02_datos_construidos/
03_analisis_datos/
04_datos_procesados/
05_resultados_modelado/
06_resultados_mapas/
07_documentos/
```

## 📈 Contenido

El repositorio incluye:

* Construcción e integración del dataset.
* Análisis descriptivo y exploratorio.
* Preprocesamiento de variables.
* Entrenamiento y comparación de modelos.
* Validación cruzada y temporal.
* Importancia de variables.
* Mapas de observaciones, predicciones y errores.
* Resultados y métricas del modelo final.

Los archivos de gran tamaño, como rásteres, GeoPackages y modelos pesados, no se incluyen en el repositorio.

## 👩‍💻 Autora

**María Claudia Angulo Rojas**

Máster en Ciencia de Datos y Aprendizaje Automático

Universidad de La Rioja

Curso 2025–2026
