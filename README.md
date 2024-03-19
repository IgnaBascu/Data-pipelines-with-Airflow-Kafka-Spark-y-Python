# Data-pipelines-with-Airflow-Kafka-Spark-y-Python
Creación de una Pipeline de automatización de flujo de datos de API OpenWeather con las tecnologías Airflow/Kafka/Spark

* **Objetivo del proyecto:**

Este proyecto esta basado en el tutorial del canal de Banana Code (https://www.youtube.com/watch?v=3Lwl5GRVrfM) el cual es una introducción para entender como funciona una pipeline de streaming con diversas herramientas con fines educativos.

* **Tecnologías utilizadas:**

  * Python
  * Airflow
  * Kafka
  * Spark
  * Ubuntu 22.04.3 LTS para Windows 11
  * Visual Code
 
---
## Diagrama Pipeline

asdasd

---
## Resumen

### API OpenWeather
Este proyecto inicia obteniendo una API Key de la API OpenWeather para poder usar sus servicios. Se utilizaron las coordenadas de la ciudad de Santiago para obtener la temperatura y otras caracteristicas en tiempo real.

### AirFlow
La plataforma Apache Airflow permite la creación, la planificación y el seguimiento de flujos de trabajo a través de la programación informática.

Como se utilizaba el SO Windows 11, se procedió a utilizar el Subsistema de Windows para Linux (WSL) para instalar Ubuntu desde la Microsoft Store y así poder instalar la plataforma y manejarla.

*Se creó una variable de ruta con fines de comodidad de uso*

### Kafka
Apache Kafka es una popular plataforma de streaming de eventos que sirve para recoger, procesar y almacenar datos de eventos de streaming o datos sin principio ni final concretos.

Se inició y probó la plataforma en base a la guía de Apache Kafka (https://kafka.apache.org/quickstart)

### Spark
Apache Spark es un motor unificado de analíticas para procesar datos a gran escala que integra módulos para SQL, streaming, aprendizaje automático y procesamiento de grafos.

Se configuró a nivel local con un worker escuchando las peticiones de las tareas de Airflow por medio de un script python (app.py).

---

## Conclusión

Este tipo de proyectos son una excelente manera de introducirse en el tema y adquirir experiencia práctica en el campo de la ingeniería de datos. Genera la capacidad de diseñar, implementar y mantener pipelines de datos completos, desde la adquisición hasta la presentación de resultados en terminal com fines de entender las herramientas usadas y su implementación.


