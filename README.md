# Tic-Tac-Toe

Este proyecto consiste en un programa sencillo que simula una partida de Tres en Raya (Tic-Tac-Toe) entre el usuario y la computadora, siguiendo un conjunto de reglas simplificadas.

## Requisitos mínimos

- Python >= 3.0.0 

## Descripción del juego

La computadora juega con X

El usuario juega con O

La computadora siempre comienza la partida

El primer movimiento de la computadora es siempre en el centro del tablero

El tablero es de 3x3 y las casillas están numeradas del 1 al 9, de izquierda a derecha y de arriba hacia abajo

## Reglas del juego

El usuario elige su movimiento ingresando el número de la casilla.

El número ingresado debe cumplir las siguientes condiciones:

Ser un número entero

Estar entre 1 y 9

Corresponder a una casilla libre

Después de cada jugada:

El programa verifica si el juego ha terminado

Si no ha terminado, la computadora realiza su movimiento

La computadora no utiliza inteligencia artificial:

Sus movimientos se eligen aleatoriamente entre las casillas disponibles

## Posibles resultados

Después de cada turno, el programa evalúa el estado del juego. Existen cuatro posibles resultados:

El juego continúa

Empate

Gana el usuario

Gana la computadora

## Lógica de la computadora

Juega siempre con X

El primer movimiento es fijo (casilla central)

Los siguientes movimientos se eligen al azar entre las casillas disponibles