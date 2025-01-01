## Scraping de Intranet corporativa

<img src="images/imagen_4.jpg">

Mi nueva jefatura se encarga de controlar y gestionar la renovación de pedidos a provedores. Solicita al Departamento de Compras el lanzamiento de pedidos previo análisis de ciertos datos. Es una labor fundamentalmente adminsitrativa y muy manual, que decido sustituir por desarrollos propios.

Empiezo creando un módulo Python que implementa técnicas de web scraping para obtener datos de la Intranet, y permite inyectar en ella los formularios de las diversas solicitudes de pedido.

Sobre esa base, creo scripts que procesan archivos excel, consultan la Intranet, analizan todos estos datos y automatizan en gran medida la solicitud de pedidos. Disminuyo mucho la posibilidad de errores en tareas manuales bastante laboriosas.

Como es común en los desarrollos de scraping, es necesario ir reconstruyendo partes del módulo cuando me encuentro con alguna modificación en la Intranet. Algo que generalmente es excepcional pero en este periodo ocurre mas de una vez. Mantener código creado (¡y olvidado!) hace meses, revela la importancia de documentarlo bien.


#### librerías Python utilizadas:
- beautifulsoup
- requests
- openpyxl
- os
- sys
- colorama
- mi propio módulo de scraping Intranet


#### Utilidades usadas:
- BURP Community Suite

Estos desarrollos han estado plenamente operativos. Pero no estoy autorizado a publicarlos pues exponen detalles internos de los sistemas de mi anterior empresa. Y porqué no decirlo: no estoy especialmente orgulloso del primer código Python escrito mientras iba profundizando en su aprendizaje.