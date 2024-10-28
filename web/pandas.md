## Análisis y manipulación de datos con pandas

<img src="images/pandas_2.png">

En cierta etapa, se despliega como herramienta estratégica en la compañía Power BI. La jefatura empieza a generar informes con ella como base de nuestra labor diaria. Lo hace importando datos desde ficheros excel volcados a diario de la base de datos de la Intranet. Descubro así que puedo acceder a muchos de los datos que necesito, utilizando estos ficheros excel.

Refactorizo gran parte de las consultas en mi módulo. Sustituyo el scraping (relativamente lento) por el tratamiento de estos ficheros excel. Elijo utilizar la librería pandas, que me parece interesante por su capacidad de cruzado, manejo de elevados volumenes de datos (como es el caso), y rapidez de ejecución.

Sobre este nuevo módulo, desarrollo scripts que, tras una pesada carga inicial, proporcionan consultas muy rápidas y completas sobre casi todos los datos relevantes que utilizo para analizar pedidos. También generan informes en excel que son entrada a diversos scripts de análisis y generación de pedidos. El rendimiento en mi día a día aumenta bastante.


#### librerías Python utilizadas:
- pandas
- os
- sys
- colorama
- openpyxl


Estos desarrollos han estado plenamente operativos. Pero no estoy autorizado a publicarlos pues exponen detalles internos de los sistemas de mi anterior empresa.
