# Nobel Prize Winners Analysis

### Table of content
### EN
- [About the project](#About-the-project)
- [Objectives](#Objectives)
- [Scope](#Scope)
- [Project Steps](#Project-Steps)
- [Source of Data](#Source-of-Data)
- [Used tools, softwares and platforms](#Used-tools-softwares-and-platforms)
- [Findings](#Findings)
- [Conclusions, Limitations and Recommendations](#Conclusions-Limitations-and-Recommendations)

### ES
- [Sobre el proyecto](#Sobre-el-proyecto)
- [Objetivos](#Objetivos)
- [Alcance](#Alcance)
- [Pasos del Proyecto](#Pasos-del-Proyecto)
- [Fuente de Datos](#Fuente-de-Datos)
- [Herramientas, Softwares y Plataformas Utilizadas](#Herramientas-Softwares-y-Plataformas-Utilizadas)
- [Descubrimientos](#Descubrimientos)
- [Conclusiones, limitaciones y recomendaciones](#Conclusiones-limitaciones-y-recomendaciones)

### About the Project
The Nobel Prize Winners Analysis is a Personal Exploratory Data Analytics Project that involves the data of both female and male Nobel Prize Winners since 1901 to 2019.
The objective of this project was to observe winning gender, location, year and the category trends throught the history of the event.

### Objetives
The main objetive of the Nobel Prize Winners Analysis project is to determine and represent trends related to the gender of winners, their locations, the distribution of awards over the years, and the categories in which they were awarded. Providing information about:

"Total Male Nobel Prize Winners (1901-2019)"
"Total Female Nobel Prize Winners (1901-2019)"
"Total Nobel Prize Winners (1901-2019)"
"Gender Distribution of Nobel Prize Winners by Continent"
"Total Nobel Prize Winners by Continent"
"Distribution of Winners by Category Across Continents"
"Distribution of Female Winners by Category Across Continents"
"Distribution of Male Winners by Category Across Continents"
"Distribution of Winners by Category and Continent"
"Distribution of Male Winners by Category and Continent"
"Distribution of Female Winners by Category and Continent"
"Annual Count of Female Nobel Prize Winners"
"Annual Count of Male Nobel Prize Winners"
"Annual Count of Nobel Prize Winners"

### Scope
This project aims to provide an "easy to digest" visual representation of the dataset for the viewers to identify patterns, insights, and find relationships beetween all the factors in hand to gain a comprehensive understanding of the historical trends and dynamics of the Nobel Prize event.

### Project Steps
1) Obtain data source online, download it to local machine and connect it to the Microsoft Power BI Desktop.
2) Perform initial general cleaning and prepare data to create the table from which the analysis will start by removing duplicated records, accurately manipulating null values and replacing them with "Not registered" value, fixed and handled structural errors like accuratelly asigning datatypes.
3) Determine chart distribution and tones for each page of the dashboard:
  a) Front page
    #773D29 
  b) Total Male Winners Page
    #314959 
    #094780
    #7BB7DF
    #8D9CA6
    #5F818A
  c) Total Female Winners Page
    #A64141
    #DD9898
    #D65454
    #573C3C
  d) Total nobel prize winners
    #574C1A 
    #D6AF00
    #DDC142
    #A38600
4) Create interactive Dashboard that includes:
- Front Page - Pagination
![Captura de pantalla 2024-03-15 173357](https://github.com/RafaellaGuti/Nobel-Prize-Winners-Analysis--Project/assets/138822208/7dc15878-8abc-482a-8ef8-78c4aa19bb2f)

- Page 1 : "Male Nobel Prize Winners in History" that summarizes the ammount of MALE winners, their location, the category and the years.
![Captura de pantalla 2024-03-15 173336](https://github.com/RafaellaGuti/Nobel-Prize-Winners-Analysis--Project/assets/138822208/0161fb5c-6c2b-4454-b27d-bbb99f2be9c1)

- Page 2: "Female Nobel Prize Winners in History" that summarizes the ammount of FEMALE winners, their location, the category and the years
![Captura de pantalla 2024-03-15 173248](https://github.com/RafaellaGuti/Nobel-Prize-Winners-Analysis--Project/assets/138822208/19d776da-ae0c-4ad8-867c-26e16d475b56)

- Page 3: "Total Nobel Prize Winners in History" that answers the questions metioned before regardless of the gender.
![Captura de pantalla 2024-03-15 173309](https://github.com/RafaellaGuti/Nobel-Prize-Winners-Analysis--Project/assets/138822208/dbc98668-8a58-4736-b863-dcb213208e38)

### Source of Data
Source: https://www.kaggle.com/datasets/carrie1/ecommerce-data?resource=download
The dataset was downloaded to the local machine and subsequently uploaded to the Microsoft Power BI Desktop software for further manipulation in the Power Query section.

### Used tools, softwares and platforms
- Microsoft Excel.
- Microsoft PowerBI Desktop.
- www.Flaticon.com - For icons and individual images extraction.
- www.Canva.com - For background images creation.
- www.AdobeColors.com - For Color palette creation.

### Findings
Total winners from 1901 to 2019 in all categories = 2,089
Total female winners from 1901 to 2019 in all categories = 122, Percentage of total 5.9%
Total male winners from 1901 to 2019 in all categories = 1,929, Percentage of total 92.4%
Total multinational organizations winners from 1901 to 2019 in all categories = 38, Percentage of total 1.7%

The most awarded categories in women are:
1. Peace.
2. Literature.
3. Medicine
   
Continent from which the majority of female winners originate and their category:
1. Europe with a total of 59 winners with Literature (23 winners) as the main category.
2. North America with a total of 36 winners with Medicine (14 winners) as the main category.
3. Asia with a total of 16 winners.
   
The most awarded categories in men are:
1. Medicine
2. Physics
3. Chemistry
   
Continent from which the majority of male winners originate:
1. Europe with a total of 248 winners with Medicine (248 winners) as the main category.
2. North America with a total of 705 winners with Physics (186 winners) as the main category.
   
Continent with the most total winners from 1901 - 2019:
1. Europe with 1,118 total winners and Medicine (258 total winners) as the main category.
   
Top Awarded Categories by Country from 1901 - 2019:

Medicine - Europe with 258 total winners.
Physics - Europe with 251 total winners.
Chemistry - Europe with 227 total winners.
Economics - North America with 117 total winners.
Peace - Europe with 128 total winners.
Literature - Europe with 192 total winners.

### Conclusions, Limitations and Recommendations

The distribution of Nobel Prizes between men and women is notably unequal, with an overwhelming majority of male winners compared to female winners. This reflects historical gender disparities in the fields of science, literature, and peace, but also highlights the progress towards gender equity that still needs to be achieved in these fields.

Although the categories of Medicine, Physics, and Chemistry continue to be dominated by male winners, there is an interesting trend in the categories of Peace and Literature, where women are well represented. This suggests a gradual shift in perceptions and opportunities for women in traditionally male-dominated areas.

Geographic analysis reveals that Europe and North America have been the main producing regions of Nobel Prize winners over the years. However, there is potential to further explore the contributions of other regions of the world, such as Asia, Africa, and South America, and better understand their impact on global science, literature, and peace.

Additional examples of questions that can be explored using the interactive dashboard and this base information:

How has the representation of winners from different countries evolved over time?
Is there any correlation between a country's level of development and its success in obtaining Nobel Prizes in certain categories?
Which specific fields within each prize category have been the most innovative or influential in recent history?

  
# ES - Análisis de Ganadores del Premio Nobel

### Sobre el Proyecto
El Análisis de Ganadores del Premio Nobel es un Proyecto Personal de Análisis de Datos Exploratorio que involucra los datos de ganadores del Premio Nobel tanto masculinos como femeninos desde 1901 hasta 2019. El objetivo de este proyecto era observar las tendencias en cuanto al género, ubicación, año y categoría de los ganadores a lo largo de la historia de este evento.

### Objetivos
El principal objetivo del proyecto de Análisis de Ganadores del Premio Nobel es determinar y representar tendencias relacionadas con el género de los ganadores, sus ubicaciones, la distribución de premios a lo largo de los años y las categorías en las que fueron premiados. Proporcionando información sobre:

"Total de ganadores del Premio Nobel masculinos (1901-2019)"
"Total de ganadores del Premio Nobel femeninos (1901-2019)"
"Total de ganadores del Premio Nobel (1901-2019)"
"Distribución de género de los ganadores del Premio Nobel por continente"
"Total de ganadores del Premio Nobel por continente"
"Distribución de ganadores por categoría en todos los continentes"
"Distribución de ganadoras por categoría en todos los continentes"
"Distribución de ganadores por categoría en todos los continentes"
"Distribución de ganadores por categoría y continente"
"Distribución de ganadores masculinos por categoría y continente"
"Distribución de ganadoras femeninas por categoría y continente"
"Recuento anual de ganadoras del Premio Nobel"
"Recuento anual de ganadores del Premio Nobel masculinos"
"Recuento anual de ganadores del Premio Nobel"

 ### Alcance
 
Este proyecto tiene como objetivo proporcionar una representación visual "fácil de entender" del conjunto de datos para que los espectadores puedan identificar patrones, insights y relaciones entre todos los factores presentes para obtener una comprensión integral de las tendencias históricas y la dinámica del evento del Premio Nobel.

### Pasos del Proyecto

1) Obtener la fuente de datos en línea, descargarla en la máquina local y conectarla al Microsoft Power BI Desktop.
2) Realizar una limpieza general inicial y preparar los datos para crear la tabla a partir de la cual comenzará el análisis eliminando registros duplicados, manipulando con precisión los valores nulos y reemplazándolos con el valor "No registrado", corrigiendo y manejando errores estructurales como la asignación precisa de tipos de datos.
3) Determinar la distribución del gráfico y los tonos para cada página del panel:
    a) Página principal
    b) Página de Ganadores Masculinos
    c) Página de Ganadoras Femeninas
    d) Página de Ganadores Totales
4) Crear un panel interactivo que incluya:
- Página principal: Paginación
![Captura de pantalla 2024-03-15 173357](https://github.com/RafaellaGuti/Nobel-Prize-Winners-Analysis--Project/assets/138822208/7dc15878-8abc-482a-8ef8-78c4aa19bb2f)

- Página 1: "Ganadores Masculinos del Premio Nobel en la Historia" que resume la cantidad de ganadores masculinos, su ubicación, la categoría y los años.
![Captura de pantalla 2024-03-15 173336](https://github.com/RafaellaGuti/Nobel-Prize-Winners-Analysis--Project/assets/138822208/0161fb5c-6c2b-4454-b27d-bbb99f2be9c1)

- Página 2: "Ganadoras Femeninas del Premio Nobel en la Historia" que resume la cantidad de ganadoras femeninas, su ubicación, la categoría y los años.
![Captura de pantalla 2024-03-15 173248](https://github.com/RafaellaGuti/Nobel-Prize-Winners-Analysis--Project/assets/138822208/19d776da-ae0c-4ad8-867c-26e16d475b56)

- Página 3: "Total de Ganadores del Premio Nobel en la Historia" que responde a las preguntas mencionadas anteriormente independientemente del género.
![Captura de pantalla 2024-03-15 173309](https://github.com/RafaellaGuti/Nobel-Prize-Winners-Analysis--Project/assets/138822208/dbc98668-8a58-4736-b863-dcb213208e38)


### Fuente de Datos
Fuente: https://www.kaggle.com/datasets/carrie1/ecommerce-data?resource=download
El conjunto de datos fue descargado en la máquina local y posteriormente cargado en el software Microsoft Power BI Desktop para su manipulación adicional en la sección Power Query.

### Herramientas, Software y Plataformas Utilizadas
Microsoft Excel.
Microsoft Power BI Desktop.
www.Flaticon.com - Para la extracción de íconos e imágenes individuales.
www.Canva.com - Para la creación de imágenes de fondo.
www.AdobeColors.com - Para la creación de paletas de colores.

### Descubrimientos

Ganadores totales desde 1901 a 2019 en todas las categorias=  2.089
Ganadoras femeninas totales desde 1901 a 2019 en todas las categorias= 122 Porcentaje a partir del total 5.9%
Ganadores masculinos totales desde 1901 a 2019 en todas las categorias= 1.929 Porcentaje a partir del total 92.4%
Organizaciones Multinacionales ganadoras totales desde 1901 a 2019 en todas las categorias= 38 Porcentaje a partir del total 1.7%

Las categorías más premiadas en mujeres son:
1.Paz.
2.Literatura.
3.Medicina.

Continente del cual provienen la mayoría de las ganadoras femeninas y su categoria: 
1. Europa con total de 59 ganadoras con Literatura (23 ganadoras) como categoria principal.
2. Norte America con un total de 36 ganadoras con Medicina (14 ganadoras) como categoria principal.
3. Asia con un total de 16 ganadoras.


Las categorías más premiadas en hombres son:
1. Medicina
2. Fisica
3. Quimica
   
Continente del cual provienen la mayoría de los ganadores masculinos: 
1. Europa con un total de 248 ganadores con Medicina (248 ganadores) como categoria principal.
2. Norte America con un total de 705 ganadores con Fisica (186 ganadores) como categoria principal.
   

Continente con mas ganadores totales desde 1901 - 2019:
1. Europa con 1.118 ganadores totales y Medicina (258 ganadores totales) como categoria principal.

Principales Categorías Premiadas por País desde 1901 - 2019:
Medicina - Europa con 258 ganadores totales. 
Fisica - Europa con 251 ganadores totales.
Quimica - Europa con 227 ganadores totales.
Economia - Norte America con 117 ganadores totales. 
Paz - Europa con 128 ganadores totales. 
Literatura - Europa con 192 ganadores totales. 

### Conclusiones

La distribución de los premios Nobel entre hombres y mujeres es notablemente desigual, con una abrumadora mayoría de ganadores masculinos en comparación con las ganadoras femeninas. Esto refleja las disparidades de género históricas en los campos de la ciencia, la literatura y la paz, pero también destaca el progreso hacia la equidad de género que aún queda por alcanzar en estos campos.

Aunque las categorías de Medicina, Física y Química siguen siendo dominadas por los ganadores masculinos, se observa una tendencia interesante en las categorías de Paz y Literatura, donde las mujeres están bien representadas. Esto sugiere un cambio gradual en las percepciones y oportunidades para las mujeres en áreas tradicionalmente dominadas por hombres.

El análisis geográfico revela que Europa y América del Norte han sido las principales regiones productoras de ganadores del Premio Nobel a lo largo de los años. Sin embargo, hay un potencial para explorar más a fondo las contribuciones de otras regiones del mundo, como Asia, África y América del Sur, y comprender mejor su impacto en la ciencia, la literatura y la paz a nivel mundial.

Ejemplos adicionales de preguntas que se pueden explorar utilizando el tablero interactivo y esta información base:

¿Cómo ha evolucionado la representación de ganadores de diferentes países a lo largo del tiempo?
¿Existe alguna correlación entre el nivel de desarrollo de un país y su éxito en la obtención de premios Nobel en ciertas categorías?
¿Qué campos específicos dentro de cada categoría de premio han sido más innovadores o influyentes en la historia reciente?
