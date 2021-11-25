# Estados de juegos y Grupos

### Codigos para declarar Grupos

Se establecen dentro de la `function setup(){}`

Definir grupo

`nombre_Grupo = new Group();`

Agregar grupo a los sprites similares

`nombre_Grupo.add(sprite);`

### Codigos para declarar estados de juegos

Declarar variables con los estados de juegos como variables globales

(opcional los nombres)

`var PLAY = 1;`

`var END = 0;`

`var GameState = PLAY;`

Declarar un codigo condicional en `funcion draw(){}`

```javascript
if (Declarar estado de juego inicial) {
//Mover aqui la velocidad de suelo

//Mover aqui conteo de puntos 
  
//Mover aqui puntuacion
  
//Mover aqui ciclo de repeticion de suelo
 
//Mover aqui salto de trex
  
//Mover aqui efecto gravedad  
  
//Mover aqui nubes

//Mover aqui obstaculos

//Establecer cambio de estado de juego GS
    if (  ) {}
    
} else if (Declarar estado de juego final){

    //Establecer aqui movimiento 0 del suelo

}
```



### Codigo para detener los objetos en el juego



`sprite_Grupo.setVelocityXEach(0);`



### Codigo para cambiar profundidad de capa en los objetos



`sprite.depth = trex.depth;`

`trex.depth = trex.depth + 1;`

