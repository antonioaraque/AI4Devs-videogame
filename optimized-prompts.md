# Prompts Optimizados para Desarrollo de un Clon de Ghosts 'n Goblins

## 1. Configuración Inicial del Proyecto

```
Eres un experto desarrollador de videojuegos. Qué librería/framework me recomiendas para desarrollar un clon del juego Ghosts 'n Goblins, utilizando HTML5/CSS/Javascript para que el juego sea funcional desde cualquier navegador web?
```

## 2. Estructura del Proyecto

```
Eres un desarrollador de videojuegos experto. Tu tarea es configurar la estructura para un clon de Ghosts 'n Goblins utilizando Phaser 3, un framework popular para juegos HTML5. No quiero escribir ni una línea de código, así que por favor encárgate de toda la creación y configuración de archivos necesaria.

Primero, crea la siguiente estructura de proyecto:
ghosts-n-goblins/
│── index.html
│── main.js
│── assets/
│   │── images/
│   │── audio/

Ejecuta los comandos necesarios usando Python para crear estos directorios y archivos. Una vez creada la estructura, completa index.html y main.js y verifica que Phaser está correctamente agregado.

El juego debe tener una interfaz amigable y atractiva, similar al juego original. Necesitaremos configurar un canvas con las dimensiones adecuadas y preparar un sistema de estados para manejar la pantalla de título, el juego principal y la pantalla de game over.
```

## 3. Implementación del Personaje Principal

```
Eres un desarrollador de videojuegos experto. Tu tarea es continuar configurando el clon de Ghosts 'n Goblins usando Phaser 3. Ya hemos creado la estructura básica del proyecto, y los archivos HTML y JavaScript iniciales están configurados.

A continuación, necesitamos:
- Añadir el personaje principal (Arthur) al juego.
- Asegurar que el personaje principal pueda moverse a la izquierda, derecha, y saltar usando el teclado.
- Implementar la mecánica de disparo del personaje con la lanza.

Tenemos los siguientes sprites ubicados en el directorio assets/images/Arthur:
- Idle.png (Arthur de pie)
- Run.png (Arthur corriendo)
- Jump.png (Arthur saltando)
- Throw.png (Arthur lanzando su arma)
- Death.png (Arthur muriendo)

Los nombres describen la acción para la que está destinado cada sprite. Utiliza Idle.png cuando no haya movimiento, Run.png cuando se mueva, Jump.png al saltar, etc.

Por favor, maneja todas las actualizaciones y configuraciones de archivos necesarias para lograr esto. Una vez completado, prueba el juego para asegurar que el personaje principal puede moverse, saltar y disparar según lo esperado.
```

## 4. Diseño de Sprites para el Personaje

```
Eres un diseñador de videojuegos experto, puedes diseñar estas imágenes:

- Idle.png (Arthur de pie)
- Run.png (Arthur corriendo)
- Jump.png (Arthur saltando)
- Throw.png (Arthur lanzando su arma)
- Death.png (Arthur muriendo)

¿Teniendo que Arthur representa a un guerrero enano?
y ubicarlas en el directorio assets/images/Arthur
```

## 5. Integración de Sprites

```
Actúa como un desarrollador de videojuegos e integra esos sprites diseñados en el videojuego
```

## 6. Implementación del Escenario

```
Eres un desarrollador de videojuegos experto. Tu tarea es continuar configurando el clon de Ghosts 'n Goblins usando Phaser 3. Ya hemos añadido el personaje principal e implementado controles básicos de movimiento.

A continuación, necesitamos:
- Añadir plataformas y el escenario de la primera etapa del juego.
- Asegurar que el personaje principal pueda interactuar con estas plataformas (colisiones).
- Diseñar un nivel que refleje la estética del cementerio del juego original.
- Implementar un sistema de cámara que siga al personaje.

Utiliza sprites de plataformas y elementos del escenario que reflejen la estética del juego original: lápidas, árboles secos, piso de tierra, etc.

Por favor, maneja todas las actualizaciones y configuraciones de archivos necesarias para lograr esto. Una vez completado, prueba el juego para asegurar que el personaje principal puede interactuar correctamente con el escenario.
```

## 7. Mejora de Mecánicas de Salto

```
Actúa como desarrollador de videojuegos. Hay plataformas muy altas a las que personaje Arthur no puede llegar. Se tendría que poder saltar a esas plataformas, pulsando por más de una vez en la flecha arriba del cursor
```

## 8. Diseño de Enemigos

```
Eres un diseñador de videojuegos. Diseña un archivo Zombie.png que es un sprite con múltiples frames para la animación del zombie.
Un zombie es el enemigo del juego.
Los zombies se mueven en sentido contrario a arthur y emergen de la tierra.
```

## 9. Implementación de Enemigos

```
Eres un desarrollador de videojuegos experto. Tu tarea es continuar configurando el clon de Ghosts 'n Goblins usando Phaser 3. Ya hemos añadido el escenario y las plataformas.

A continuación, necesitamos:
- Añadir enemigos básicos al juego (zombies que emergen de la tierra).
- Implementar la lógica de movimiento de los enemigos.
- Implementar la lógica de colisión entre el personaje y los enemigos.
- Añadir la mecánica de pérdida de armadura cuando Arthur es golpeado por primera vez.
- Implementar la lógica de game over cuando Arthur es golpeado sin armadura.

Tenemos un archivo Zombie.png que es un sprite con múltiples frames para la animación del zombie.

Por favor, maneja todas las actualizaciones y configuraciones de archivos necesarias para lograr esto. Una vez completado, prueba el juego para asegurar que el personaje principal puede interactuar con los enemigos y que la lógica de game over funciona según lo esperado.
```

## 10. Solución de Errores de Colisión

