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
  
* [imagen del modelo](https://drive.google.com/file/d/1pCvPwV4grpSzm78EUiYKmU_U586tpWAS/view?usp=drive_link)

*Nota*: incluir un link con la imagen de un modelo, puede ser modelo de dominio, diagrama de clases, DER. Si lo prefieren pueden utilizar diagramas con [Mermaid](https://mermaid.js.org) en lugar de imágenes.

## Alcance Funcional 

### Alcance Mínimo

*Nota*: el siguiente es un ejemplo para un grupo de 3 integrantes para un sistema de hotel. El 

Regularidad:
|Req|Detalle|
|:-|:-|
|CRUD simple|1. CRUD Cine<br>2. CRUD Comida<br>3. CRUD Género<br>4. CRUD Usuario|
|CRUD dependiente|1. CRUD Pelicula {depende de} CRUD Genero<br>2. CRUD Sala {depende de} CRUD Cine|
|Listado<br>+<br>detalle| 1. Listado de película por género -> detalle CRUD película (nombre, descripción)<br> 2. Mostrar estrenos del próximo mes|
|CUU/Epic|1. Dar de alta funciones<br>2. Comprar comida.|


Adicionales para Aprobación
|Req|Detalle|
|:-|:-|
|CRUD |1. CRUD Comida<br>2. CRUD Eventos<br>3. CRUD Sorteo<br>4. CRUD Promociones(*)|
|CUU/Epic|1. Compra entrada<br>2. Cancelar compra<br>3. Promociones de Entrada<br>4. Evento<br>5. Sorteo|


### Alcance Adicional Voluntario

*Nota*: El Alcance Adicional Voluntario es opcional, pero ayuda a que la funcionalidad del sistema esté completa y será considerado en la nota en función de su complejidad y esfuerzo.

|Req|Detalle|
|:-|:-|
|Listados |1. Listado de promoción de comida.<br>2. Listado películas más vistas<br>3. Mostrar películas que están por salir de cartelera (no más funciones)<br>4. Listado por formato de película (2D,3D,4D)|
|CUU/Epic|1. Realizar sorteo<br>|
|Otros|1. Envío de recordatorio de película|

