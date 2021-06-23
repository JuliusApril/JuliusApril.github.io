---
title: "101. Data wrangling (1). Análisis del retraso en los vuelos de EEUU en 2008"
image: 
  path: /images/gettyImages-96665029_resized_2-1440x680.jpg
  thumbnail: /images/gettyImages-96665029_resized_2-small.jpg
  caption: "Photo from [getty images](https://www.gettyimages.es)"
  
---

Ejercicio de exploración y análisis de datos, donde busco patrones y tendencias en los retrasos de los vuelos en EEUU en el año 2008. 

He utilizado el dataset del repositorio de Kagle que se encuentra [aquí](https://www.kaggle.com/giovamata/airlinedelaycauses) que recoge los datos de los vuelos nacionales en EEUU en 2008.



## Indice

* Ingesta de los datos.
* Limpieza y preprocesado.  
* Combinación con otros datasets
* Análisis exploratorio
* Conclusiones


## Hallazgos

1. Existe una relación entre la fecha y el retraso. Días previos a las vacaciones suelen tener mayor número de vuelos y acumulan mayores retrasos.    
2. Los festivos como 4 de julio o 25 de diciembre son los días que acumularon menos retraso.
3. Se observa una tendencia a sufrir mayor retraso cuando hay más tráfico aéreo.
4. El retraso a la llegada muestra una relación lineal conel retraso a la salida.
5. Aviones más antiguos tienden a tener mayores retrasos.

Podéis acceder al notebook en mi repositorio de [github](https://github.com/JuliusApril/Data_wrangling_Vuelos_EEUU-2008).
