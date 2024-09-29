

# 4A Problemario: Solución Numérica de Sistemas de Ecuaciones Diferenciales Ordinarias

- Maestría en Sistemas Inteligentes Embebidos
- Materia: Métodos matemáticos
- Unidad: Métodos numéricos
- Docente: Dr. Juliho Castillo Colmenares
- Puntaje total: 15

## Objetivo

Aplicar y analizar diferentes métodos numéricos para resolver sistemas de ecuaciones diferenciales ordinarias.

## Instrucciones

1. **Consulta** [Tveito et al., 2010], capítulos 2 y 3.
2. **Recopila** y **analiza** tu información.
3. **Descarga** el archivo [4A Métodos numéricos](https://github.com/julihocc/msie-metodos-matematicos-actividades/tree/main/u4-actividad) 
4. **Documenta** cada paso de tu proceso de resolución, incluyendo las ecuaciones utilizadas, los cálculos realizados y las soluciones obtenidas
5. **Utiliza** Python o SageMath para realizar los cálculos necesarios. 
6. **Redacta** tu trabajo en una libreta Jupyter.
7. **Exporta y entrega** tu trabajo en formato PDF.
8. **Considera** los [criterios de evaluación](https://github.com/julihocc/msie-metodos-matematicos-actividades/tree/main/u4-actividad)

## Problemas

### Problema 1 (8 puntos)

Considera el problema de valor inicial 

$$
r'(t) = 1 + 4r(t), r(0)=0, t \in [0,T]
$$.

1. Encuentra la solución exacta del problema. 
2. Encuentra un esquema explícita para la solución utilizando el método de Euler hacia adelante. La $i-$ésima iteración de este esquema se denotarán por $y_i$ donde $y_0=r(0)=0$.
3. Calcula $y_{100}$ utilizando $\Delta t =0.01$. 
4. Calcula el error absoluto relativo de $y_{100}$​ respecto a la solución exacta.
5. Encuentra un esquema implícito para la solución utilizando el método de Euler hacia atras. La $i-$ésima iteración de este esquema se denotarán por  $z_i$ donde $z_0=r(0)=0$.
6. Calcula $z_{100}$ utilizando $\Delta t =0.01$. 
7. Calcula el error absoluto relativo de $z_{100}$ respecto a la solución exacta.
8. ¿Cuál de los dos métodos es mejor?

### Problema 2

Considera el sistema
$$
F' & = (2-S)F, & F(0) & = F_0\\
S'& = (F-1)S, & S(0) & = S_0
$$

### Inciso 1. (2 puntos)
Determina un esquema numérico explícito para aproximar la solución.

### Inciso 2. (2 puntos)
Encuentra una aproximación numérica a la solución en $t=1$ si $F_0 = 1.9 $,$ S_0=0.1$ , $\Delta t = 0.001.$

### Inciso 3 (2 puntos)

Encuentra una aproximación numérica a la solución en $t=1$ si $F_0 = 1$,$ S_0=2$ , $\Delta t = 0.001.$

### Inciso 4 (1 puntos)

A partir del sistema de ecuaciones y el correspondiente esquema numérico, explica los resultados del inciso anterior.

## Bibliografía

1. Fuhrer, C., Solem, J. E., Verdier, O. (2021). Scientific Computing with Python - Second Edition: High-Performance Scientific Computing with NumPy, SciPy, and Pandas. India: Packt Publishing.
2. Johansson, R. (2018). Numerical Python: Scientific Computing and Data Science Applications with Numpy, SciPy and Matplotlib. Germany: Apress.
3. Linge, S., Langtangen, H. P. (2016). Programming for Computations - Python: A Gentle Introduction to Numerical Simulations with Python. Germany: Springer International Publishing.
4. Tveito, A., Langtangen, H. P., Nielsen, B. F., Cai, X. (2010). Elements of Scientific Computing. Germany: Springer.