```
Ok, ya aparecen en el mismo nivel los Zombies. Ahora estoy teniendo el problema de que cuando un Zombie choca con Arthur tengo este error:
phaser.min.js:1 Uncaught TypeError: Cannot read properties of undefined (reading 'duration')
   at initialize.getFirstTick (phaser.min.js:1:209696)
   at initialize.startAnimation (phaser.min.js:1:196404)
   at initialize.play (phaser.min.js:1:195993)
   at initialize.play (phaser.min.js:1:93184)
   at GameScene.handlePlayerZombieCollision (GameScene.js:487:34)
   at initialize.collideSpriteVsSprite (phaser.min.js:1:619441)
   at initialize.collideHandler (phaser.min.js:1:618810)
   at initialize.collideObjects (phaser.min.js:1:618284)
   at initialize.update (phaser.min.js:1:634473)
```

## 11. Diseño de Armas

```
Eres un diseñador de videojuegos. Diseña archivos png que sean sprites con múltiples frames para la animación de cada una de las armas (lanza, daga, antorcha, hacha) y sus animaciones de impacto.
```

## 12. Implementación del Sistema de Armas

```
Eres un desarrollador de videojuegos experto. Tu tarea es continuar configurando el clon de Ghosts 'n Goblins usando Phaser 3. Ya hemos añadido enemigos básicos e implementado la lógica de game over.

A continuación, necesitamos:
- Mejorar el sistema de armas de Arthur.
- Permitir que Arthur pueda recoger diferentes armas del juego original (lanza, daga, antorcha, hacha).
- Implementar la lógica de colisión entre las armas y los enemigos.
- Añadir efectos visuales y sonoros para el disparo y el impacto de las armas.

Tenemos sprites para cada una de las armas y sus animaciones de impacto.

Por favor, maneja todas las actualizaciones y configuraciones de archivos necesarias para lograr esto. Una vez completado, prueba el juego para asegurar que el sistema de armas funciona correctamente.
```

## 13. Mecánica de Daño a Enemigos

```
Estableced el mecanismo para matar a los zombies: Si el arma cae cerca de su posición también deben morirse. El efecto de morirse del zombie es que parpadee en el primer impacto y posteriormente si hay un segundo impacto el zombie se ponga rojo y desaparezca.
```

## 14. Implementación de Cofres y Power-ups

```
Eres un desarrollador de videojuegos experto. Tu tarea es continuar configurando el clon de Ghosts 'n Goblins usando Phaser 3. Ya hemos implementado el sistema de armas.

A continuación, necesitamos:
- Añadir cofres que aparezcan en el escenario.
- Implementar la lógica para que los cofres se abran cuando Arthur los golpea con su arma.
- Añadir power-ups que salgan de los cofres (armas nuevas, armadura, puntos extra).
- Implementar un sistema de puntuación.

Genera con python los sprites para los cofres y los diferentes power-ups.

Por favor, maneja todas las actualizaciones y configuraciones de archivos necesarias para lograr esto. Una vez completado, prueba el juego para asegurar que los cofres y los power-ups funcionan correctamente.
```

## 15. Implementación del Jefe Final

```
Eres un desarrollador de videojuegos experto. Tu tarea es continuar configurando el clon de Ghosts 'n Goblins usando Phaser 3. Ya hemos añadido cofres y power-ups.

A continuación, necesitamos:
- Añadir un jefe final al final del nivel (el demonio volador).
- Implementar patrones de movimiento y ataque para el jefe.
- Añadir una barra de vida para el jefe.
- Implementar la lógica de victoria cuando el jefe es derrotado.

Genera con python un sprite para el jefe final con múltiples frames para sus animaciones.

Por favor, maneja todas las actualizaciones y configuraciones de archivos necesarias para lograr esto. Una vez completado, prueba el juego para asegurar que el jefe final y la lógica de victoria funcionan correctamente.
```

## 16. Implementación de Pantallas y UI

```
Eres un desarrollador de videojuegos experto. Tu tarea es continuar configurando el clon de Ghosts 'n Goblins usando Phaser 3. Ya hemos implementado el jefe final y la lógica de victoria.

A continuación, necesitamos:
- Crear una pantalla de título con el logo del juego y opciones para comenzar.
- Implementar una pantalla de game over con opción para reintentar.
- Crear una pantalla de victoria al completar el nivel.
- Añadir una interfaz de usuario durante el juego que muestre puntuación, vidas y tiempo restante.

Por favor, maneja todas las actualizaciones y configuraciones de archivos necesarias para lograr esto. Una vez completado, prueba el juego para asegurar que todas las pantallas y menús funcionan correctamente.
```

## 17. Implementación de Audio

```
Eres un desarrollador de videojuegos experto. Tu tarea es continuar configurando el clon de Ghosts 'n Goblins usando Phaser 3. Ya hemos implementado todas las pantallas y menús.

A continuación, necesitamos:
- Añadir la música de fondo original del juego.
- Implementar efectos de sonido para:
  - Saltos y movimientos de Arthur
  - Lanzamiento de armas
  - Impacto de armas en enemigos
  - Muerte de enemigos
  - Daño recibido por Arthur
  - Muerte de Arthur
  - Recogida de power-ups
  - Apertura de cofres
  - Jefe final
- Añadir opciones para silenciar el sonido y la música.

No disponemos de archivos de audio para todos los efectos de sonido y la música, por lo que podríamos utilizar dos vías. O utilizar sonidos/melodías publicas a través de urls o descargar los archivos de audio al entorno local.

Por favor, maneja todas las actualizaciones y configuraciones de archivos necesarias para lograr esto. Una vez completado, prueba el juego para asegurar que todos los efectos de sonido y la música funcionan correctamente.
```
