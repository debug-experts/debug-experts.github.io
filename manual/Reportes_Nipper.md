# Como sacar reportes de equipos Checkpoint en Nipper

Para sacar los reportes de algun equipo Checkpoint en Nipper neceesitamos los siguientes archivos: 

- objects.C
- objects.C_41
- objects_5_0.C
- rulebases_5_0.fws

Es necesario que estos archivos se encuentren en la Maquina Virtual con nombre “Nipper-Dex”, consultar el manual “Respaldos_Checkpoint” para tener las indicaciones de como obtener dichos archivos. 

Una vez que los archivos antes mencionados se encuentren en la MV se puede sacar el reporte de Nipper con los siguintes pasos: 

1.- Entrar a la MV Nipper-Dex con IP 172.16.0.223
2.- Validar que existe la carpeta con nombre “C:\Archivos_para_Nipper” dentro de esta carpeta se encuentran distintas carpetas con el nombre de cada cliente de soporte, al momento de hacer este manual se encuentra la carpeta: 

- Infonavit
- TRIFE
- SEDENA

3.- Copiar los archivos en la carpeta que corresponde al cliente, en este ejemplo se obtendra el reporte del TRIFE por tal motivo se copiaran los archivos en la carpeta 
“C:\Archivos_para_Nipper\TRIFE”, es necesario usar esta carpeta, ya que de lo contrario se usara una nueva licencia de Nipper por cada carpeta distinta a esta: 
4.- Abrir la aplicación “Nipper Studio”, el acceso directo se encuentra en el escritorio. 
5.- Ir al menu “File>New Report” se abrira una ventana 
6.- Dentro de la ventana dar click en “Add Directory” y abrira una ventana para seleccionar la carpeta deseada 
7.- Seleccionar la carpeta del cliente en el directorio “C:\Archivos_para_Nipper”, en este ejemplo se seleccionara la carpeta TRIFE, la cual esta en “C:\Archivos_para_Nipper” y dar click en “Seleccionar Carpeta”, se cerrara la actual ventana y nos regresara a la anterior.
8.- Dar click en “Next”
9.- Dar click en “Next” 
10.- Dar click en “Next”
11.- Seleccionar la politica “Standard” y dar click en “OK”
12.- Solamente seleccionar los Firewalls del que se esta obteniendo el report, por ejemplo, FW1-SalaSuperior, FW2-SalaSuperior y Cluster-SalaSuperior y dar click en “ok”.
13.- Dar click en “Finish”, ahora el reporte ya esta creado
14.- Guardar el reporte en formato CSV para poder obtener el reporte mensual que se entregara al cliente, ir al menu “File>Save>Table to CVS”
15.- Validar que este seleccionado “All Report Tables” y dar click en “ok” 
16.- Se abrira una ventana para seleccionar la carpeta donde se guardara el reporte y colocar el nombre del reporte, guardarlo en la carpeta “C:\CSV_para_reporte”. 
Dentro de esta carpeta ya se encuentran las carpetas de los clientes y subcarpetas de cada mes del 2020 por cada Firewall. En este ejemplo se guardaran en la siguiente direccion 
C:\CSV_para_reporte\TRIFE\2020\Mayo\Sala Superior

C:\CSV_para_reporte – Carpeta donde se guardaran todos los archivos CSV de todos los clientes 
C:\CSV_para_reporte\TRIFE – Carpeta del cliente Tribunal Electoral del Poder Judicial de la Federacion 
C:\CSV_para_reporte\TRIFE\2020\Mayo – Todos los archivos de Mayo de 2020
C:\CSV_para_reporte\TRIFE\2020\Mayo\Sala Superior – Archivos del Cluster de Sala Superior 

Colocar el nombre del reporte en este caso sera “TRIFE_Mayo_SalaSuperior” y dar click en “Guardar”






