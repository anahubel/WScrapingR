# PRÁCTICA 1: WEB SCRAPING

# NOTA: NECESARIO ACTUALIZAR ENFOQUE HACIA FILMAFFINITY UNA VEZ DECIDIDO

# Antecedentes

El objetivo de este repositorio es dar respuesta a la práctica 1 de la asignatura Tipología y ciclo de vida de los datos, impartida dentro del Máster en Ciencia de Datos de la UOC. El objetivo de esta actividad es crear un dataset a partir de los datos contenidos en una página web.


# Descripción

La actividad ha sido desarrollada de forma conjunta por Ana Hubel y Jaime Pérez Ordieres. 

En ella se aplican técnicas de web scraping mediante el lenguaje de programación R para extraer datos de la página filmaffinity.

El objetivo final será la extracción de los datos características (nombre, género, posición) de las películas pertenecientes a los géneros acción, animación, aventuras, bélico, ciencia ficción, cine negro, comedia, drama, fantástico, infantil, intriga, musical, romance, terror, thriller y western. De esta forma se espera generar un dataset limpio que será utilizado caracterizar y dar respuesta a una serie de preguntas, como por ejemplo:

* ¿Está relacionada la popularidad con el género de la película?
*Añadir más preguntas cuando tengamos más variables*

> Tanto las preguntas, como las respuestas al propio enunciado de la práctica, se encuentra recogidos en el archivo html generado por /WScraping/results.Rmd


# Contenido del repositorio

* WScraping
    - main.R: fichero que ejecuta todo el proceso de carga y limpieza
    - scrap.R: contiene el programa que descarga los archivos de la página de imbd
    - clean_df.R: contiene el código que limpia el dataframe y genera el .csv final
    - results.Rmd: este fichero da respuesta a los principales objetivos y requisitos de la práctica. Se carga y analiza el dataframe limpio. Además, se presenta el contexto en el que se ha recopilado la información, se realizan representaciones gráficas del contenido, estadísticas básicas y descripciones de las variables, resultados de correlaciones, clasificaciones, etc.

* test: contiene ficheros donde se realizan pruebas de scraping previas a la generación de los ficheros principales
* License: se ha elegido la licencia MIT para el software desarrollado. Esta licencia no tiene restricciones, permite el uso, copia, modificación, integración con otro software, publicación, distribución, sublicenciamiento y uso comercial del código. Por otro lado, el dataset obtenido mediante el uso del software se encuentran bajo licencia creative commons by-nc-sa 4.0. Esta licencia permite copiar y redistribuir el material en cualquier medio o formato y adaptarlo o modificarlo bajo ciertas condiciones (https://creativecommons.org/licenses/by-nc-sa/4.0/)

# Recusos y bibliografía utilizada

* Simon Munzert, Christian Rubba, Peter Meißner, Dominic Nyhuis. (2015). Automated Data Collection with R: A Practical Guide to Web Scraping and Text Mining. John Wiley & Sons.
