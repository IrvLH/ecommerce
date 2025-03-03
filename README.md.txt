# Registro de pedidos en un restaurante

Se creara un sistema para dispositivos moviles, de uso casi exclusivo para  
**tablets**, la pagina **principal** ofrece la posibilidad de  
agregar la distribucion _grafica_ de las mesas o podria tenerse en forma  
de _lista_.  
Las **mesas** tendrian los siguientes estados:  
1. Libre
2. Reservada
3. Pendiente(antes de ordenar)
4. Preparacion de platillos
5. Servida
6. (_opcional_)Nueva orden, regresa a punto 4
7. Cuenta solicitada
8. Pagado
9. Esperando limpieza

Cuando una mesa este lista para _ordenar_, se redirige a otra pantalla  
la cual tendra el menu digitalizado en forma de lista, dicha lista tendra  
la siguiente estructura:  

|Imagen|Nombre|Disponibilidad|Precio|cantidad|
|-|-|-|-|-|

Tambien, **El gerente** podra acceder a una pantalla _exclusiva_ que  
requiere ~~contraseña~~, esta pantalla tendra un listado con:  
* No. Mesa
* Nombre mesero/a
* Listado del pedido(_ventana flotante_):
1.Nombre platillo
2.precio individual 
3.precio total
* Hora entrada
* Hora salida
