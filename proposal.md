# Propuesta TP DSW

## Grupo
### Integrantes
* Mansilla Gonzalo Leg: 49859
* Simbel Pagliero,Santino Lucio Leg: 49438
* Fernández, Martina Leg: 48033
* Vazquez, Sabrina Leg: 47469 


### Repositorios
* [frontend app](https://github.com/gonza2nm/cineUTN-frontend)
* [backend app](https://github.com/gonza2nm/cineUTN-backend)

## Tema: Cine
### Descripción
Cine UTN es una franquicia de cines. Un cine tiene un dueño y sus respectivos encargados. El dueño registra su nuevo cine, puede modificar salas y administrar a los encargados. Además se encarga de todo lo referido a los sorteos y eventos.
Los encargados administran las películas, las comidas, los géneros, y las promociones.  
Los clientes deben registrarse en el sistema para luego poder hacer la compra de entradas y/o comida. También pueden consultar las películas y próximos estrenos. 

### Modelo
* [Modelo](https://app.diagrams.net/#G11WrESic0HIv2KUoiPSt1pC8J9RV4a3Y3#%7B%22pageId%22%3A%22qWFum7RDt3cktn1nixqp%22%7D)
imagen del modelo:

*Nota*: incluir un link con la imagen de un modelo, puede ser modelo de dominio, diagrama de clases, DER. Si lo prefieren pueden utilizar diagramas con [Mermaid](https://mermaid.js.org) en lugar de imágenes.

## Alcance Funcional 

### Alcance Mínimo

*Nota*: el siguiente es un ejemplo para un grupo de 3 integrantes para un sistema de hotel. El 

Regularidad:
|Req|Detalle|
|:-|:-|
|CRUD simple|1. CRUD Tipo Habitacion<br>2. CRUD Servicio<br>3. CRUD Localidad|
|CRUD dependiente|1. CRUD Habitación {depende de} CRUD Tipo Habitacion<br>2. CRUD Cliente {depende de} CRUD Localidad|
|Listado<br>+<br>detalle| 1. Listado de habitaciones filtrado por tipo de habitación, muestra nro y tipo de habitación => detalle CRUD Habitacion<br> 2. Listado de reservas filtrado por rango de fecha, muestra nro de habitación, fecha inicio y fin estadía, estado y nombre del cliente => detalle muestra datos completos de la reserva y del cliente|
|CUU/Epic|1. Reservar una habitación para la estadía<br>2. Realizar el check-in de una reserva|


Adicionales para Aprobación
|Req|Detalle|
|:-|:-|
|CRUD |1. CRUD Tipo Habitacion<br>2. CRUD Servicio<br>3. CRUD Localidad<br>4. CRUD Provincia<br>5. CRUD Habitación<br>6. CRUD Empleado<br>7. CRUD Cliente|
|CUU/Epic|1. Reservar una habitación para la estadía<br>2. Realizar el check-in de una reserva<br>3. Realizar el check-out y facturación de estadía y servicios|


### Alcance Adicional Voluntario

*Nota*: El Alcance Adicional Voluntario es opcional, pero ayuda a que la funcionalidad del sistema esté completa y será considerado en la nota en función de su complejidad y esfuerzo.

|Req|Detalle|
|:-|:-|
|Listados |1. Estadía del día filtrado por fecha muestra, cliente, habitaciones y estado <br>2. Reservas filtradas por cliente muestra datos del cliente y de cada reserve fechas, estado cantidad de habitaciones y huespedes|
|CUU/Epic|1. Consumir servicios<br>2. Cancelación de reserva|
|Otros|1. Envío de recordatorio de reserva por email|

