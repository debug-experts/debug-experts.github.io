# Tablas y referencias para Bases de Datos

*__ESTE DOCUMENTO ESTÁ DIRIGIDO PARA LOS ADMINISTRADORES DE LAS BASES DE DATOS Y LAS APLICACIONES DE MANEJO DE ARCHIVOS DE NIPPER__*

La siguiente tabla es una referencia de los datos obtenidos en nipper, en este caso, el nombre de la tabla y cómo deben quedar escritos en las bases de datos.

__[CÓDIGO]__ | __NOMBRE DE TABLA__ | __CHART__ | __ID CHART__
-------------|-----------------
__[R_000]__ | __Security Audit device list__ | __Dispositivos Analizados__ | __N/A__
__[R_010]__ | __Firewall Filter Policy Collections Standard administrative service rules on Firewall Policies__ | __1. REGLAS QUE PERMITEN ACCESO A SERVICIOS DE GESTIÓN__ | __1__
__[R_020]__ | __Firewall Filter Policy Collections Standard rules allowing packets from any source to network destinations and any port on Firewall Policies__ | __XXX__ | __X__
__[R_030]__ | __Firewall Filter Policy Collections Standard clear-text protocol rules on Firewall Policies__ | __2. REGLAS QUE PERMITEN SERVICIOS SIN CIFRADO.__ | __2__
__[R_040]__ | __Firewall Filter Policy Collections Standard rules allowing packets from a network source to any destination and any port on Firewall Policies__ | __XXX__ | __X__
__[R_050]__ | __Firewall Filter Policy Collections Standard rules allowing packets from any source to network destinations and a port range on Firewall Policies__ | __XXX__ | __X__
__[R_060]__ | __Firewall Filter Policy Collections Standard unnecessary service rules on Firewall Policies__ | __4. REGLAS QUE PERMITEN EL ACCESO A SERVICIOS POTECIALMENTE  INNECESARIOS.__ | __4__
__[R_070]__ | __Firewall Filter Policy Collections Standard sensitive service rules on Firewall Policies__ | __5. REGLAS QUE PERMITEN EL ACCESO A SERVICIOS  CON DATOS SENSIBLES.__ | __5__
__[R_080]__ | __Firewall Filter Policy Collections Standard rules allowing packets to any destination and any port on Firewall Policies__ | __7. REGLAS QUE PERMITEN TRÁFICO A CUALQUIER RED DE DESTINO POR CUALQUIER PUERTO.__ | __7__
__[R_090]__ | __Firewall Filter Policy Collections Standard rules allowing packets from a network source to network destinations and any port on Firewall Policies__ | __XXX__ | __X__
__[R_100]__ | __Firewall Filter Policy Collections Standard rules allowing packets to network destinations and any port on Firewall Policies__ | __9. REGLAS QUE PERMITEN ACCESO A REDES DE DESTINO POR CUALQUIER PUERTO.__ | __9__
__[R_110]__ | __Firewall Filter Policy Collections Standard rules allowing packets from a network source to network destinations and a port range on Firewall Policies__ | __XXX__ | __X__
__[R_120]__ | __Firewall Filter Policy Collections Standard rules allowing packets from any source to network destinations on Firewall Policies__ | __8. REGLAS QUE PERMITEN TRÁFICO DESDE CUALQUIER ORIGEN DE RED A REDES DE DESTINO ESPECÍFICAS.__ | __8__
__[R_130]__ | __Firewall Filter Policy Collections Standard any protocol rules on Firewall Policies__ | __10. REGLAS QUE PERMITEN EL ACCESO A CUALQUIER PROTOCOLO.__ | __10__
__[R_140]__ | __Firewall Filter Policy Collections Standard rule allowing packets to network destinations and a port range on Firewall Policies__ | __XXX__ | __X__
__[R_150]__ | __Firewall Filter Policy Collections Standard rules allowing packets from a network source to any destination on Firewall Policies__ | __XXX__ | __X__
__[R_160]__ | __Firewall Filter Policy Collections Standard rules allowing packets to any destination on Firewall Policies__ | __12. REGLAS QUE PERMITEN TRÁFICO A CUALQUIER DESTINO.__ | __12__
__[R_170]__ | __Firewall Filter Policy Collections Standard rules allowing packets from a network source to network destinations on Firewall__ | __13. REGLAS QUE PERMITEN TRÁFICO DE RED DE UN ORIGEN A MÚLTIPLES DESTINOS DE RED__ | __13__
__[R_180]__ | __Firewall Filter Policy Collections Standard rules not logging allowed network traffic on Firewall Policies__ | __XXX__ | __X__
__[R_190]__ | __Firewall Filter Policy Collections Standard rules allowing packets to network destinations on Firewall Policies__ | __15. REGLAS QUE PERMITEN EL TRÁFICO A DESTINOS DE RED.__ | __15__
__[R_200]__ | __Interfaces__ | __Interfaces__ | __TBD__
__[R_210]__ | __Rutas__ | __Rutas__ | __TBD__
__[R_220]__ | __Memoria__ | __Memoria__ | __TBD__
__[R_301]__ | __NOT FOUND__ | __11. REGLAS QUE PERMITEN ACCESO A UN RANGO DE RED DE DESTINO Y A CUALQUIER PUERTO.__
__[R_302]__ | __NOT FOUND 2__ | __14. REGLAS QUE PERMITEN TRÁFICO DE UN RANGO DE ORÍGENES A DESTINOS DE RED.__
__[R_303]__ | __NOT FOUND 3__ | __3. REGLAS SIN RESTRICCIÓN DE SERVICIOS PARA REDES ESPECÍFICAS.__