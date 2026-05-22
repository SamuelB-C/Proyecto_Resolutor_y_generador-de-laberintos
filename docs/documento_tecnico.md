# Documento Técnico
## Generador y Resolutor de Laberintos

---

# 1. Descripción del problema y motivación

El proyecto consiste en desarrollar un sistema capaz de generar y resolver laberintos utilizando grafos y algoritmos de búsqueda.

Cada celda del laberinto representa un nodo del grafo y las conexiones entre celdas representan aristas.

La motivación del proyecto es aplicar conceptos fundamentales de teoría de grafos y comparar el comportamiento de los algoritmos BFS y DFS.

---

# 2. Modelado del problema con grafos

## Nodos

Cada celda accesible del laberinto representa un nodo.

## Aristas

Las conexiones entre celdas vecinas representan aristas.

## Dirección

El grafo es no dirigido, ya que el movimiento puede realizarse en ambas direcciones.

## Pesos

Las aristas no poseen pesos.

---

# 3. Estructuras de datos utilizadas

## Matriz bidimensional

Se utiliza una matriz para representar el laberinto.

```js
maze[y][x]
```

Donde:

- 0 representa una pared.
- 1 representa un camino accesible.

## Cola

Utilizada en BFS para recorrer el grafo por niveles.

## Pila

Utilizada en DFS para explorar profundamente el grafo.

## Arreglo de visitados

Permite evitar visitar nodos repetidos.

---

# 4. Operaciones implementadas

## Generación aleatoria de laberintos

El sistema genera laberintos aleatorios utilizando valores binarios.

Complejidad aproximada:

O(n*m)

---

## Resolución mediante BFS

El algoritmo BFS explora el grafo por niveles y garantiza encontrar el camino más corto.

Complejidad:

O(V + E)

---

## Resolución mediante DFS

El algoritmo DFS explora profundamente antes de retroceder.

Complejidad:

O(V + E)

---

# 5. Casos de prueba

| Caso | Resultado esperado |
|---|---|
| Laberinto con camino | El algoritmo encuentra la salida |
| Laberinto bloqueado | El sistema indica que no existe camino |
| Laberinto pequeño | BFS y DFS resuelven correctamente |

---

# 6. Instrucciones de ejecución

1. Descargar el proyecto.
2. Abrir la carpeta src.
3. Ejecutar el archivo index.html en un navegador web.

---

# 7. Limitaciones y mejoras futuras

## Limitaciones

- El generador es aleatorio.
- Algunos laberintos pueden no tener solución.
- No se manejan pesos en las aristas.

## Mejoras futuras

- Cargar laberintos desde archivos.
- Implementar Dijkstra y A*.
- Permitir tamaños dinámicos de tablero.
- Agregar comparación de tiempos de ejecución.

---

# 8. Conclusión

El proyecto permitió aplicar conceptos de grafos, búsqueda y estructuras de datos mediante una representación visual e interactiva de laberintos utilizando BFS y DFS.