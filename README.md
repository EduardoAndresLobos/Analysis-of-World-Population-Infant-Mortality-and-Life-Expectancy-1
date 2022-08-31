# Analysis-of-World-Population-Infant-Mortality-and-Life-Expectancy-1

Proyecto del curso ofrecido por Datdata en Udemy - Curso Power BI Análisis de Datos y Business Intelligence

En él informe primer Población Mundial, se cargan 3 archivos .xlsx

Population, contiene un listado de países y cantidad de habitantes.
Countries, contiene listado de países, código del país y su respectivo continente.
Países, es el símil de Countries pero en español.
Al querer trabajar los datos en idioma español, se ocultan todos los datos que no se van a utilizar, en este caso la tabla Countries y la columna Country de la tabla Population.

En el segundo Mortalidad y Esperanza de Vida, se cargan 2 archivos .xlsx adicionales

Infant+death+rate, contiene un listado de países y el promedio de muertes infantiles por cada 1000 decesos.
Life+expectancy, contiene un listado de países y el promedio de esperanza de vida.
En el modelo de datos se generan las siguientes relaciones:
Modelo

Informe Población Mundial
Un Treemap con la cantidad de habitantes por país
Una Matriz donde podemos ver el detalle de habitantes por continente y país
Un Mapa donde se puede observar la distribución de países por continente, las burbujas están condicionas al tamaño de la población de cada país
Adicional al filtro segmentado la cantidad de habitantes se agregó uno por continente

Poblacion Mundial

En Power Query se genera una columna condicional para segmentar los países en 4 categorías:

0 - 1M
1M - 10M
10M - 100M
100M >
Con esta segmetación se agrega un filtro

PQ Cantidad Poblacion

Informe Mortalidad Infantil y Esperanza de Vida
Una Matriz donde podemos ver el detalle de habitantes por continente y país, promedio de Esperenza de Vida y promedio de Mortalidad Infantil
Gráfico de dispersión, estudiando la relación entre la esperanza de vida y la mortalidad infantil
Un Mapa donde se puede observar la distribución de países por continente, las burbujas están condicionas al tamaño de la Mortalidad Infantil
Mortalidad
 ![image](https://user-images.githubusercontent.com/112581327/187763506-9ffddded-9c89-454c-adf7-8ccdf7d8090d.png)


En Power Query se genera una columna condicional en cada tabla para segmentar:

Mortalidad Infantil
0 a 10
10 a 25
25 0 50
50 >
PQ Mortalidad

Esperanza de Vida
0 a 60
60 a 70
70 a 80
80 >
Esperanza de vida promedio

Estos dos segmetaciones se usan como filtro sumadas a los dos anteriores.

Algunas conclusiones que se pueden sacar de este informe
A menor esperanza de vida mayor es la mortalidad infantil, siendo el continente africano el más afectado por esta tendencia.
Angola representa el país más afectado ya que su esperanza de vida promedio es de 56 años y una mortalidad infantil de 191 por cada 1000 decesos.
El país menos afectado en Mónaco perteneciente al continente Europeo con una esperanza de vida promedio de 89 años y una mortalidad infantil de 5 por cada 1000 decesos.
