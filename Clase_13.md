# Uso de la funcion switch 

### Codigo para cargar las imagenes de los obstaculos 

Declarar variables globales para los objetos de cactus

`var nombre_objeto;`

Cargar imagen en `function preload (){}`

`nombre_objeto = loadImage(".png");`

### Codigo para establecer el tablero

Declarar variable score en variables globales

`var score;`

Declar valor de score al inicio de partida en `function setup(){}`

`score = 0;`

Declar conteo de puntos dentro de `function draw (){}` 

`text("Puntuacion: " + score, 500, 50);`

Establecer el conteo de fotogramas por segundo

`score = score + Math.round(frameCount/60);`

### Codigo switch

Establecer proyeccion random dentro de la `funcion cactus(){}`

 `var rand = Math.round (random(1,6));`

Declarar funcion switch     

```javascript
switch (rand) {
  case 1:   nombre_obstaculo.addImage(nombre_objeto);
  break;
  case 2: nombre_obstaculo.addImage(nombre_objeto);
  break;
  case 3: nombre_obstaculo.addImage(nombre_objeto);
  break;
  case 4: nombre_obstaculo.addImage(nombre_objeto);
  break;
  case 5: nombre_obstaculo.addImage(nombre_objeto);
  break;
  case 6: nombre_obstaculo.addImage(nombre_objeto);
  break;
  //Fin de las opciones de imagen 
  default: break;  
                 }
```

