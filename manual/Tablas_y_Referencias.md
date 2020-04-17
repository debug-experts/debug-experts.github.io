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
__[R_190]__ | __Firewall Filter Policy Collections Standard rules allowing packets to network destinations on Firewall Policies__ | __15__ | __15. Reglas que permiten el tráfico a destinos de red.__
__[R_200]__ | __Interfaces__ | __TBD__ | __Interfaces__
__[R_210]__ | __Rutas__ | __TBD__ | __Rutas__
__[R_220]__ | __Memoria__ | __TBD__ | __Memoria__





# Las siguientes tablas no se encuentran en las bases de datos existentes:





__[CÓDIGO]__ | __NOMBRE DE TABLA__ | __ID CHART__ | __NOMBRE CHART__
-------------|---------------------|--------------|-----------------
__[R_301]__ | __NOT FOUND__ | __11__ | __11. Reglas que permiten acceso a un rango de red de destino y a cualquier puerto.__
__[R_302]__ | __NOT FOUND 2__ | __14__ | __14. Reglas que permiten tráfico de un rango de orígenes a destinos de red.__
__[R_303]__ | __NOT FOUND 3__ | __3__ | __3. Reglas sin restricción de servicios para redes específicas.__
