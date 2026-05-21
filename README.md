# Generador y Resolutor de Laberintos

Proyecto académico sobre grafos que implementa un generador y resolutor de laberintos utilizando los algoritmos BFS (Breadth First Search) y DFS (Depth First Search).

## Descripción

El proyecto representa un laberinto como un grafo, donde:

- Cada celda del tablero representa un nodo.
- Las conexiones entre celdas accesibles representan aristas.
- No hay pesos
- No es dirigido

El sistema permite:

- Generar laberintos aleatorios.
- Visualizar el laberinto en pantalla.
- Resolver el laberinto utilizando BFS.
- Resolver el laberinto utilizando DFS.
- Mostrar paso a paso el recorrido de los algoritmos.

---

## Integrantes

- Samuel Baron Lopez
- Cristian Javier Molina Gómez

---

## Tecnologías utilizadas

- HTML
- CSS
- JavaScript

---

## Algoritmos implementados

### BFS (Breadth First Search)

- Recorre el grafo por niveles.
- Garantiza encontrar el camino más corto.

### DFS (Depth First Search)

- Explora profundamente antes de retroceder.
- No garantiza el camino más corto.

---

## Estructura del proyecto

```plaintext
Proyecto-Laberintos/

│ README.md
│
├── src/
│      index.html
│
├── docs/
│      documento_tecnico.md
│
└── data/
```

---

## Cómo ejecutar el proyecto

1. Descargar o clonar el repositorio.
2. Abrir la carpeta `src`.
3. Ejecutar el archivo `index.html` en el navegador.

---

## Controles

- Generar Laberinto → crea un nuevo laberinto aleatorio.
- Resolver BFS → resuelve el laberinto utilizando BFS.
- Resolver DFS → resuelve el laberinto utilizando DFS.

---

## Representación visual

- Negro → paredes
- Blanco → caminos
- Verde → inicio
- Rojo → meta
- Azul → recorrido BFS
- Naranja → recorrido DFS
- Amarillo → camino encontrado

---

## Complejidad de los algoritmos

| Algoritmo | Complejidad |
|---|---|
| BFS | O(V + E) |
| DFS | O(V + E) |

Donde:

- V = número de nodos
- E = número de aristas

---

## Posibles mejoras

- Cargar laberintos desde archivos.
- Generación avanzada de laberintos.
- Permitir distintos tamaños de tablero.
- Comparar tiempos de ejecución.
- Agregar pesos y algoritmos como Dijkstra o A*.

---

## Licencia

Proyecto académico desarrollado con fines educativos.