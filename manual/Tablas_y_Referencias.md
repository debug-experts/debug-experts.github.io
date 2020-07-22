# Tablas y referencias para Bases de Datos.

*__ESTE DOCUMENTO ESTÁ DIRIGIDO PARA LOS ADMINISTRADORES DE LAS BASES DE DATOS Y LAS APLICACIONES DE MANEJO DE ARCHIVOS DE NIPPER__*

La siguiente tabla es una referencia de los datos obtenidos en nipper, en este caso, el nombre de la tabla y cómo deben quedar escritos en las bases de datos.

__[CÓDIGO]__ | __NOMBRE DE TABLA__ | __ID CHART__ | __NOMBRE CHART__
-------------|---------------------|--------------|-----------------
__[R_000]__ | __Security Audit device list__ | __N/A__ | __Dispositivos Analizados__ 
__[R_010]__ | __Firewall Filter Policy Collections Standard administrative service rules on Firewall Policies__ | __1__ |__1. Reglas que permiten acceso a servicios de gestión.__
__[R_020]__ | __Firewall Filter Policy Collections Standard rules allowing packets from any source to network destinations and any port on Firewall Policies__ | __X__ | __XXX__
__[R_030]__ | __Firewall Filter Policy Collections Standard clear-text protocol rules on Firewall Policies__ | __2__ | __2. REGLAS QUE PERMITEN SERVICIOS SIN CIFRADO.__
__[R_040]__ | __Firewall Filter Policy Collections Standard rules allowing packets from a network source to any destination and any port on Firewall Policies__ | __X__ | __XXX__
__[R_050]__ | __Firewall Filter Policy Collections Standard rules allowing packets from any source to network destinations and a port range on Firewall Policies__ | __X__ | __XXX__
__[R_060]__ | __Firewall Filter Policy Collections Standard unnecessary service rules on Firewall Policies__ | __4__ | __4. Reglas que permiten el acceso a servicios potecialmente  innecesarios.__
__[R_070]__ | __Firewall Filter Policy Collections Standard sensitive service rules on Firewall Policies__ | __5__ | __5. Reglas que permiten el acceso a servicios  con datos sensibles.__
__[R_080]__ | __Firewall Filter Policy Collections Standard rules allowing packets to any destination and any port on Firewall Policies__ | __7__ | __7. Reglas que permiten tráfico a cualquier red de destino por cualquier puerto.__
__[R_090]__ | __Firewall Filter Policy Collections Standard rules allowing packets from a network source to network destinations and any port on Firewall Policies__ | __6__ | __6. Reglas que permiten a una red origen a una red de destino por cualquier puerto.__
__[R_100]__ | __Firewall Filter Policy Collections Standard rules allowing packets to network destinations and any port on Firewall Policies__ | __9__ | __9. Reglas que permiten acceso a redes de destino por cualquier puerto.__
__[R_110]__ | __Firewall Filter Policy Collections Standard rules allowing packets from a network source to network destinations and a port range on Firewall Policies__ | __X__ | __XXX__
__[R_120]__ | __Firewall Filter Policy Collections Standard rules allowing packets from any source to network destinations on Firewall Policies__ | __8__ | __8. Reglas que permiten tráfico desde cualquier origen de red a redes de destino específicas.__
__[R_130]__ | __Firewall Filter Policy Collections Standard any protocol rules on Firewall Policies__ | __10__ | __10. Reglas que permiten el acceso a cualquier protocolo.__
__[R_140]__ | __Firewall Filter Policy Collections Standard rule allowing packets to network destinations and a port range on Firewall Policies__ | __X__ | __XXX__
__[R_150]__ | __Firewall Filter Policy Collections Standard rules allowing packets from a network source to any destination on Firewall Policies__ | __X__ | __XXX__
__[R_160]__ | __Firewall Filter Policy Collections Standard rules allowing packets to any destination on Firewall Policies__ | __12 Y 16__ | __12. Reglas que permiten tráfico a cualquier destino.__
__[R_170]__ | __Firewall Filter Policy Collections Standard rules allowing packets from a network source to network destinations on Firewall__ | __13 y 17__ | __13. Reglas que permiten tráfico de red de un origen a destinos de red.__
__[R_180]__ | __Firewall Filter Policy Collections Standard rules not logging allowed network traffic on Firewall Policies__ | __18__ | __18. Reglas que no registran tráfico de red permitido (logging)__
__[R_190]__ | __Firewall Filter Policy Collections Standard rules allowing packets to network destinations on Firewall Policies__ | __15 y 19__ | __15. Reglas que permiten el tráfico a destinos de red.__
__[R_200]__ | __Interfaces__ | __TBD__ | __Interfaces__
__[R_210]__ | __Rutas__ | __TBD__ | __Rutas__
__[R_220]__ | __Memoria__ | __TBD__ | __Memoria__





# Las siguientes tablas no se encuentran en las bases de datos existentes:





