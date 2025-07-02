# Hospitalary_Network
 
En la actualidad, el correcto diseño y la adecuada seguridad de las redes hospitalarias son aspectos críticos para garantizar la continuidad asistencial, 
la privacidad de los datos clínicos y la disponibilidad de los sistemas médicos. Dado que los hospitales manejan información sensible y dispositivos 
vitales que requieren una conectividad estable y protegida, resulta imprescindible implementar infraestructuras de red seguras, segmentadas y adaptadas a las 
particularidades de este entorno. Además, la creciente incorporación de dispositivos médicos (IoMT) aumenta la superficie de exposición y demanda 
estrategias más restrictivas para su protección.

En este proyecto se presenta el diseño y simulación de dos redes hospitalarias utilizando Cisco Packet Tracer: una propone una red detallada para el Hospital Son Espases y la otra propone una red de interconexión entre los cuatro hospitales más grandes de Mallorca (Son Espases, Hospital de Manacor, Hospital Comarcal de Inca y Son Llàtzer), incorporando diversas medidas de seguridad tanto a nivel físico como lógico. La solución propuesta segmenta la red mediante VLANs para aislar los distintos departamentos del hospital y establece políticas de seguridad mediante listas de control de acceso (ACLs), además de incluir redundancia tanto a nivel de hardware como a 
nivel de enlace, así como protocolos y servicios de red esenciales como DHCP o NAT. Como elemento diferencial, se ha implementado una subred específica para dispositivos IoMT, configurada con restricciones y medidas de seguridad avanzadas que limitan su interacción con el resto de la infraestructura, minimizando así los riesgos asociados a su conectividad.