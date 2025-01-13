<link rel="stylesheet" href="css/styles2.css">


# 2021-2023 Automatización de procesos

![Banner](images/imagen_4_1920x150.jpg)


Durante este periodo profesional, automatizo tareas administrativas repetitivas mediante scripts en **Python**, aprendiendo y aplicando diversos enfoques técnicos.

En más de una ocasión refactorizo mi propio código, observando la importancia de una buena documentación.


## Scraping de Intranet corporativa

Desarrollo un módulo de Python en programación estructurada que aplica técnicas de **web scraping** para extraer información de la Intranet y rellenar sus formularios. Se basa en ficheros de Excel de tamaño mediano y gestiona la lógica de negocio necesaria para preparar los datos que se inyectan en los formularios.

#### Librerías Python utilizadas:
- **beautifulsoup**
- **requests**
- **openpyxl**
- **colorama**


## Análisis y manipulación de datos con pandas

Power BI se adopta extensamente como herramienta corporativa, alimentada por ficheros de Excel volcados desde bases de datos departamenmtales. Refactorizo gran parte de las consultas en mi módulo, sustituyendo el *web scraping* (más lento) por la manipulación de dichos archivos. Opto por la librería **pandas** debido a su eficiencia en el tratamiento de grandes volúmenes de datos.

#### Librerías Python utilizadas:
- **pandas**


## Refactorización OOP del módulo de scraping

Reescribo por completo el módulo de *scraping* siguiendo un enfoque de Diseño Orientado a Objetos. Creo una jerarquía de clases que me permitiría, en el futuro, abordar de forma eficiente el *scraping* de otros formularios de la Intranet.


## Nuevo sistema de gestión, SQL

La Intranet y el sistema de gestión son sustituidos por un end-to-end basado en SAP S/4HANA. Esto modifica por completo el modelo de datos y los flujos de trabajo, haciéndose necesario rediseñar la lógica de gestión y los procesos de obtención de datos en mis módulos y scripts. Empiezo a dar los primeros pasos para basar la captura de datos en *pyodbc*.

### Librerías Python utilizadas:
- *pyodbc*

