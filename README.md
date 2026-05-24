# TFM: Búsqueda de genes involucrados en el grado histológico de tumores de mama

[![Language: R](https://img.shields.io/badge/Language-R-blue.svg)](https://www.r-project.org/)
[![License: CC BY-NC-ND 3.0 ES](https://img.shields.io/badge/License-CC_BY--NC--ND_3.0_ES-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-nd/3.0/deed.es)

---

## 📖 Descripción
Este repositorio contiene el código fuente desarrollado para el Trabajo Final de Máster (TFM) del **Máster Universitario en Ciencia de Datos de la UOC**. 

El proyecto implementa un pipeline bioinformático completo para el análisis de expresión génica (RNA-Seq) en cáncer de mama. A través de técnicas de aprendizaje automático (**Random Forest** y **SVM**), se ha desarrollado un modelo capaz de clasificar el grado histológico tumoral, facilitando la identificación de biomarcadores génicos con relevancia clínica.

## 📂 Estructura del Repositorio
* `CODE/`: Contiene el rMarkdown con el flujo completo de análisis, desde el preprocesamiento de datos hasta la evaluación de modelos.
* `DATA/`: *Directorio reservado para los datos fuente (no incluidos).*

## Guía de Reproducción
Para ejecutar el análisis, sigue estos pasos:

1. **Preparación del entorno:** Crea una carpeta llamada `DATA` en la raíz del repositorio.
2. **Descarga de datos:** Obtén los archivos originales (`GSE268851_series_matrix.txt` y `GSE268851_TNBC_Study_RawCounts.txt`) desde [NCBI GEO (GSE268851)](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE268851) y colócalos en la carpeta `DATA`.
3. **Ejecución:** Abre `CODE/TFM_Memoria_Analisis.Rmd` en RStudio y asegúrate de tener instaladas las librerias y dependencias necesarias.

## ⚠️ Responsabilidad Clínica
Este modelo constituye una herramienta de **apoyo a la decisión clínica** y no sustituye, bajo ninguna circunstancia, el diagnóstico médico profesional. La validación final de los biomarcadores identificados debe ser realizada por personal clínico cualificado.

## ⚖️ Licencia
Esta obra está sujeta a la licencia [Creative Commons Attribution-NonCommercial-NoDerivs 3.0 Spain](https://creativecommons.org/licenses/by-nc-nd/3.0/deed.es).

---
**Autor:** Oriol Castellano Aguilera  
*Máster Universitario en Ciencia de Datos, UOC.*
