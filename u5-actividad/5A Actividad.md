# 5A Actividad: Dinámica en gráficas

- Maestría en Sistemas Inteligentes Embebidos
- Materia: Métodos Matemáticos
- Unidad: Teoría de Grafos
- Docente: Dr. Juliho Castillo Colmenares
- Puntaje total: 15

## Objetivo

Aplicar y analizar diferentes conceptos de la teoría de grafos para resolver problemas relacionados con el análisis y optimización de redes, la optimización de rutas en sistemas de transporte y la planificación de redes de comunicación.

## Instrucciones

1. **Consulta** [Sagemath, Graph Theory](https://doc.sagemath.org/pdf/en/reference/graphs/graphs.pdf)
2. **Recopila** y **analiza** tu información
3. **Descarga** el archivo[ 5A Actividad](https://github.com/julihocc/msie-metodos-matematicos-actividades/tree/main/u5-actividad) y **redacta** tus respuestas en formato Markdown
4. **Documenta** cada paso de tu proceso de resolución, incluyendo las ecuaciones utilizadas, los cálculos realizados y las soluciones obtenidas
5. **Utiliza** Python o SageMath para realizar los cálculos necesarios.
6. **Redacta** tu trabajo en una libreta Jupyter.
7. **Exporta y entrega** tu trabajo en formato PDF.
8. **Considera** los [criterios de evaluación](https://github.com/julihocc/msie-metodos-matematicos-actividades/tree/main/u5-actividad)

## Bibliografía

1. Diestel, R. (2017). Graph Theory. Springer.
2. Farrelly, C. M., Mutombo, F. K. (n.d.). Modern Graph Theory Algorithms with Python: Harness the Power of Graph Algorithms and Real-world Network Applications Using Python. United Kingdom: Packt Publishing.
3. Golumbic, M. C. (2004). Algorithmic Graph Theory and Perfect Graphs. Elsevier.
4. Gross, J. L., & Yellen, J. (2018). Graph Theory and Its Applications. CRC Press.
5. Valiente, G. (2021). Algorithms on Trees and Graphs: With Python Code. Switzerland: Springer International Publishing.

### Actividad: Explorando Teoría de Gráficas en SageMath

### Descripción del grafo a utilizar en los ejercicios
Para los siguientes ejercicios, trabajaremos con un grafo no dirigido que tiene 5 nodos y 7 aristas, representado por la siguiente **lista de adyacencia**:

- Nodo 0: conectado con los nodos 1, 2 y 4.
- Nodo 1: conectado con los nodos 0, 2 y 3.
- Nodo 2: conectado con los nodos 0 y 1.
- Nodo 3: conectado con los nodos 1 y 4.
- Nodo 4: conectado con los nodos 0 y 3.

Esta lista de adyacencia define las conexiones (aristas) entre los nodos del grafo.

### Ejercicios

---

### Ejercicio 1: Creación de un grafo y visualización
Crea el grafo definido por la lista de adyacencia anterior. Visualiza el grafo y asegúrate de que se representen correctamente las aristas y nodos.

**Indicaciones:**
1. Usa la lista de adyacencia proporcionada para definir los nodos y las conexiones entre ellos.
2. Visualiza el grafo utilizando Sage.

---

### Ejercicio 2: Cálculo de grados de los nodos
Calcula el grado de cada nodo en el grafo creado en el **Ejercicio 1**.

**Indicaciones:**
1. Usa Sage para obtener el grado de cada nodo.
2. Verifica que la suma de todos los grados sea el doble del número de aristas, de acuerdo con las propiedades básicas de los grafos.

---

### Ejercicio 3: Caminos y conectividad
Verifica si el grafo es conexo y encuentra el camino más corto entre dos nodos dados (por ejemplo, entre el nodo 0 y el nodo 3).

**Indicaciones:**
1. Determina si el grafo es conexo.
2. Usa la función de caminos más cortos para encontrar la ruta entre los nodos.

---

### Ejercicio 4: Ciclos en el grafo
Determina si el grafo contiene algún ciclo y, de ser así, encuentra un ciclo en el grafo.

**Indicaciones:**
1. Usa las funciones de detección de ciclos en Sage.
2. Si existe un ciclo, imprímelo.

---

### Ejercicio 5: Grafos bipartitos y coloración
Comprueba si el grafo es bipartito y encuentra una coloración de los nodos con el mínimo número de colores.

**Indicaciones:**
1. Usa la función para verificar si el grafo es bipartito.
2. Si no es bipartito, intenta encontrar una coloración mínima de los nodos.

---

Esta actividad te permitirá explorar conceptos clave de teoría de gráficas y practicar tus habilidades en SageMath utilizando listas de adyacencia.