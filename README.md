# Análisis de Causas de Muerte: China vs Estados Unidos (1990-2019)

## Descripción
Este proyecto tiene como objetivo analizar la evolución temporal de las principales causas de muerte a nivel global entre 1990 y 2019, con un enfoque particular en Estados Unidos y China como representantes de Occidente y Oriente, respectivamente.

Se utilizó Python como herramienta principal. El análisis implicó un exhaustivo proceso de limpieza y transformación de datos para reorganizar la tabla original en un formato adecuado para el análisis temporal. Posteriormente, se aplicó una estrategia de agrupación por país, causa y año para estudiar la evolución de las muertes de forma estructurada.

Una parte destacada del proyecto fue el desarrollo de un script en Python que permite generar múltiples visualizaciones iterativas de manera automatizada, lo que facilitó comparar entre países y causas a lo largo del tiempo. Este enfoque habría sido considerablemente más complejo en entornos no programables. El análisis permitió identificar tendencias clave y diferencias notables entre ambos países en cuanto a las causas predominantes de mortalidad.

## Dataset
Se trabajó con un conjunto de datos global que contiene información sobre causas de muerte desagregadas por país y año. El dataset incluye columnas como: país, año, causa de muerte y número de muertes. Fue necesario transformar la estructura original para adaptarla a un formato largo (long format) que facilite el análisis temporal.

## Metodología 
1. **Análisis exploratorio de datos (EDA)**  
   En esta etapa se exploró en profundidad el dataset para entender sus características y patrones generales.. Esta fase fue crucial para comprender las transformaciones necesarias.

2. **Limpieza y transformación de datos**  
   Se realizó una organización exhaustiva de los datos, que incluyó de la tabla a un formato largo con el objetivo de facilitar el análisis temporal y las visualizaciones., además de limitar el análisis a dos países También se agruparon los datos por país, año y causa para una visualización estructurada.

3. **Generación automatizada de visualizaciones**  
   Se desarrolló un script en Python que genera gráficos iterativos de forma automática, permitiendo una comparación directa entre causas y países. Esto se hizo con el objetivo de automatizar el análisis visual sin intervención manual constante.

La siguiente imagen representan la conclusión del trabajo hecho ya que podemos visualizar la variación de muertes en función del tiempo en el intervalo que estamos estudiando y que los datos lo permiten. Análogamente a esta imagen se hicieron las correspondientes iteraciones para obtener la información en forma de visualización automatizada

![image](https://github.com/user-attachments/assets/99d31d65-f7b6-47e9-9054-7d6ed33a6cb6)



4. **Análisis comparativo y extracción de insights**  
   Se compararon tendencias de mortalidad en China y Estados Unidos, observando diferencias y similitudes relevantes. Se identificaron causas dominantes por país y se interpretaron las implicaciones socioeconómicas o sanitarias de dichas tendencias.

## Resultados
- Se generaron múltiples visualizaciones de evolución temporal por causa y país desde 1990 hasta 2019.
- Se observaron diferencias notables en las causas más frecuentes de muerte entre China y Estados Unidos.
- El proceso de automatización de visualizaciones permitió acelerar el análisis exploratorio comparativo entre ambos países.


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
