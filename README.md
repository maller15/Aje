# Proyecto de Visualización de Partidas de Ajedrez en Java

Este proyecto implementa una aplicación en Java para visualizar partidas de ajedrez a partir de archivos en formato PGN (Portable Game Notation). La aplicación utiliza principios de Programación Orientada a Objetos (POO) y una interfaz gráfica desarrollada con Java Swing para mostrar el tablero y los movimientos de la partida.

## Características

- **Lectura de archivo PGN**: Lee un archivo de texto con los movimientos de una partida en formato PGN.
- **Interpretación de movimientos**: Interpreta y aplica los movimientos al estado del tablero de ajedrez.
- **Interfaz gráfica**: Muestra el tablero de ajedrez y las piezas en sus posiciones actuales.
- **Control de movimientos**: Permite avanzar y retroceder en la secuencia de movimientos para observar la evolución de la partida.
- **Cargar archivo PGN**: Posibilidad de cargar archivos PGN directamente desde la interfaz gráfica.

## Requisitos

- Java Development Kit (JDK) 8 o superior.
- IDE recomendado: NetBeans, Eclipse, IntelliJ IDEA o cualquier otro que soporte Java.
- Biblioteca de Java Swing (incluida en el JDK).

## Estructura del Proyecto

```plaintext
AjedrezPGN
├── src
│   └── AjedrezPGN
│       ├── InterfazAjedrez.java   # Clase principal con la interfaz gráfica
│       ├── JuegoDeAjedrez.java    # Lógica de control del juego
│       ├── PGNReader.java         # Clase para leer y procesar el archivo PGN
│       ├── Peon.java              # Clase para la pieza Peón
│       ├── Pieza.java             # Clase abstracta para piezas de ajedrez
│       ├── Posicion.java          # Clase para representar posiciones en el tablero
│       └── Tablero.java           # Clase para el tablero de ajedrez
└── partida.pgn                    # Archivo PGN con los movimientos de la partida
