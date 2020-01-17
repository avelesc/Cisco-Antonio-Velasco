# Cisco-Antonio-Velasco

Para este ejercicio he creado 5 redes que están dispuestas de la siguiente manera:
Una primera red en la que crearé 3 subredes, la segunda tendrá 8 ordenadores mediante DHCP, la tercera tiene 4 ordenadores por DHCP, la cuarta tiene 4 con IP fija y cinco ordenadores por DHCP conectados a un punto de acceso y en la última 5 ordenadores con IP fija y tres servidores de red que detallaremos más adelante. 
Configuramos los routers para que los equipos tengan acceso y conexión entre ellos, y en las redes que necesiten DHCP he puesto un servidor con el servicio de DHCP activado para que esos equipos tengan una dirección asignada automáticamente.
Los servidores de red tendrán una página alojada en la cual guardaremos distintas imágenes que se detallan en la práctica.
Además de eso en esta red he colocado un servidor de DNS para que cualquier equipo de la red poniendo la IP del servidor o de la página web pueda acceder a dichas fotografías.
Las subredes las he configurado para que la primera soporte 100 host, la segunda 30 y la última 6.
Las tenía configuradas para que una pudiera acceder al exterior pero Packet Tracer no permite esa opción ya que da error si intentas hacer ping desde la última subred al exterior.
