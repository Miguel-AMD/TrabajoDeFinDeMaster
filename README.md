# TrabajoDeFinDeMaster

Este el código para mi trabajo de fin de máster.
Esta desarrollado en la API de JavaScript de Google Earth Engine.

En este trabajo se realiza una comparativa entre los resultados obtenidos por distintos algoritmos de clasificación para la estimación del área quemada con el área estimada por las imágenes generadas por índices espectrales, concretamente los índices BAI y dBAI.
Para la obtención del índice dBAI se generó una imagen de referencia pre-incendio, utilizando todas las imágenes de Marzo.

Los resultados finales son los siguientes:
* Algunas imágenes para visualizar algunos resultados.
* Mapas de color para realizar las comparativas entre los algoritmos y los índices en cada una de las imágenes y por cada uno de los métodos.
* Mapas de color para comparar el porcentaje de coincidencia entre los distintos algoritmos.
* Tablas con el área quemada.

Es necesario silenciar algunas partes del código para obtener los resultados, de lo contrario se obtendrá el error ***computation timed out***
