## Procedimiento para cargar información de Firewall a base de datos por medio de aplicaciones web

#### Objetivo: Este manual documenta el procedimiento para cargar información de firewall recolectada (CPView) y procesada por Nipper (Reporte de análisis de vulnerabilidades) a una base de datos; dicha base de datos es empleada por Chartio para la creación de gráficas y tablas que contendrá el reporte generado por Debug Experts.

Antes de presentar el procedimiento a seguir para cargar la información a la base de datos, es importante que se posea la siguiente información:
* 1) Archivos en formato CSV generados por Nipper que correspondende a información de tabla comprimidos en **ZIP**. Los archivos de interés son aquellos cuyo nombre poseen la palabra *table*
* 2) Archivo CPViewDB contenido dentro del CPInfo. El archivo tiene extención *.dat*
* 3) Firewall de donde se obtuvó la información antes mencionada
* 4) Fecha cuando la información de firewall fue recolectada

Una vez que se tengan dicha información, el procedimiento para cargarla a la base de datos es la siguiente:
* 1. Dirigirse a la applicación web que se localiza en el siguiente enlace [WebApp-Nipper](http://172.16.0.225:5050).
![loadDB_pic1.png](https://raw.githubusercontent.com/miguelDE/services-manual/master/manual/Images/loadDB_pic1.png)

* 2. Eligir el archivo **ZIP** que contiene la información de las tablas generadas por Nipper en formato CSV, y dar *click* en la opción *Choose*.
![loadDB_pic2.png](https://raw.githubusercontent.com/miguelDE/services-manual/master/manual/Images/loadDB_pic2.png)

* 3. Insertar la fecha en la cual fue recolectada la información de firewall por medio del calendario. 
![loadDB_pic3.png](https://raw.githubusercontent.com/miguelDE/services-manual/master/manual/Images/loadDB_pic3.png)

* 4. Eliger el *datacenter* al cual pertenece el firewall. La aplicación desplegará la lista de los *datacenters*.
![loadDB_pic4.png](https://raw.githubusercontent.com/miguelDE/services-manual/master/manual/Images/loadDB_pic4.png)

* 5. Una vez que **toda** la información fue definida en la aplicación web, se deberá dar *click* en el botón **Submit** para que la información sea cargada a la base de datos. 

* 6. Una vez que el proceso de carga de información haya finalizado, la aplicación web lanzará el siguiente mensaje, indicando que la información fue cargada a la base de datos de manera satisfactoria. 
![loadDB_pic5.png](https://raw.githubusercontent.com/miguelDE/services-manual/master/manual/Images/loadDB_pic5.png)

