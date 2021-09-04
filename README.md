# Primer Avance PIA
=====================================================================
## Integrantes del Equipo

Morales Rodríguez Adrián Esteban 1919724\
Vázquez Avila Noé Orlando 1678410

=====================================================================
## Introducción

### *Problematica:* 
En un restaurante de mariscos, ha habido mucha perdida de inventario (ingredientes y bebidas), y cuando <br />un cliente pide alguna orden, es en ese momento que se dan cuenta que no hay ingredientes suficientes <br />para realizar la orden, además de no llevar un registro de la entrada y salida de dinero en ventas, y ademas <br />de apuntar en un papeles(los cuales suelen perderse y retrasar a orden del cliente) las ordenes de los clientes.

### *Propuesta Técnica*
**Entidades:**
- Empleado
- Cocina
- Caja
- Orden
- Inventario

**Atributos:**
- Empleado contará con un número de id, ademas de ingresar su nombre y cual es su puesto dentro del restaurante.
- *crearOrden();* Esta función servirá para que la persona que este trbajando como mesero genere de una manera mas <br />sencilla la orden, generando un número de orden.
- *recibirOrden();* Esta función se usara en la Clase Cocina y Caja, recibirá el número de orden enviada desde la Clase Orden. 
- *reportarInventario();* En la Clase Cocina se podra hacer el reporte, generando un número de reporte, si faltase o <br />este a punto de acabarse algun ingrediente o bebida.
- *Ordenlista();* Dentro de la Clase Cocina se verifica cuando la orden este terminada y lista para servirse.
- *pago();* En esta funcion se calcula la cantidad a pagar por parte del cliente y se ingresa la cantidad con la que <br />pagó el cliente, para finalmente regresar el cambio.
- *generarticket();* Despues de recibir la orden y el pago realizado, se genera el ticket donde se muestra la cantidad de <br />platillos y bebidas, y el precio a pagado y el cambio recibido.
- *imprimirticket();* Se manda a imprimir el ticket.
- *recibirReporte();* Esta función pertenece a la Clase Inventario, y le servira a la persona que sea administrador <br />recibir los reportes de ingredientes o bebidas faltantes.
- *actualizarInventario();* Finalmente cuando ya se halla realizado y recibido la mercancia para el inventario, se actualiza <br />los datos dentro de la CLase Inventario.

**Funcionalidades:**
- *sesion();* En esta funcion se incia la sesion para un empleado nuevo o se ingresa la id de un empleado existente.

=====================================================================
