# Análisis de datos de taxis de Nueva York con PySpark: ExercicioRDDs

Este repositorio contiene un análisis de datos del conjunto de datos de viajes en taxi de la ciudad de Nueva York utilizando PySpark en un notebook de Jupyter llamado `ExercicioRDDs.ipynb`. El análisis se realiza en un clúster de CESGA y cubre diversas preguntas relacionadas con los viajes de taxis, como la cantidad de viajes, la duración media de los viajes y los ingresos generados.

## Requisitos previos

Antes de comenzar, es necesario tener el archivo de datos en el sistema de archivos HDFS en la siguiente ruta:

/opt/cesga/cursos/pyspark_2022/datasets/NYC_taxi_trip_records/yellow_tripdata_2018-11.csv

## Tecnologías y estructuras de datos utilizadas

Este análisis utiliza las siguientes tecnologías y estructuras de datos:

- **PySpark**: Un marco de análisis de datos en Python que proporciona una API para trabajar con grandes conjuntos de datos de manera distribuida en un clúster.
- **Jupyter Notebook**: Una herramienta interactiva que permite crear y compartir documentos con código en vivo, ecuaciones, visualizaciones y texto narrativo.
- **RDD (Resilient Distributed Dataset)**: Una colección distribuida y tolerante a fallos de objetos que puede ser procesada en paralelo.
- **DataFrames de PySpark**: Una estructura de datos tabular distribuida basada en RDD que permite realizar consultas SQL y trabajar con datos de manera eficiente y escalable.

## Análisis en un clúster de CESGA

Este análisis se llevó a cabo en un clúster proporcionado por el Centro de Supercomputación de Galicia (CESGA). El clúster permite ejecutar el análisis en paralelo utilizando múltiples nodos para mejorar el rendimiento y la escalabilidad.

## Contenido del repositorio

- `ExercicioRDDs.ipynb`: El notebook de Jupyter que contiene el análisis completo de los datos de viajes en taxi de Nueva York. Incluye código en vivo y explicaciones detalladas de cada paso del análisis.

## Cómo ejecutar el análisis

Para ejecutar el análisis en tu propia máquina o en un clúster, sigue estos pasos:

1. Clona este repositorio en tu máquina local o en un nodo del clúster.
2. Instala Jupyter Notebook y PySpark si aún no lo tienes.
3. Abre el archivo `ExercicioRDDs.ipynb` en Jupyter Notebook.
4. Ejecuta las celdas del notebook para llevar a cabo el análisis.

## Autor

[Martín Pose](https://github.com/martypose)