__[CÓDIGO]__ | __NOMBRE DE TABLA__ | __ID CHART__ | __NOMBRE CHART__
-------------|---------------------|--------------|-----------------
__[R_301]__ | __NOT FOUND__ | __11__ | __11. Reglas que permiten acceso a un rango de red de destino y a cualquier puerto.__
__[R_302]__ | __NOT FOUND 2__ | __14__ | __14. Reglas que permiten tráfico de un rango de orígenes a destinos de red.__
__[R_303]__ | __NOT FOUND 3__ | __3__ | __3. Reglas sin restricción de servicios para redes específicas.__


__ __
__ __
__ __
__ __

# __TABLAS DE REFERENCIA PARA PALO ALTO NETWORKS__
__ __
__ __

__ORIGINAL NAME CHART__ | __NOMBRE CHART CHARTIO__ | __[CÓDIGO]__
-------------|-------------------------|-------------------------
Audit device scope | Alcance de la auditoria del dispositivo | 1010
Summary of findings for each device | Resumen de hallazgos para cada dispositivo | 1020
Report text conventions | Convenciones de texto del reporte | 1030
Network filter rule actions | Acciones de la regla de filtrado de Red | 1040
Network filter object types | Tipo de objetos del Filtrado de Red | 1050
Security Audit device list | Lista de dispositivos de la auditoria de seguridad | 1060
The impact rating | Calificacion del impacto | 1070
The ease rating | Calificacion de la facilidad | 1080
The fix rating | Calificacion de la solucion | 1090
The Issue Types | Tipos de problemas | 1100
Security Policy rules allowing packets from any source to any destination and any port on PA-Lores-vsys1 | Reglas que permiten paquetes desde cualquier origen a cualquier destino y cualquier puerto | 1110
Security Policy administrative service rules on PA-Lores-vsys1 | Reglas de servicios administrativos | 1120
Security Policy rules allowing packets from any source to network destinations and any port on PA-Lores-vsys1 | Reglas que permiten paquetes desde cualquier origen a destinos de red especificos y cualquier puerto | 1130
Security Policy clear-text protocol rules on PA-Lores-vsys1 | Reglas de protocolos de texto claro | 1140
Security Policy rules allowing packets from a network source to any destination and any port on PA-Lores-vsys1 | Reglas que permiten paquetes desde un origen de red especifico a cualquier destino y cualquier puerto | 1150
Security Policy unnecessary service rules on PA-Lores-vsys1 | Reglas de servicios innecesarios | 1160
Security Policy sensitive service rules on PA-Lores-vsys1 | Reglas con servicios sensibles | 1170
Security Policy rules allowing packets to any destination and any port on PA-Lores-vsys1 | Reglas que permiten paquetes a cualquier destino y cualquier puerto | 1180
Security Policy rules allowing packets from any source to any destination on PA-Lores-vsys1 | Reglas que permiten paquietes desde cualquier origen a cualquier destino | 1190
Security Policy rules allowing packets from a network source to network destinations and any port on PA-Lores-vsys1 | Reglas que permiten paquetes desde un origen de red especifico a destinos de red especificos  por cualquier puerto | 1200
User on PA-Lores with 'admin' in username | Usuario con 'admin' en su nombre de usuario | 1210
Security Policy rules allowing packets to network destinations and any port on PA-Lores-vsys1 | Reglas que permiten paquetes a destinos de red especificos por cualquier puerto | 1220
Security Policy rules allowing packets from any source to network destinations on PA-Lores-vsys1 | Reglas que permiten paquetes desde cualquier origen a destinos de red especificos | 1230
Security Policy any protocol rules on PA-Lores-vsys1 | Reglas que permiten cualquier protocolo | 1240
Security Policy rules allowing packets from a network source to any destination on PA-Lores-vsys1 | Reglas que permiten paquetes desde una fuente de red especifica a cualquier destino | 1250
Weak SNMP community string on PA-Lores | Comunidades de SNMP con strings debiles | 1260
SNMP community string with no view on PA-Lores | Comunidades de SNMP con strings sin vista | 1270
Security Policy rules allowing packets from a network source to network destinations on PA-Lores-vsys1 | Reglas que permiten paquetes desde un origen de red especifico a destinos de red especificos | 1280
Security Policy rules allowing packets to any destination on PA-Lores-vsys1 | Reglas que permiten paquetes a cualquier destino | 1290
Security Policy rule allowing packets to network destinations on PA-Lores-vsys1 | Reglas que permiten paquetes a destinos de red especificos | 1300
Security Audit device conclusions | Conclusiones de la auditoria de seguridad | 1310
Security Audit recommendations list | Lista de recomendaciones de la auditoria de seguridad | 1320
The mitigation classification | Clasificacion de la mitigacion | 1330
The Issue Types | Tipos de problemas | 1340
The Issue Classification | Clasificasion de problemas | 1350




