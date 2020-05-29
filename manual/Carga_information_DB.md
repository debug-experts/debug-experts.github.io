# Procedimiento para cargar información de Firewall a base de datos por medio de aplicaciones web

Objetivo: Este manual documenta el procedimiento para cargar información de firewall recolectada (CPView) y procesada por Nipper (Reporte de análisis de vulnerabilidades) a una base de datos; dicha base de datos es empleada por Chartio para la creación de gráficas y tablas que contendrá el reporte generado por Debug Experts.

**a) Carga de información de Nipper a base de datos**

Antes de presentar el procedimiento a seguir para cargar la información a la base de datos, es importante que se posea la siguiente información:

   * Archivos en formato CSV generados por Nipper que corresponde a información de tabla __comprimidos__ en **ZIP**. Los archivos de interés son aquellos cuyo nombre poseen la palabra ***table***; ejemplo de archivo: *TRIFE_Mayo - table 32 The Issue Classification.csv*
   * ***Cliente*** y ***sitio*** al cual pertenece el o los firewalls
   * ***Fecha*** cuando la información de firewall fue recolectada

   Una vez que se tengan dicha información, el procedimiento para cargarla a la base de datos es la siguiente:

   i) Dirigirse a la aplicación web que se localiza en el siguiente enlace [Load Nipper data to db](https://doc.dexperts.com.mx:8123/loadnipper).
   ![loadDB_pic1.png](Images/loadDB_pic1.png)

   ii) Elegir el archivo **ZIP** que contiene la información de las tablas generadas por Nipper en formato CSV, y dar *click* en la opción *Choose*.
   ![loadDB_pic2.png](Images/loadDB_pic2.png)

   iii) Insertar la fecha en la cual fue recolectada la información de firewall por medio del calendario.
   ![loadDB_pic3.png](Images/loadDB_pic3.png)

   iv) Elegir el *cliente* y *sitio* al cual pertenece el o los firewalls. La aplicación desplegará la lista del *cliente* y *sitio*.
   ![loadDB_pic4.png](Images/loadDB_pic4.png)

   v) Una vez que **toda** la información fue definida en la aplicación web, se deberá dar *click* en el botón **Submit** para que dicha información sea cargada a la base de datos.

   vi) Una vez que el proceso de carga de información haya finalizado, la aplicación web lanzará el siguiente mensaje, indicando que la información fue cargada a la base de datos de manera satisfactoria.
![loadDB_pic5.png](Images/loadDB_pic5.png)

**b) Carga de información de CPView a base de datos**

Antes de presentar el procedimiento a seguir para cargar la información a la base de datos, es importante que se posea la siguiente información:

   * Archivo CPViewDB contenido dentro del CPInfo. El archivo tiene extensión *.dat*
   * *Datacenter* al cual pertenece el firewall
   * Firewall al cual pertenece la información recolectada
   * Fecha cuando la información de firewall fue recolectada

   Una vez que se tengan dicha información, el procedimiento para cargarla a la base de datos es la siguiente:

   i) Dirigirse a la aplicación web que se localiza en el siguiente enlace [Load CPView data to db](https://doc.dexperts.com.mx:8123/loadcpview).
   ![loadDB_pic6.png](Images/loadDB_pic6.png)

   ii) Elegir el archivo **DAT** que contiene la información de desempeño y salud del firewall (ejemplo: consumo de CPU, memoria, disco, *throughput*, y conexiones), y dar *click* en la opción *Choose*.
   ![loadDB_pic7.png](Images/loadDB_pic7.png)

   iii) Insertar la fecha en la cual fue recolectada la información de firewall por medio del calendario.
   ![loadDB_pic8.png](Images/loadDB_pic8.png)

   iv) Elegir el *cliente*, *sitio*  y el *firewall* al cual pertenece la información. La aplicación desplegará la lista del *cliente*, *sitio* y *firewall*.
   ![loadDB_pic9.png](Images/loadDB_pic9.png)

   v) Una vez que **toda** la información fue definida en la aplicación web, se deberá dar *click* en el botón **Submit** para que la información sea cargada a la base de datos.

   vi) Una vez que el proceso de carga de información haya finalizado, la aplicación web lanzará el siguiente mensaje, indicando que la información fue cargada a la base de datos de manera satisfactoria.
![loadDB_pic5.png](Images/loadDB_pic5.png)
