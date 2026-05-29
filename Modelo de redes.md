# Modelo de redes

- Sirve para modelar amplia gama de problemas.
- Problemas de redes: el problema del arbol de expansión mínima, el problema del camino más corto, el problema del flujo máximo, el problema de la asignación, etc.

## Problema del árbol de expansión mínima
La tecnica del arbol de expansion minima implica conetar todos los puntos de una red con el menor costo posible. El costo de conectar dos puntos se representa por el peso de la arista que los une. El objetivo es encontrar un subconjunto de aristas que conecte todos los puntos con el menor costo total.

### Pasos para resolver el problema del árbol de expansión mínima:
1. Seleccionar cualquier nodo en la red.
2. Conectar este nodo con el nodo más cercano que no esté conectado.
3. Repetir el paso 2 hasta que todos los nodos estén conectados.
4. El resultado es un árbol que conecta todos los nodos con el menor costo total.

## Problema de flujo máximo
El problema de flujo máximo se refiere a encontrar la cantidad máxima de flujo que puede pasar a través de una red desde una fuente hasta un sumidero, respetando las capacidades de las aristas.

- Tenemos siempre un punto de origen (fuente) y un punto de destino (sumidero).
- Cada arista tiene dos valores asociados a la cantidad de flujo que puede pasar de izquierda a derecha y de derecha a izquierda.

### Pasos para resolver el problema de flujo máximo:
1. Comenzamos eligiendo arbitrariamente un camino desde la fuente hasta el sumidero.
2. Se escoje cual es el flujo máximo que se puede enviar por ese camino(el valor mas pequeño que no sea cero), que es el mínimo de las capacidades de las aristas en ese camino.
3. Se actualizan las capacidades de las aristas en el camino, restando el flujo maximo que se ha enviado.

+(->)-  
-(<-)+

## Problema de la ruta más corta
El problema de la ruta más corta se refiere a encontrar el camino más corto entre dos nodos.

### Pasos para resolver el problema de la ruta más corta:
1. Encontrar el nodo mas cercano al nodo de origen.
2. Actualizar las distancias a los nodos vecinos del nodo seleccionado.
3. Repetir los pasos 1 y 2 hasta que se alcance el nodo de destino o se hayan visitado todos los nodos.
4. El resultado es el camino más corto desde el nodo de origen hasta el nodo de destino.

