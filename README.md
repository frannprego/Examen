# Examen
Primer examen

# Examen 1ª Evaluación

---

Explica a continación cada apartado del examen

Con cada apartado realiza un commit diferente


## 1. Diagrama de Flujo

A continuación, se presenta el diagrama de flujo para recorrer el tablero:

https://app.diagrams.net/#G1rX7wvZg-dOlr5yTZhWuB24R1Qo6Xjw9Y#%7B%22pageId%22%3A%22zUcDdNzx59Hts0esW-dg%22%7D

![Diagrama de Flujo](1.jpg)

### Explicación del Diagrama de Flujo

1. **Inicio**: Comienza el recorrido del tablero.
2. **Recorrer Filas y Columnas**: El diagrama recorre todas las casillas de la cuadrícula 8x8.
3. **Comprobación de Casillas**: Si la casilla está ocupada, se muestra la coordenada y el tipo de ficha.
4. **Contabilización**: Se cuentan las fichas de cada jugador.
5. **Resultado**: Se muestra quién va ganando dependiendo del número de fichas.

## 2. Ejemplo del Tablero

El tablero de "Damas" tiene un tamaño de 8x8, con casillas alternadas. A continuación, un ejemplo de cómo se representa:


**Leyenda:**
- **R**: Ficha del jugador 1 (rojo)
- **B**: Ficha del jugador 2 (negro)
- **.**: Casilla vacía

A B C D E F G H

1 R . R . R . R .

2 . R . R . R . R

3 R . R . R . R .

4 . . . . . . . .

5 . . . . . . . .

6 . B . B . B . B
7 B . B . B . B .
8 . B . B . B . B


## 3. Funciones Propuestas

Para mejorar la legibilidad y mantener el código modular, propongo las siguientes funciones:

### 3.1 `verificarCasilla`

**Descripción**: Verifica si una casilla está ocupada y devuelve el tipo de ficha en caso afirmativo.


public String verificarCasilla(int fila, int columna, char[][] tablero) {
}

### 3.2 `contarCasilla`

**Descripción**: Cuenta cuántas fichas tiene cada jugador en el tablero

public int contarFichas(char[][] tablero, char ficha) {
}

### 3.3`quienGana`

**Descripción**:  Compara el número de fichas de ambos jugadores y determina quién va ganando.

public void quienGana(int fichasJugador1, int fichasJugador2) {}


## 4. JAVADOC

public String verificarCasilla(int fila, int columna, char[][] tablero) {
}

/**
* Verifica si una casilla está ocupada y devuelve el tipo de ficha.
* @param fila La fila de la casilla en el tablero.
* @param columna La columna de la casilla en el tablero.
* @param tablero El arreglo bidimensional que representa el tablero.
* @return Un mensaje indicando si la casilla está ocupada o vacía.
  */



public  String verificarCasilla(int fila, int columna, char[][] tablero) {
// Implementación
return "";
}

    /**
     * Cuenta cuántas fichas de un jugador están en el tablero.
     * @param tablero El arreglo bidimensional que representa el tablero.
     * @param ficha El tipo de ficha a contar (por ejemplo, 'R' para el jugador 1).
     * @return El número de fichas encontradas de ese tipo.
     */

public int contarFichas(char[][] tablero, char ficha) {
// Implementación
return 0;
}

    /**
     * Compara el número de fichas de ambos jugadores y muestra quién va ganando.
     * @param fichasJugador1 El número de fichas del jugador 1.
     * @param fichasJugador2 El número de fichas del jugador 2.
     */

public void quienGana(int fichasJugador1, int fichasJugador2) {
// Implementación
}diferente
