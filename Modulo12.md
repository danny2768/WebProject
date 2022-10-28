## 12.1 Problemas de IPv4
Ipv4 se esta quedando sin direcciones, Ipv6 es el sucesor de Ipv4, Ipv6 cuenta con 128 bits a diferencia de Ipv4 (32 bits)

El desarrollo de Ipv6 incluyo correciones para las limitaciones de Ipv4

# Coexistencai de Ipv4 e Ipv6

El IETF creó difersos protocolos y herramientas para ayudar a los administradores  de redes a migrar a Ipv6, estas se pueden dividir en tres categorias

- # Dual stack
Ejecutan pilas de protocolos Ipv4 e Ipv6 de manera simultanea.
- # Tunneling
Es un método para transportar un paquete Ipv6 a través de una red Ipv4. El paquete Ipv6 se encapsula dentro de un paquete Ipv4.
- # Translation
NAT64 (NEtwoek Address Translation 64) permite a los dispositivos con Ipv6 habilitado que se comuniquen con dispositivos Ipv4 habilitado mediante una tecnica de traduccion a similar a NAT para Ipv4.

# Formatos direcciones Ipv6
- Las direcciones Ipv6 tienen 128 bits de longitud y estan escritas en hexadecimal.
- No se distingue entre mayusculas y minusculas
- En Ipv6 un Hexteto es el termino no oficial para segmento de 16 bits

# Unicast, Multicast, Anycast
- Unicast: Identifica de manera unica una inferfaz de un dispositivo habilitado para Ipv6
- Multicast: Se usan para enviar un único paquete Ipv6 a varios destinos.
- Anycast: Esta es cualqueir direccion unicast Ipv6 que puede asignarse a varios dispositivos. Paquetes anycast se enrutan al dispositivo mas cercano.

# Longitud prefijo Ipv6
La longitud de prefijo en Ipv6 se recomienda que sea de /64 sin enargo puede ir de 0 a 128

# Tipos de direcciones Unicast de Ipv6

- Global Unicast Address(GUA): Similares a las direccciones Ipv4 publicas. Enrutables de internet, globalmente excluidas.

- Link-Local Address(LLA): Requerido para cada dispositivo Ipv6, utilizado para comunicarse con otros dispositivos en la misma red local. LLA no enrutables y confinadas unico enlace.





LoopBack
Ipv4: 127.0.0.1
Ipv6: ::1