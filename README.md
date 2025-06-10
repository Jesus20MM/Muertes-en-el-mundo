# Análisis Temporal de Causas de Muerte: China vs Estados Unidos (1990-2019)

## Descripción
Este proyecto tiene como objetivo analizar la evolución temporal de las principales causas de muerte a nivel global entre 1990 y 2019, con un enfoque particular en Estados Unidos y China como representantes de Occidente y Oriente, respectivamente.

Se utilizó Python como herramienta principal. El análisis implicó un exhaustivo proceso de limpieza y transformación de datos para reorganizar la tabla original en un formato adecuado para el análisis temporal. Posteriormente, se aplicó una estrategia de agrupación por país, causa y año para estudiar la evolución de las muertes de forma estructurada.

Una parte destacada del proyecto fue el desarrollo de un script en Python que permite generar múltiples visualizaciones iterativas de manera automatizada, lo que facilitó comparar entre países y causas a lo largo del tiempo. Este enfoque habría sido considerablemente más complejo en entornos no programables. El análisis permitió identificar tendencias clave y diferencias notables entre ambos países en cuanto a las causas predominantes de mortalidad.

## Dataset
Se trabajó con un conjunto de datos global que contiene información sobre causas de muerte desagregadas por país y año. El dataset incluye columnas como: país, año, causa de muerte y número de muertes. Fue necesario transformar la estructura original para adaptarla a un formato largo (long format) que facilite el análisis temporal.

📌 **Lugar sugerido para imagen:**  
*Incluye una imagen del dataset original vs el dataset transformado (ej. tabla antes y después del pivoteo). Esto ayudará a visualizar el trabajo de limpieza de datos.*

## Metodología 
1. **Análisis exploratorio de datos (EDA)**  
   En esta etapa se exploró en profundidad el dataset para entender las variables disponibles, su distribución, y patrones generales. Se definieron las preguntas clave en torno a las causas de muerte más frecuentes y su evolución temporal por país. Esta fase fue crucial para comprender las transformaciones necesarias.

   📌 **Lugar sugerido para imagen:**  
   *Gráficos iniciales del EDA: distribución general de muertes por país y año, top 5 causas de muerte globales.*

2. **Limpieza y transformación de datos**  
   Se realizó una limpieza exhaustiva de los datos, que incluyó el manejo de valores nulos y la reorganización de la tabla a un formato largo con el objetivo de facilitar el análisis temporal y las visualizaciones. También se agruparon los datos por país, año y causa para una visualización estructurada.

3. **Generación automatizada de visualizaciones**  
   Se desarrolló un script en Python que genera gráficos iterativos de forma automática, permitiendo una comparación directa entre causas y países. Esto se hizo con el objetivo de automatizar el análisis visual sin intervención manual constante.

   📌 **Lugar sugerido para imagen:**  
   *Ejemplo de visualización generada automáticamente (por país y por causa). Pueden ser gráficos de líneas o áreas.*

4. **Análisis comparativo y extracción de insights**  
   Se compararon tendencias de mortalidad en China y Estados Unidos, observando diferencias y similitudes relevantes. Se identificaron causas dominantes por país y se interpretaron las implicaciones socioeconómicas o sanitarias de dichas tendencias.

## Resultados
- Se generaron múltiples visualizaciones de evolución temporal por causa y país desde 1990 hasta 2019.
- Se observaron diferencias notables en las causas más frecuentes de muerte entre China y Estados Unidos.
- El proceso de automatización de visualizaciones permitió acelerar el análisis exploratorio comparativo entre ambos países.

📌 **Lugar sugerido para imagen:**  
*Coloca dos o tres visualizaciones destacadas que mejor ilustren las diferencias entre China y EUA (por ejemplo, enfermedades cardiovasculares vs accidentes de tráfico).*

## Lecciones aprendidas
- Cómo reorganizar un dataset según el objetivo analítico.
- Aplicación de lógica para automatizar tareas repetitivas como la creación de visualizaciones.
- Ventajas de usar Python frente a otras herramientas más visuales pero menos programables.
- Cómo construir un análisis comparativo basado en datos públicos y automatizado.

## Tecnologías
Pandas, Numpy, matplotlib, seaborn, automatización de scripts de visualización, análisis exploratorio de datos, transformación de datos.

## Mejoras futuras
- Mejorar la estética de los gráficos (colores, tipografías, leyendas).
- Ampliar el análisis a otros países o continentes para identificar patrones más amplios.
- Realizar comparaciones entre países vecinos o similares en desarrollo para analizar la eficiencia de sus sistemas de salud.
- Implementar dashboards o reportes en herramientas como Tableau o Power BI para comunicar mejor los resultados finales.
