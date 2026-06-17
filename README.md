# telecom-analysis
# Proyecto: Análisis de Clientes y Patrones de Uso en ConnectaTel

## Objetivo del proyecto

El objetivo de este proyecto es analizar el comportamiento de los clientes de ConnectaTel mediante técnicas de limpieza, exploración, segmentación y visualización de datos. Se busca identificar patrones de consumo, segmentos de clientes y oportunidades de negocio que permitan mejorar la oferta de planes y la toma de decisiones comerciales.

## Datasets utilizados

El análisis se realizó utilizando los siguientes archivos:

* **plans.csv**: Información de los planes ofrecidos por ConnectaTel.
* **users_latam.csv**: Datos demográficos y de suscripción de los usuarios.
* **usage.csv**: Registros históricos de llamadas y mensajes realizados por los clientes durante 2024.

## Etapas del análisis realizadas

1. **Carga y exploración de datos**

   * Importación de librerías.
   * Revisión de dimensiones, tipos de datos y estructura de los datasets.

2. **Identificación de problemas de calidad**

   * Detección de valores nulos.
   * Identificación de sentinels y valores inválidos.
   * Revisión de fechas fuera de rango.

3. **Limpieza de datos**

   * Reemplazo de sentinels.
   * Corrección de fechas imposibles.
   * Tratamiento de valores nulos estructurales.

4. **Creación de métricas por usuario**

   * Número total de mensajes.
   * Número total de llamadas.
   * Total de minutos consumidos en llamadas.

5. **Análisis exploratorio**

   * Resúmenes estadísticos.
   * Histogramas y boxplots.
   * Detección de outliers mediante el método IQR.

6. **Segmentación de clientes**

   * Segmentación por nivel de uso.
   * Segmentación por grupos de edad.
   * Visualización de segmentos.

7. **Generación de insights ejecutivos**

   * Identificación de segmentos valiosos.
   * Recomendaciones para nuevos planes y estrategias comerciales.

## Cómo ejecutar el notebook

Este proyecto puede ejecutarse fácilmente en Google Colab.

1. Descargar el archivo `.ipynb`.
2. Abrir Google Colab.
3. Seleccionar **Archivo → Subir notebook**.
4. Cargar el archivo del proyecto.
5. Subir los datasets `plans.csv`, `users_latam.csv` y `usage.csv` a la sesión de Colab.
6. Ejecutar todas las celdas en orden.

## Guía de reproducción

Para reproducir el análisis:

1. Cargar los tres datasets proporcionados.
2. Ejecutar las etapas de limpieza de datos.
3. Generar las métricas agregadas por usuario.
4. Realizar el análisis exploratorio y la detección de outliers.
5. Crear las variables de segmentación por edad y nivel de uso.
6. Revisar las visualizaciones y el análisis ejecutivo para interpretar los resultados.

## Herramientas utilizadas

* Python 3
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Google Colab
