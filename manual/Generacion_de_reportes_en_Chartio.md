# __Inicio de sesión__

__El login se hace en el portal de chartio:__

[chartio.com](https://chartio.com)

![reportes_001.png](https://raw.githubusercontent.com/EgaleanaDexperts/services-manual/master/manual/reportes_001.png)

__En la página principal, hacer clic en Login para iniciar el proceso de inicio de sesión.__

![reportes_002.png](https://raw.githubusercontent.com/EgaleanaDexperts/services-manual/master/manual/Images/reportes_002.png)

__En la ventana de login, hay que ingresar las credenciales de inicio de sesión. Si la cuenta de Chartio está ligada a una cuenta de debug Experts, hay que iniciar sesión previamente con la cuenta de Debug Experts en cuestión, si hay un inicio de sesión actual en el navegador web, el inicio de sesión en Chartio es inmediato dando clic en el botón de Login with Google.__

![reportes_002.png](https://raw.githubusercontent.com/EgaleanaDexperts/services-manual/master/manual/Images/reportes_003.png)

__En el panel de inicio de Chartio, hallarán distintos dashboards disponibles. Cada cliente tiene un dashboard. En este ejemplo, se accederá al Dashboard "Reporte Firewall" haciendo clic en el dashboard llamado "Reporte Firewall".__

![reportes_002.png](https://raw.githubusercontent.com/EgaleanaDexperts/services-manual/master/manual/Images/reportes_004.png)

__Esta es la vista del Dashboard del "Reporte Firewall". Del lado izquierdo se observan los elementos que estarán disponible en el reporte generado, mientras que del lado derecho se observan los elementos de edición del Dashboard. NOTA: No todos estos elementos podrían estar disponibles porque dependen de los permisos de escritura/lectura del usuario que accede. En caso de no presentarse un elemento que no permita continuar con la creación del reporte, favor de reportarlo al equipo de desarrollo del servicio de reportes.__

![reportes_002.png](https://raw.githubusercontent.com/EgaleanaDexperts/services-manual/master/manual/Images/reportes_005.png)

__Antes de generar un reporte, se deben aplicar filtros en el dashboard, para ello, se hará uso de los filtros que se encuentran en el inicio del Dashboard. Tales filtros determinan el Sitio, en caso de que el cliente cuente con más de un sitio, además del mes del reporte que se desee generar.__

![reportes_002.png](https://raw.githubusercontent.com/EgaleanaDexperts/services-manual/master/manual/Images/reportes_006.png)

__Para seleccionar el sitio, solo basta con hacer clic en el filtro "Sitio"; un menú desplegable aparecerá indicando los sitios disponibles. En este caso, se seleccionará el sitio llamado "Sala Superior".__

![reportes_002.png](https://raw.githubusercontent.com/EgaleanaDexperts/services-manual/master/manual/Images/reportes_007.png)

__Se repite el mismo procedimiento para el filtro "Mes". En este caso se seleccionará el mes de Abril (2020-04).__

__Tras haber usado ambos filtros, la información correspondiente al sitio y fecha será mostrada en el dashboard.__

![reportes_002.png](https://raw.githubusercontent.com/EgaleanaDexperts/services-manual/master/manual/Images/reportes_008.png)

__Se debe hacer una revisión del Dashboard, puntualmente que en todas las páginas y charts aparezca información referente al Firewall y en especial no se presenten errores. Habrá situaciones en la que algun chart no contengan ningún tipo de dato, eso puede ser normal en casos en el que no exista información, sin embargo, no debe aparecer ningún mensaje de error o que no se encontraron datos. En caso de presentarse mensajes de error o mensajes que indican que no se tienen datos, se deben reportar este tipo de situaciones con el equipo de desarrollo.__

![reportes_002.png](https://raw.githubusercontent.com/EgaleanaDexperts/services-manual/master/manual/Images/reportes_009.png)

__ __
__ __
# __EDICIÓN DEL RESUMEN EJECUTIVO Y CONCLUSIONES.__

__Dado a que cada reporte contiene información de un sitio y mes distinto y que la información de este varía conforme pasa el tiempo, el texto que acompaña el RESUMEN EJECUTIVO y las CONCLUSIONES también deberán cambiar ligeramente. Tomando esto en consideración, se debe modificar el texto para que vaya acorde a los hallazgos de cada mes.__

__El texto de CONCLUSIONES y RESUMEN EJECUTIVO no puede modificarse en el dashboard directamente. Para tales efectos, se presenta la siguiente hoja de cálculo en este enlace:__

[CONCLUSIONES](https://docs.google.com/spreadsheets/d/1E4HEr_s-1gbaDd7df7QIOizUtiawzFQHnOfnTUAmwxw/edit?usp=sharing)

__NOTA: Se debe acceder al documento con una cuenta de Debug Experts, de lo contrario, el acceso será denegado.__

__La hoja de cálculo contiene una hoja con la información de texto para cada cliente:__

![reportes_018.png](https://raw.githubusercontent.com/EgaleanaDexperts/services-manual/master/manual/Images/reportes_018.png)

__Antes de editar el texto, se debe validar que se encuentra en la hoja de cálculo correspondiente al cliente del que se desea obtener el reporte__

__Las celdas de texto que se deben editar son los mostrados en color verde y son las siguientes: 4B (Conclusiones), 6B (RESUMEN EJECUTIVO DE LA AUDITORÍA), 8B (RESUMEN DE RESULTADOS) y 10B (NOTAS). Se dejó una referencia con el texto que se recomienda seguir, sin embargo, si se desea modificar el texto a modo es posible hacerlo. Tras terminar de editar el texto, no es necesario guardar cambios, ya que la aplicación lo hará de forma automática.__

__Bajo ninguna circunstancia el resto de las celdas de las hojas de cálculo debe ser modificada, ya que contienen datos que permiten a chartio obtener la información correspondiente a cada cliente.__


__ __
__ __
# __IMPRESIÓN DEL REPORTE__


__Tras haber finalizado la revisión del dashboard y la edición de CONCLUSIONES Y RESUMEN EJECUTIVO, se puede descargar e imprimir el reporte. Para ello, se debe hacer clic en el botón "Download", ubicado en la parte inferior derecha del Dahsboard y elegir la opción "Download as PDF". El reporte será entonces generado con la información desplegada en el Dashboard y posteriormente descargado al navegador que se esté utilizando. Este proceso puede llevar de unos segundos a un par de minutos.__

![reportes_002.png](https://raw.githubusercontent.com/EgaleanaDexperts/services-manual/master/manual/Images/reportes_010.png)

![reportes_002.png](https://raw.githubusercontent.com/EgaleanaDexperts/services-manual/master/manual/Images/reportes_011.png)

__Esto finaliza el proceso de generación de un reporte de Chartio.__















