# 5A Actividad: Dinámica en gráficas

- Maestría en Sistemas Inteligentes Embebidos
- Materia: Métodos Matemáticos
- Unidad: Teoría de Grafos
- Docente: Dr. Juliho Castillo Colmenares
- Puntaje total: 15

## Objetivo

Aplicar y analizar diferentes conceptos de la teoría de grafos para resolver problemas relacionados con el análisis y optimización de redes, la optimización de rutas en sistemas de transporte y la planificación de redes de comunicación.

## Instrucciones

1. **Consulta** en la sección de aprende el material  Modern Graph Theory Algorithms with Python: Harness the Power of Graph Algorithms and Real-world Network Applications Using Python, Cap. 1 y 2
2. **Recopila** y **analiza** tu información
3. **Descarga** el archivo[ 5A Actividad](https://github.com/julihocc/msie-metodos-matematicos-actividades/tree/main/u5-actividad) y  **redacta** tus respuestas en formato Markdown
4. **Documenta** cada paso de tu proceso de resolución, incluyendo las ecuaciones utilizadas, los cálculos realizados y las soluciones obtenidas
5. **Utiliza** Python o SageMath para realizar los cálculos necesarios. 
6. **Redacta** tu trabajo en una libreta Jupyter.
7. **Exporta y entrega** tu trabajo en formato PDF.
8. **Considera** los [criterios de evaluación](https://github.com/julihocc/msie-metodos-matematicos-actividades/tree/main/u5-actividad)

## Problemas

#### Problema 1. 

- Para cada grafo proporcionado, aplica un algoritmo de la teoría de grafos para encontrar una ruta óptima.
- Dibuja las rutas obtenidas.

##### Inciso 1.1 (3 puntos)

Dado el siguiente grafo que representa una red de transporte, encuentra la ruta más corta entre el nodo A y el nodo F.

Lista de adyacencia:

```
A: [(B, 1), (D, 3)]
B: [(A, 1), (C, 2), (D, 2), (E, 1)]
C: [(B, 2), (E, 3), (F, 3)]
D: [(A, 3), (B, 2), (E, 2)]
E: [(B, 1), (C, 3), (D, 2), (F, 2)]
F: [(C, 3), (E, 2)]
```

##### Inciso 1.2 (3 puntos)

Dado el siguiente grafo que representa una red de comunicación, encuentra la ruta con mayor ancho de banda (representado por los pesos de las aristas) entre el nodo A y el nodo F.

Lista de adyacencia:

```
A: [(B, 10), (D, 30)]
B: [(A, 10), (C, 20), (D, 40), (E, 50)]
C: [(B, 20), (E, 60), (F, 60)]
D: [(A, 30), (B, 40), (E, 50)]
E: [(B, 50), (C, 60), (D, 50), (F, 40)]
F: [(C, 60), (E, 40)]
```

#### Problema 2. (4.5 puntos)

- Aplica un algoritmo de la teoría de grafos para resolver el siguiente problema de optimización de rutas en un sistema de transporte.
- Dibuja la solución obtenida.

Dado el siguiente grafo que representa un sistema de transporte, encuentra la ruta más corta que visita todos los nodos exactamente una vez.

Lista de adyacencia:

```
A: [(B, 1), (D, 3)]
B: [(A, 1), (C, 2), (D, 2), (E, 1)]
C: [(B, 2), (E, 3), (F, 3)]
D: [(A, 3), (B, 2), (E, 2)]
E: [(B, 1), (C, 3), (D, 2), (F, 2)]
F: [(C, 3), (E, 2)]
```

#### Problema 3. (4.5 puntos)

Encuentra una solución al siguiente problema de planificación de redes de comunicación utilizando la teoría de grafos. Dibuja la solución obtenida.

Dado el siguiente grafo que representa una red de comunicación, encuentra el árbol de expansión mínima.

Lista de adyacencia:

```
A: [(B, 10), (D, 30)]
B: [(A, 10), (C, 20), (D, 40), (E, 50)]
C: [(B, 20), (E, 60), (F, 60)]
D: [(A, 30), (B, 40), (E, 50)]
E: [(B, 50), (C, 60), (D, 50), (F, 40)]
F: [(C, 60), (E, 40)]
```

## Bibliografía

1. Diestel, R. (2017). Graph Theory. Springer.
2. Farrelly, C. M., Mutombo, F. K. (n.d.). Modern Graph Theory Algorithms with Python: Harness the Power of Graph Algorithms and Real-world Network Applications Using Python. United Kingdom: Packt Publishing.
3. Golumbic, M. C. (2004). Algorithmic Graph Theory and Perfect Graphs. Elsevier.
4. Gross, J. L., & Yellen, J. (2018). Graph Theory and Its Applications. CRC Press.
5. Valiente, G. (2021). Algorithms on Trees and Graphs: With Python Code. Switzerland: Springer International Publishing.

​              