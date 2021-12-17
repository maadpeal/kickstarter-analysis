
# Kickstarting with Excel

## Overview of Project

### Purpose

    Analyze a fundraising campaign dataset above to determine what factors 
    were determining for its cancellation, failure and success.
    [Analizar un conjunto de datos de campañas de recaudacion de fondos
    anteriores para determinar que factores fueron determinantes para 
    su cancelacion, fracaso y exito.]

    In this way, Louise can make the decision to make the adjustments
    relevant to her own campaign proposal to have a greater probability of 
    success (data driven).
    [De esta manera louise podra tomar la decision de hacer los ajustes
    pertinentes a su propia propuesta de campaña para tener una mayor
    probabilidad de exito (data driven).]

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date


    From the data set, a pivot table of the set was created (image A-1), 
    which had as a filter the years and the parent_category and as values 
    the count of the results and finally the release dates as rows (image A-2). 
    [Del conjunto de datos se procedio a crear una tabla pivot del conjunto
    de datos (imagen A-1), que tenia como filtro los 
    anos y el parent_category y como valores el conteo de los resultados 
    y finalmente las fechas de lanzamiento como filas(imagen A-2).]
  
![](https://github.com/maadpeal/kickstarter-analysis/blob/main/resources/pivot_table.png) A-1
![](https://github.com/maadpeal/kickstarter-analysis/blob/main/resources/pivot_filters.png) A-2

    Filtering was done by theater only in parent category (image A-3), once done
    perform the insertion of the line graph by clicking on insert, then graphing 
    the lines and then verifying that the x and y axes are on the correct places, 
    then proceeded to edit the colors and finally We would have this analysis 
    completed (image A-4).
    [Se hizo el filtrado por solo theater en parent category(imagen A-3), una vez hecho eso
    realice la insercion de la grafica de lineas dando click en insertar,
    luego grafica de lineas y luego verificando que los ejes x y y estan en
    los lugares correctos, luego se procedio a editar los colores y finalmente
    tendriamos este analisis completado(imagen A-4).]
    
![](https://github.com/maadpeal/kickstarter-analysis/blob/main/resources/filter_category.png) A-3
![](https://github.com/maadpeal/kickstarter-analysis/blob/main/resources/Theater_Outcomes_vs_Launch.png) A-4

### Analysis of Outcomes Based on Goals

    First I made use of the function COUNTIFS() from the sheet kickstarter 
    taking column D which is where the goals are and in number successful, 
    failed, canceled based on the criteria of the first row was generating 
    the pertinent filters (image B-1), for this analysis I only take into 
    account the category plays, for which I do not generate any value in the 
    canceled column, then add the totals of each column with the SUM() function
    and generate the percentages for the relevant columns (image B-2).
    [Primero hice uso de la funcion contar si conjunto apartir de la hoja
    kickstarter tomando la columna d que es donde estan las goals y en 
    number successful, failed, canceled en base a los criterios de
    la primera fila fui generando los filtros pertienentes(imagen B-1), para este analisis
    solo te tomo en cuenta la categoria plays, por lo cual no genero ningun valor 
    en la columna canceled, luego sume los totales de cada columna con la funcion sum
    y genere los porcentajes para las columnas pertienentes(imagen B-2).]
    
![](https://github.com/maadpeal/kickstarter-analysis/blob/main/resources/B-2.png) B-1
![](https://github.com/maadpeal/kickstarter-analysis/blob/main/resources/B-3.png) B-2

    Once the table was completed, I was able to generate the line chart,
    clicking on insert and then verifying that the x and y axes
    and they are where they should be, this point of creation is concluded
    analysis (image B-3).
    [Una vez culminado el cuadro pude generar el grafico de lineas,
    haciendo click en insertar y luego verificando que los ejes x y 
    y estan donde deberian estar, se da por culinado este punto de creacion
    del analisis(imagen B-3).]
    
![](https://github.com/maadpeal/kickstarter-analysis/blob/main/resources/B-4.png) B-3

### Challenges and Difficulties Encountered

    In both cases, obtaining the type of graph that I required was quite easy,
    the complicated thing was in the case of the first to obtain the colors that were
    in the example and in the case of the second because it had not filtered by
    plays and did not take into account the starting point of the ranges, it generated me
    certain differences, but in the end with patience I managed to finish it.
    [En ambos casos obtener el tipo de grafica que requeria fue bastante facil,
    lo complicado fue en el caso del primero obtener los colores que estaban
    en el ejemplo y en el caso del segundo debido a que no habia filtrado por 
    plays y no tomaba en cuenta el punto de partida de los rangos me generaba 
    ciertas diferencias, pero al final con paciencia lo logre culminar.]

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
    1. The best range of times to undertake a campaign of this style is between the months of April to July (image C-1)[El mejor rango de epocas para emprender una campana de este estilo esta entre los meses de abril hasta julio(imagen C-1)].
    2. The worst time to start a campaign comes from September to January (image C-2)[La peor epoca para iniciar una campana viene en los meses de septiembre hasta enero (imagen C-2).]

![](https://github.com/maadpeal/kickstarter-analysis/blob/main/resources/C-1.png) C-1
![](https://github.com/maadpeal/kickstarter-analysis/blob/main/resources/C-2.png) C-2
    
- What can you conclude about the Outcomes based on Goals?
    1. That those campaigns that exceed 10 thousand dollars will have very difficult to be successful (image D-1)[Que aquellas campanas que superen los 10 mil dolares tendran muy dificil tener exito (imagen D-1)]
    2. To have a better chance of success it is good to have a bell that is in the range of 1000 to 5000 dollars (image D-2)[Para tener unas mejores posibilidades de exito esta bien tener una campana que se situe en el rango de los 1000 a 5000 dolares (imagen D-2)]

![](https://github.com/maadpeal/kickstarter-analysis/blob/main/resources/D-1.png) D-1
![](https://github.com/maadpeal/kickstarter-analysis/blob/main/resources/D-2.png) D-2

- What are some limitations of this dataset?
    1. That could be very general if a person is interested in a specific country, perhaps with a dataset focused more on a specific country with specific places, more interesting and particular observations could be achieved[Que podria ser muy general si una persona le interesa un pais determinado, tal vez con un dataset centrado mas en un pais en especifico con lugares concretos se podrian lograr observaciones mas interesantes y particulares]
    2. The year, they are data from at least 4 years ago, with a fresher dataset, more precise information could be given to the person who requires the analysis.[El ano, son datos de hace 4 anos atras como minimo, con un dataset mas fresco se le podria dar una informacion mas precisa a la persona que requiere el analisis.]

- What are some other possible tables and/or graphs that we could create?
    1. The time lapses of the successful and unsuccessful campaigns, a count by days of duration with a bar graph could give us another dimension [Los lapsos de tiempo de las campanas exitosas y fallidas, un conteo por dias de duracion con un grafico de barras podria darnos otra dimension]
