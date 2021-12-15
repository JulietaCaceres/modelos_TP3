# Modelos TP3

En esta entrega se pretende llegar a la combinación óptima de lados.
A continuación se detallan los pasos realizados.

## Primera corrida
En esta primera corrida se intenta ejecuta la heuristica con el codigo provisto, dado los tiempos altos de ejecución se decide detenerla antes de llegar al resultado final.

## Segunda corrida

Se cambia la solución por la obtenida en el TP2, el resultado obtenido no es optimo, 
a continuación los resultados:
Parece que no se llego al optimo, status: 107
* Optimo: 97.000000
* Cota: 70.000000
* Nodos: 3440
* Tiempo: 1802.953000

## Tercera corrida

En esta ocación se Cambia el Max Color por la cantidad de lavados obtenidos en el TP2,
el resultado tampoco es el óptimo. También se agrega la restricción solicitada

Parece que no se llego al optimo, status: 107
* Optimo: 97.000000
* Cota: 70.000000
* Nodos: 3329
* Tiempo: 1800.282000

La cantidad de nodos y el tiempo se reduce, aunque no singificativamente.

## Cuarta corrida

Se cambia la forma en que se hardcodea el resultado, esta vez leyendo de un archivo, el resultado es el optimo
* Optimo: 91.000000
* Cota: 91.000000
* Nodos: 15490
* Tiempo: 185.344000
