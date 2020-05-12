## Procedimiento para cargar información de Firewall a base de datos por medio de aplicaciones web

#### Objetivo: Este manual documenta el procedimiento para cargar información de firewall recolectada (CPView) y procesada por Nipper (Reporte de análisis de vulnerabilidades) a una base de datos; dicha base de datos es empleada por Chartio para la creación de gráficas y tablas que contendrá el reporte generado por Debug Experts.

Antes de presentar el procedimiento a seguir para cargar la información a la base de datos, es importante que se pose la siguiente información:
* 2) Archivos en formato CSV generados por Nipper que correspondende a información de tabla. Los archivos de interés son aquellos cuyo nombre poseen la palabra *table*
* 2) Archivo CPViewDB contenido dentro del CPInfo. El archivo tiene extención *.dat*
* 3) Firewall de donde se obtuvó la información antes mencionada
* 4) Fecha cuando la información de firewall fue recolectada
