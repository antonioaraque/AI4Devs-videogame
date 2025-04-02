# Ghosts 'n Goblins - Clon Web

![Ghosts 'n Goblins Banner](assets/images/banner.png)

## Descripción

Este proyecto es un clon del clásico juego arcade "Ghosts 'n Goblins" desarrollado con Phaser 3. El juego mantiene la esencia y dificultad del original, permitiendo a los jugadores revivir esta experiencia retro directamente desde el navegador web.

## Características

- **Jugabilidad fiel al original**: Conserva la dificultad y mecánicas que hicieron famoso al juego.
- **Controles responsivos**: Sistema de movimiento fluido para Arthur, nuestro valiente caballero.
- **Sistema de armas**: Incluye lanza, daga, antorcha y hacha, cada una con comportamientos únicos.
- **Enemigos clásicos**: Zombies que emergen de la tierra y otros enemigos icónicos del juego original.
- **Jefe final**: Enfréntate al demonio volador al finalizar el nivel.
- **Power-ups**: Descubre cofres con armas nuevas, armaduras y puntos extra.
- **Sistema de armadura**: Como en el original, Arthur pierde su armadura con el primer golpe y muere con el segundo.
- **Audio retro**: Efectos de sonido y música que evocan la sensación del juego arcade.
- **Interfaz completa**: Pantallas de título, de fin de juego y de victoria.

## Requisitos del Sistema

- Navegador web moderno con soporte para HTML5 y WebGL (Chrome, Firefox, Safari, Edge)
- Conexión a internet para la carga inicial del juego
- Teclado para los controles

## Instalación

1. Clona este repositorio:
   ```bash
   git clone https://github.com/usuario/ghosts-n-goblins.git
   ```

2. Navega al directorio del proyecto:
   ```bash
   cd ghosts-n-goblins
   ```

3. Si tienes Python instalado, puedes iniciar un servidor local:
   ```bash
   # Para Python 3
   python -m http.server
   
   # Para Python 2
   python -m SimpleHTTPServer
   ```

4. Abre tu navegador y ve a `http://localhost:8000`

## Controles

- **Flechas Izquierda/Derecha**: Mover a Arthur
- **Flecha Arriba**: Saltar (pulsa varias veces para saltos más altos)
- **Espacio o Z**: Lanzar arma
- **P**: Pausar el juego
- **M**: Silenciar/Activar sonido

## Estructura del Proyecto

```
ghosts-n-goblins/
│── index.html          # Página principal del juego
│── main.js             # Archivo principal de inicialización
│── scenes/             # Escenas del juego (título, juego, fin de juego)
│   │── TitleScene.js
│   │── GameScene.js
│   │── GameOverScene.js
│   │── VictoryScene.js
│── assets/             # Recursos del juego
│   │── images/         # Sprites e imágenes
│   │   │── Arthur/     # Sprites del personaje principal
│   │   │── enemies/    # Sprites de los enemigos
│   │   │── weapons/    # Sprites de las armas
│   │   │── items/      # Sprites de los power-ups y cofres
│   │   │── level/      # Elementos del escenario
│   │── audio/          # Efectos de sonido y música
│── styles/             # Hojas de estilo CSS
│── lib/                # Bibliotecas externas (Phaser)
```

## Desarrollo

Este proyecto ha sido desarrollado utilizando:

- **Phaser 3**: Framework de juegos HTML5
- **JavaScript ES6**: Para la lógica del juego
- **HTML5/CSS**: Para la estructura y estilos
- **Programación orientada a objetos**: Para una arquitectura limpia y extensible

## Capturas de Pantalla

![Pantalla de Título](assets/images/screenshots/title.png)
![Gameplay](assets/images/screenshots/gameplay.png)
![Jefe Final](assets/images/screenshots/boss.png)

## Contribuir

Si deseas contribuir al proyecto, sigue estos pasos:

1. Haz un fork del repositorio
2. Crea una rama para tu función: `git checkout -b feature/nueva-funcion`
3. Realiza tus cambios y haz commit: `git commit -m 'Añadir nueva función'`
4. Sube tus cambios: `git push origin feature/nueva-funcion`
5. Envía un pull request

## Roadmap

Futuras mejoras planeadas:

- [ ] Niveles adicionales
- [ ] Más enemigos y jefes
- [ ] Modo cooperativo para dos jugadores
- [ ] Soporte para dispositivos móviles
- [ ] Tabla de clasificaciones online
- [ ] Editor de niveles

## Créditos

- Este proyecto es un homenaje al juego original "Ghosts 'n Goblins" desarrollado por Capcom.
- Todos los derechos sobre el juego original pertenecen a Capcom.
- Este clon ha sido creado con fines educativos y de aprendizaje.

## Licencia

Este proyecto está licenciado bajo [MIT License](LICENSE).

## Agradecimientos

- A todos los desarrolladores de Phaser por proporcionar un excelente framework
- A la comunidad de desarrollo de juegos retro por mantener viva la memoria de estos clásicos
- A Tokuro Fujiwara, diseñador del juego original

---

¿Encontraste un bug o tienes una sugerencia? Abre un issue o contáctanos en ghostsnclone@ejemplo.com
