# Propuesta TP DSW

## Grupo
### Integrantes
* Mansilla Gonzalo Leg: 49859
* Simbel Pagliero,Santino Lucio Leg: 49438
* Vazquez, Sabrina Leg: 47469 


### Repositorios
* [frontend app](https://github.com/gonza2nm/cineUTN-frontend)
* [backend app](https://github.com/gonza2nm/cineUTN-backend)
### Deploy
* [CineUTN](https://cineutn.vercel.app/)
Solo funciona lanzando el servidor del back en local hasta el momento
## Tema: Cine
### Descripción
Cine UTN es una franquicia de cines.
Un cine tiene encargados que administran los cines, las películas, los géneros, los productos, las promociones,las salas y los eventos. Asi como tambien de validar las entradas de los usuarios usando codigo QR.

Los clientes pueden consultar películas y próximos estrenos. una vez registrados en el sistema podrán hacer la compra de entradas y/o productos (Los cuales pueden tener promociones). 

Para una película y una sala se generan funciones, de esas funciones se pueden comprar las entradas en lo que es una compra, a la cual se le pueden agregar los productos comprados.


### Modelo
* [Modelo](https://drive.google.com/file/d/11WrESic0HIv2KUoiPSt1pC8J9RV4a3Y3/view?usp=sharing
)
  
* [imagen del modelo](https://drive.google.com/file/d/1eIVTMa1BZejPq6ZIsRK5IbygJdyH3Go3/view?usp=drive_link
)

## Alcance Funcional 

### Alcance Mínimo

Regularidad:
|Req|Detalle|
|:-|:-|
|CRUD simple|1. CRUD Cine<br>2. CRUD Género<br>3. CRUD Usuario|
|CRUD dependiente|1. CRUD Pelicula {depende de} CRUD Genero<br>2. CRUD Sala {depende de} CRUD Cine<br>3. CRUD Funcion {depende de} CRUD Pelicula y CRUD sala| 
|Listado<br>+<br>detalle| 1. Listado de película por cine y genero<br> 2. Mostrar estrenos del próximo mes|
|CUU/Epic|1. Cancelar compra <br>2. Comprar entradas.|

Adicionales para Aprobación
|Req|Detalle|
|:-|:-|
|CRUD |1. CRUD Producto<br>2. CRUD Evento<br>3. CRUD Promocion|
|CUU/Epic|1. Comprar productos <br>2. Promociones de Productos<br>3. Evento|

### Alcance Adicional Voluntario

|Req|Detalle|
|:-|:-|
|Listados |1. Listado de promoción de producto.<br>2.Listado de eventos con filtros por cine|
|CUU/Epic||
|Otros|1. Envío de recordatorio de película por mail.<br> Validar compras con QR|

