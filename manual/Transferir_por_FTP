# Como transferir archivos del FW a un FTP

Para poder transferir archivos a un servidor FTP se necesita entrar al equipo (Firewall o Consola de Administracion) en modo experto. A continuacion se describen los pasos a seguir. 

1.- Conectarse a la consola de administracion 
2.- Siturse en la carpeta $FWDIR/conf
3.- Validar que se encuentren los siguientes archivos 

- objects.C
- objects.C_41
- objects_5_0.C
- rulebases_5_0.fws

4.- Conectarse al servidor FTP con el siguiente comando: 
ftp 187.188.109.173
4.- Ingresar usuario y contraseña 
5.- Nos mostrara el mensaje “Login successful”
6.- Ejecutar el comando “bin”
ftp> bin

7.- Copiar los archivos antes mencionados con los siguientes comandos: 
ftp> put objects.C
ftp> put objects.C_41
ftp> put objects_5_0.C
ftp> put rulebases_5_0.fws

8.- Validar que los archivos se hayan copiado de forma satisfactoria
ftp> ls

9.- Conectarse a la Maquina Virtual con IP 172.16.0.223 (Nipper-Dex) para almacenar los archivos 
10.- Guardar los archivos en la carpeta correspondiente. 
