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
Cine UTN es una franquicia de cines.
Un cine tiene encargados que se ocupan de todo lo referido a los sorteos y eventos, también administran las películas, los géneros,los productos, las promociones y las salas.

Los clientes pueden consultar películas y próximos estrenos. una vez registrados en el sistema podrán hacer la compra de entradas y/o productos (Los cuales pueden tener promociones). 

Para una película y una sala se generan funciones, de esas funciones se pueden comprar las entradas en lo que es una compra, a la cual se le pueden agregar los productos comprados.


### Modelo
* [Modelo](https://drive.google.com/file/d/11WrESic0HIv2KUoiPSt1pC8J9RV4a3Y3/view?usp=sharing
)
  
* [imagen del modelo](https://drive.google.com/file/d/11WrESic0HIv2KUoiPSt1pC8J9RV4a3Y3/view?usp=sharing
)

## Alcance Funcional 

### Alcance Mínimo

Regularidad:
|Req|Detalle|
|:-|:-|
|CRUD simple|1. CRUD Cine<br>2. CRUD Género<br>3. CRUD Usuario|
|CRUD dependiente|1. CRUD Pelicula {depende de} CRUD Genero<br>2. CRUD Sala {depende de} CRUD Cine<br>3. CRUD Funcion {depende de} CRUD Pelicula y CRUD sala| 
|Listado<br>+<br>detalle| 1. Listado de película por cine<br> 2. Mostrar estrenos del próximo mes|
|CUU/Epic|1. CRUD Entrada depende de función <br>2. Comprar comida.|

Adicionales para Aprobación
|Req|Detalle|
|:-|:-|
|CRUD |1. CRUD Producto<br>2. CRUD Evento<br>3. CRUD Sorteo<br>4. CRUD Promocion(*)|
|CUU/Epic|1. Compra entrada<br>2. Cancelar compra<br>3. Promociones de Productos<br>4. Evento<br>5. Sorteo|

### Alcance Adicional Voluntario

|Req|Detalle|
|:-|:-|
|Listados |1. Listado de promoción de producto.<br>2. Listado películas más vistas<br>3. Mostrar películas que están por salir de cartelera (no más funciones)<br>4. Mostrar detalle compra con QR|
|CUU/Epic|1. Realizar sorteo<br>|
|Otros|1. Envío de recordatorio de película|

