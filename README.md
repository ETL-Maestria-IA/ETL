# Repositorio ETL para Procesamiento de Datos del Suelo

Este repositorio contiene proyectos de Extracción, Transformación y Carga (ETL) para el procesamiento y análisis de datos relacionados con el suelo. Incluye dos notebooks de Colab: uno para procesar la fuente de datos "Gravena" y otro para un proyecto ETL centrado en el análisis de las propiedades del suelo.

## Descripción

Este repositorio contiene dos proyectos ETL implementados en notebooks de Colab, diseñados para trabajar con datos del suelo. Los proyectos cubren el procesamiento de una fuente de datos específica llamada "Gravena" y un proyecto ETL más amplio que implica el análisis de las propiedades del suelo.

## Archivos

### `ProcesarFuenteGravena.ipynb`

Este notebook de Jupyter está diseñado para el procesamiento y transformación de datos provenientes de una fuente específica denominada "Gravena".

* **Objetivo:** Extraer, limpiar y formatear datos de suelo desde la fuente "Gravena" para su posterior análisis.
* **Fuentes de Datos:** Fuente de datos "Gravena" un XLSX.
* **Salida:** Se almacena la info en una base de datos MySQL en AWS

### `Proyecto_ETL_Soil.ipynb`

Este notebook de Jupyter implementa un proyecto ETL más general, centrado en el análisis de datos del suelo.

* **Objetivo:** Construir un pipeline ETL para analizar las propiedades químicas y físicas del suelo y generar datos preparados para modelos predictivos].
* **Fuentes de Datos:** Archivos CSV con datos de campo, bases de datos de laboratorios
* **Salida:** Se almacena la info en el data warehouse BigQuery en GCP

## Uso

### Ejecución de los notebooks

1.  Asegúrate de tener instalados los requisitos previos.
2.  Abre Jupyter Notebook o Colab.
3.  Navega hasta la ubicación de los archivos `ProcesarFuenteGravena.ipynb` y `Proyecto_ETL_Soil.ipynb`.
4.  Abre el notebook deseado y ejecuta las celdas en orden.

## Tecnologías Utilizadas

* Python
* Colab
* Pandas
* Numpy
* Matplotlib
* Bigquery
* GCP
* Cloud Storage

