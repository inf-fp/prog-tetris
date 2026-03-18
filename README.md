# Proyecto Tetris

(DOCUMENTACIÓN EN DESARROLLO)

# 1. Introducción

- desarrollar videojuego para PC multiplaforma (Windows, MacOS y Linux)
- finalidad: 
  - entretenimiento (desde punto de vista usuario)
  - aprendizaje (desde punto de vista alumno)
- público objetivo: 
  - hombres e mulleres de 30+


# 2. Gestión del proyecto

## Objetivos
- crear un videojuego Tetris sin errores
- adquirir los conocimientos de Java para desarrollar un juego de estas características


## Alcance
- Funcionalidades **includas**:
  - Interfaz gráfica (una **única ventana** de juego).
  - Único **modo de juego**: clásico.
    - Sistema de niveles: 
      - Aumento de nivel por alcanzar un valor determinado de puntos (cada X puntos se sube 1 nivel).
      - Velocidad incemental. El aumento de nivel implica aumento de la velocidad de caída de las piezas, aumentando la dificultad del juego.
    - El juego termina cuando una pieza toca la parte superior del tablero.
  - **Piezas**
    - Un total de 7 piezas (https://upload.wikimedia.org/wikipedia/commons/6/6b/Piezas_Tetris_99.png)
    - Cada pieza tiene una forma diferente
    - Cada pieza tiene un color diferente
  - **Controles** por teclado de piezas
    - Rotación de pieza
    - Desplazamiento de pieza horizontalmente (derecha-izquierda)
    - Aceleración vertical
    - Salto vertical (caída de pieza)
  - Panel de información
    - Mostrar controles
    - Contador de líneas eliminadas/completadas
    - Puntuación
    - Nivel
    - Rachas
    - Bonus actual
  - Sistema de **puntuación**:
    - Contabilizar líneas completadas
      - Empieza en 0
      - Va incrementando por línea completada + bonificación (en caso de haberla).
    - Multiplicador de puntos en base a:
      - ¿Cuántas líneas elimino a la vez?
      - ¿Cuántas veces seguidas elimino líneas?
        - (PENDIENTE)
- Funcionalidades **no incluidas**:
  - Pausar juego
  - Histórico de puntuaciones
  - Modos de juego:
    - Mapa abierto lateral: hai un hueco en los laterales izquierdo-derecho y, si se introduce una ficha por uno, sale por el opuesto otra ficha diferente.
    - Cronómetro: empieza un temporizador con cuenta regresiva. Solo aumenta si se obtienen bonificaciones.
    - Difícil: velocidad incrementada y con una fila roja en el medio que producirá una caída instanténea de la ficha.
  - Ninguna característica relacionada con multijugador
  - Menú principal: logo, ajustes, jugar, nombre usuario, salir
  - Ajustes: pantalla completa, modo oscuro, idioma

## Requisitos funcionales

## Planificación temporal
14 días (5 semanas)

## Asignación de recursos





# 3. Desarrollo del proyecto
## Diseño
## Arquitectura

# 4. Propuestas de mejora



### NOTAS
- cronómetro
  - bonus por racha
- ancho y alto tablero
- sistema de puntuación
- velocidad
- bonus
- números de piezas y formas
- mapas diferentes??
- gestión de jugadores
  - pedir nombre
  - guardar estadísticas y puntuación
  - pueden jugar jugadores diferentes?