# __Inicio de sesión__

__El login se hace en el portal de chartio:__

[chartio.com](https://chartio.com)

![reportes_001.png](https://raw.githubusercontent.com/EgaleanaDexperts/services-manual/master/manual/reportes_001.png)

En la página principal, hacer clic en Login para iniciar el proceso de inicio de sesión.

![reportes_001.png](https://raw.githubusercontent.com/EgaleanaDexperts/services-manual/master/manual/Images/reportes_002.png)

En la ventana de login, hay que ingresar las credenciales de inicio de sesión. Si la cuenta de Chartio está ligada a una cuenta de debug Experts, hay que iniciar sesión previamente con la cuenta de Debug Experts en cuestión, si hay un inicio de sesión actual en el navegador web, el inicio de sesión en Chartio es inmediato dando clic en el botón de Login with Google.

En el panel de inicio de Chartio, hallarán distintos dashboards disponibles. Cada cliente tiene un dashboard. En este ejemplo, se accederá al Dashboard del TEPJF haciendo clic en el dashboard llamado "Reporte Firewall TEPJF".

Esta es la vista del Dashboard del "Reporte Firewall TEPJF". Del lado izquierdo se observan los elementos que estarán disponible en el reporte generado, mientras que del lado derecho se observan los elementos de edición del Dashboard. No todos estos elementos estarán disponibles porque dependen de los permisos de escritura/lectura del usuario que accede.

Antes de generar un reporte, se deben aplicar filtros en el reporte, para ello, se hará uso de los filtros que se encuentran en el inicio del Dashboard. Tales filtros determinan el Sitio, en caso de que el cliente cuente con más de un sitio, además del mes del reporte que se desee generar.

Para seleccionar el sitio, solo basta con hacer clic en el filtro "Sitio"; un menú desplegable aparecerá indicando los sitios disponibles. En este caso, se seleccionará el sitio llamado "Sala Superior".


Se repite el mismo procedimiento para el filtro "Mes". En este caso se seleccionará el mes de Abril.

Tras haber usado ambos filtros, la información corredspondiente será poblada en el dashboard.

Antes de continuar, se recomienda ampliamente que se revisen que en todas las páginas aparezca información referente al Firewall y que en especial no se presenten errores. Habrá situaciones en la que algun chart no contengan ningún tipo de dato, eso puede ser normal en casos en el que no exista información. Independiente de que sea un comportamiento esperado, se recomienda reportar este tipo de situaciones.

Tras haber finalizado la revisión del dashboard, se puede descargar e imprimir el reporte. Para ello, se debe hacer clic en el botón "Download", ubicado en la parte inferior derecha del Dahsboard y elegir la opción "Download as PDF". El reporte será entonces generado con la información desplegada en el Dashboard y posteriormente descargado al navegador que se esté utilizando. Este proceso puede llevar de unos segundos a un par de minutos.

EDICIÓN DEL REPORTE.

El reporte en pdf contiene la información filtrada del Dashboard, además de una serie de estampas de tiempo, número de página y marcas de agua que Chartio imprime en el documento. El siguiente paso es borrar tales elementos.

Con un editor de pdfs, en caso de este ejemplo se usará el editor de pdf de preview, se cubrirán los elementos que se encuentran en la parte superior e inferior de todas las páginas del documento.


Se utilizarán autoformas rectangulares sin borde, que empaten con el color del fondo del reporte y se colocarán a modo que bloqueen los elementos que deseamos cubrir.

Tras haber cubierto la primer página, se seleccionan las dos autoformas usadas y se copian y pegan en las siguientes páginas.


Al final obtendremos un documento pdf sin las marcas que Chartio pone. Para hacer los cambios permanentes, solo basta con guardar el documento o sobreescribir el que se había descargado.

Esto finaliza el proceso de generación de un reporte de Chartio.















