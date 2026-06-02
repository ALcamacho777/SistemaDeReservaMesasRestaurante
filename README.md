# SistemaDeReservaMesasRestaurante
Sistema de reserva de mesas para restaurante que permirte al usuario registrarse para poder reservar una mesa en restaurante, el codigo sera en java, debe tener login y se usaran patrones de diseño Prototype,Singleton,Adapter y Bridge, el sistema contenera una base de datos donde se guardara los registros de un usuario y admin.
El sistema consistira en los siguientes pasos, el usuario registrado debera estar logueado en el sistema y cuando una vez se verifica las credenciales se le permitira ingresar al sistema para elegir su reserva, en este caso el usuario podra elegir el numero de mesa.
En el caso del administrador tambien estara ingresado en el sistema y cuando el entre el tendra permisos exclusivos para poder permitir la reserva de la mesa dependiendo si esta esta disponible
Las mesas estaran asignadas por numeros y contaran con 3 estados, disponible, No disponible y En uso
El ciclo es el siguiente:
El usuario o admin ingresan al sistema
Se verifican las credenciales para poder ingresar, en el caso del ususario podra ver la mesa por numero y estado, una vez que seleccione la mesa de su gusto y si esta disponible, se procedera a pasar al metodo de pago, lo cual esto mandara en el sistema un metodo para poder pagar,En el flujo del administrador este verificara las credenciales e ingresara al sistema, una vez dentro le aparecera un mensaje de reserva, el administrador comprobara el pago y procedera a confirmar la reserva en el sistema, el usuario igual le aparece que esta reservado pero el administradorm verifica que realmente este reservado, desde luego esto se confirmara por el pago concluido.
Una vez realizada la reserva y todo el proceso se mostrara en el sistema que este realizada la reserva de la mesa del restaurante.
