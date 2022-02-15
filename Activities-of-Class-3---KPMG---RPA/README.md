# Activities-of-Class-3---KPMG---RPA

Enunciado(dtMovies):
------------
Se extrajo un listado de peliculas de la platafora IMdb, este mismo se encuentra en un archivo Excel que debe ser:
1. Filtrado por peliculas pertenecientes al año 2016
2. Mantener solo las columnas "title", "release year", "ratingDescription"
3. Tal listado debe ser pegado en un archivo excel de nombre "Movies.xlsx" con nombre de hoja "Movies2016"


Obtendra puntos adicionales, si:
1. Ordena de menor a mayor por la columna "ratingDescription"
2. Filtra las peliculas (de 2016) con "ratingDescription" mayor a 100 que no contengan el signo "_" y copia este listado en una nueva hoja llamada "BestMovies"
3. Utiliza buenas practicas
------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Enunciado(dtBooksAction):
------------
Hay una nueva coleccion de libros de "Action" que se quiere recomendar solo a aquellos Clientes que han comprado Libros de este tipo en el ultimo tiempo.
Para ello se les va a brindar la actividad de "Build dataTable ya completada"


Step by step:
--------------
1. Se crea dt1 con datos de "Client"
2. Se crea dt2 con datos de "Books sold"
3. Se unen por ID las tablas "Books Sold" y "Client" en "dtRecommend"
4. Se agrega la columna "Recommend"
5. Si la fila correspondiente pertenece a Action se recomienda
6. Pasamos la dtRecommend a string
7. Nos quedamos con las filas que solo sean recomendadas
8. Removemos la columna "ID_1"
9. Nos quedamos con las filas que solo sean de Action 
