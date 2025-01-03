<link rel="stylesheet" href="css/styles2.css">


# 2021-2023 Automatizaciones administrativas

Durante este periodo profesional, tomé la iniciativa de automatizar tareas repetitivas, principalmente administrativas, mediante scripts en **Python**. A medida que obtuve acceso a distintas fuentes de datos, aprendí y apliqué diversos enfoques técnicos.

En más de una ocasión, refactoricé mi propio código, observando la importancia de una buena documentación.


## Scraping de Intranet corporativa

Desarrollé un módulo de Python en programación estructurada que aplica técnicas de **web scraping** para extraer información de la Intranet y rellenar sus formularios. Se basa en ficheros de Excel de tamaño mediano y gestiona la lógica de negocio necesaria para preparar los datos que se inyectan en dichos formularios.

#### Librerías Python utilizadas:
- **beautifulsoup**
- **requests**
- **openpyxl**
- **colorama**


## Análisis y manipulación de datos con pandas

Power BI se adoptó ampliamente como herramienta, alimentada por ficheros de Excel volcados desde la base de datos corporativa. Refactoricé gran parte de las consultas en mi módulo, sustituyendo el *web scraping* (más lento) por la manipulación de dichos archivos. Opté por la librería **pandas** debido a su eficiencia en el tratamiento de grandes volúmenes de datos.

#### Librerías Python utilizadas:
- **pandas**


## Refactorización OOP del módulo de scraping

Reescribí por completo el módulo de *scraping* siguiendo un enfoque de Diseño Orientado a Objetos. Creé una jerarquía de clases que me permitirá, en el futuro, abordar de forma eficiente el *scraping* de otros formularios de la Intranet.


## Nuevo sistema de gestión, SQL

La Intranet y el sistema de gestión fueron sustituidos por un end-to-end basado en SAP S/4HANA. Esto modificó por completo el modelo de datos y los flujos de trabajo, haciéndose necesario rediseñar la lógica de gestión y los procesos de obtención de datos en mis módulos y scripts. Cuando obtuve acceso a una réplica de la nueva base de datos corporativa, empecé a dar los primeros pasos para basar la captura de datos en *pyodbc*.

### Librerías Python utilizadas:
- *pyodbc*

