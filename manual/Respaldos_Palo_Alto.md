# Respaldo para reporte de Nipper

### En Palo Alto solo es necesario obtener un respaldo de seguridad de todo el equipo, el cual trae, además de la configuración de las reglas de seguridad, NAT, etc. información de la configuración del dispositivo tales como la gestión y red. A continuación se indican los pasos a seguir para realizar el respaldo de un equipo firewall Palo Alto Networks.

## ACCESO A LA GUI DE ADMINISTRACIÓN WEB.

### Todos los dispositivos Palo Alto cuentan con una consola de gestión web. Comúnmente se puede acceder a esta vía https, aunque también podría cambiar el puerto por el cual se anuncia tal servicio, en algunos casos puede ser http (tcp80) o incluso tcp8443. Se recomienda consultar con el administrador del sistema Palo Alto cuál es el puerto de acceso en caso de presentar algún problema. La url de acceso es la siguiente:

https://<IP_del_dispositivo>

### Dónde <IP_del_dispositivo> es la dirección IPv4 en donde reside la consola de administración. Si se ingresó la url de forma correcta, probablemente aparecerá una pantalla de error de certificado:

<<Pantalla de error de certificado>>

### Después de aceptar y continuar, debe aparecer una pantalla de login similar a la siguiente:

<<Pantalla de login de palo Alto>>

### La pantalla de inicio de sesión puede cambiar dependiendo de la versión de sistema operativo PANOS que esté instalado en el dispositivo.

### Justo en esta ventana de login es dónde deben ponerse la información de login (Usuario y Contraseña). Tras ingresar los datos de forma satisfactoria, se tendrá acceso al GUI siendo el dasboard la pantalla de inicio que se desplegará.

<<Pantalla del Dashboard de la GUI de Palo Alto>>

### La GUI de Palo Alto tiene distintas secciones, para poder llevar a cabo el respaldo, se debe navegar a las siguientes secciones en el siguiente orden:

Pestaña: Device -> Sección: Setup -> Subpestaña: Operations.

<<Pantalla del la sección Operations >>

### Ubicado en esta sección, en el panel de "Configuration Manager", buscar y hacer clic en la opción " Save Named Configuration Snapshot". Si la opción no aparece, hay que estar seguros que las credenciales con las que se accdió a la GUI tienen los privilegios para poder sacar respaldos.

<<Pantalla de la opción de guardar snapshot>>

### En la ventana que se abre, se debe indicar un nombre para nuestro respaldo. Se recomienda que se use un formato que identifique al cliente, al dispositivo y el momento en el que se ejecutó el respaldo. Un ejemplo sería: "Cliente_Hostname_20200915_1230". El nombre del respaldo tiene un máximo de 32 carácteres, por lo que se debe respetar este límite, de lo contrario el respaldo fallará. Tras indicar el nombre, se debe hacer clic en "OK".

<<Pantallazo de nombre de respaldo>>

### Tras finalizar el respaldo se indicará que el respaldo fue realizado correctamente, lo que nos regresa al panel de opciones. Para obtener una copia del respaldo realizado, se debe hacer clic en la opción "Export named configuration snapshot". En caso de no aparecer esta opción como disponible, se tendrán que verificar los permisos del ususario con los que se inició sesión en la GUI.

### Una nueva ventana aparecerá, en la cual se indica a través de un menú desplegable los archivos disponibles para su descarga. Se debe buscar el archivo del respaldo recién generado y dar clic en OK. La descarga del archivo iniciará en breve a través del navegador.

<<Pantallazo de descarga de respaldo>>

### Después de todas estas actividades, el respaldo habrá sido creado y exportado.