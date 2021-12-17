
# Kickstarting with Excel

## Overview of Project

### Purpose

    Analizar un conjunto de datos de campañas de recaudacion de fondos
    anteriores para determinar que factores fueron determinantes para 
    su cancelacion, fracaso y exito.

    De esta manera louise podra tomar la decision de hacer los ajustes
    pertinentes a su propia propuesta de campaña para tener una mayor
    probabilidad de exito (data driven).

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
    Del conjunto de datos se procedio a crear una tabla pivot del conjunto
    de datos (imagen A-1), que tenia como filtro los 
    anos y el parent_category y como valores el conteo de los resultados 
    y finalmente las fechas de lanzamiento como filas(imagen A-2).
  
![](https://github.com/maadpeal/kickstarter-analysis/blob/main/resources/pivot_table.png)

    Se hizo el filtrado por solo theater en parent category(imagen A-3), una vez hecho eso
    realice la insercion de la grafica de lineas dando click en insertar,
    luego grafica de lineas y luego verificando que los ejes x y y estan en
    los lugares correctos, luego se procedio a editar los colores y finalmente
    tendriamos este analisis completado(imagen A-4).

### Analysis of Outcomes Based on Goals

    Primero hice uso de la funcion contar si conjunto apartir de la hoja
    kickstarter tomando la columna d que es donde estan las goals (imagen B-1) y en 
    number successful, failed, canceled en base a los criterios de
    la primera fila fui generando los filtros pertienentes(imagen B-2), para este analisis
    solo te tomo en cuenta la categoria plays, por lo cual no genero ningun valor 
    en la columna canceled, luego sume los totales de cada columna con la funcion sum
    y genere los porcentajes para las columnas pertienentes(imagen B-3).

    Una vez culminado el cuadro pude generar el grafico de lineas,
    haciendo click en insertar y luego verificando que los ejes x y 
    y estan donde deberian estar, se da por culinado este punto de creacion
    del analisis(imagen B-4).

### Challenges and Difficulties Encountered

    En ambos casos obtener el tipo de grafica que requeria fue bastante facil,
    lo complicado fue en el caso del primero obtener los colores que estaban
    en el ejemplo y en el caso del segundo debido a que no habia filtrado por 
    plays y no tomaba en cuenta el punto de partida de los rangos me generaba 
    ciertas diferencias, pero al final con paciencia lo logre culminar.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
    1. El mejor rango de epocas para emprender una campana de este estilo esta entre los meses de abril hasta julio(imagen C-1).
    2. La peor epoca para iniciar una campana viene en los meses de septiembre hasta enero (imagen C-2).
    
- What can you conclude about the Outcomes based on Goals?
    1. Que aquellas campanas que superen los 10 mil dolares tendran muy dificil tener exito (imagen D-1)
    2. Para tener unas mejores posibilidades de exito esta bien tener una campana que se situe en el rango de los 1000 a 5000 dolares (imagen D-2)

- What are some limitations of this dataset?
    1. Que podria ser muy general si una persona le interesa un pais determinado, tal vez con un dataset centrado mas en un pais en especifico con lugares concretos se podrian lograr observaciones mas interesantes y particulares
    2. El ano, son datos de hace 4 anos atras como minimo, con un dataset mas fresco se le podria dar una informacion mas precisa para la persona que requiere el analisis.

- What are some other possible tables and/or graphs that we could create?
    1. Los lapsos de tiempo de las campanas exitosas y fallidas, por ahi un conteo por dias de duracion con un grafico de barras podria darnos otros indicadores
