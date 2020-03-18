# Respaldo para reporte de Nipper

Se requieren los siguientes archivos para poder obtener el reporte de Nipper 

objects.C
objects.C_41
objects_5_0.C
rules.C
rulebases.fws
rulebases_5_0.fws

Para poder copiar estos archivos se levantara una Maquina virtual para no hacer cambios en el equipo del cliente. 
Se requiere sacar un resplado de la politica de seguridad configurada en la consola que administra los FW usando la herramienta "Migration Tools", a continuacion se muestran los pasos a seguir para sacar dicho respaldo: 

1.- Conectarse por linea de comando al "Security Management Server"
2.- Entrar al modo experto con el comando "expert"
3.- Ir a la carpeta "/opt/CPsuite-R80.20/fw1/bin/upgrade_tools" 
cd $FWDIR/bin/upgrade_tools
4.- Crear el respaldo de la configuracion: 
[Expert@MGMT:0]# ./migrate export repaldo_FW_fwcha.tgz
5.- En este punto te pedira cerrar todos los clientes conectados al Security Management Server, despues de validar que todos los clientes se hayan cerrado continuar presionando la letra "y".
6.- Posterior te confirmara que el archivo se creo de forma satisfactoria. 
7.- Sacar el archivo del Security Management Server, se puede usar el cliente WinSCP para copiar el archivo. 

Para poder copiar los archivos necesarios para realizar el reporte, se montara el respaldo en una maquina virtual. 

1.- Crear Maquina Virtual con la misma version de GAIA del Security Management Server. 
2.- Copiar el archivo a la Maquina Virtual antes mencionada. 
3.- Conectarse por linea de comando a la Maquina Virtual 
2.- Entrar al modo experto con el comando "expert"
3.- Ir a la carpeta "/opt/CPsuite-R80.20/fw1/bin/upgrade_tools" 
cd $FWDIR/bin/upgrade_tools
4.- Cargar el respaldo de la configuracion: 
[Expert@MGMT:0]# ./migrate import repaldo_FW_fecha.tgz 
5.- Confirmar la carga del respaldo en la Maquina Virtual. 
6.- Validar que la configuracion se haya cargado de forma correct, conectarse por el Smarconsole. 

Sacar archivos de Maquina Virtual. 

1.- 
2.-
