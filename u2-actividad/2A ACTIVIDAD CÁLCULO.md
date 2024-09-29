# 2A Actividad: Análisis de sistemas dinámicos

- Maestría en Sistemas Inteligentes Embebidos
- Materia: Métodos Matemáticos
- Unidad: Cálculo
- Docente: Dr. Juliho Castillo Colmenares
- Puntaje: 15

## Objetivo

Analizar sistemas dinámicos lineales de forma cualitativa y cuantitativa

## Instrucciones

1. **Consulta** en la sección de aprende el recurso [Kelley, 2013], capítulos 3, secciones 1 a 4. 
2. **Recopila** y **analiza** tu información
3. **Descarga** el archivo[ 2A Actividad](https://github.com/julihocc/msie-metodos-matematicos-actividades/tree/main/u2-actividad) y  **redacta** tus respuestas en formato Markdown
4. **Documenta** cada paso de tu proceso de resolución, incluyendo las ecuaciones utilizadas, los cálculos realizados y las soluciones obtenidas
5. **Utiliza** Python o SageMath para realizar los cálculos necesarios. 
6. **Redacta** tu trabajo en una libreta Jupyter.
7. **Exporta y entrega** tu trabajo en formato PDF.
8. **Considera** los [criterios de evaluación](https://github.com/julihocc/msie-metodos-matematicos-actividades/tree/main/u2-actividad)

## Problemas

### Problema 1.

- Para cada sistema, determina si es hamiltoniano.
- Si es hamiltoniano, construye la función hamiltoniana paso a paso y verifica que sea tu construcción sea correcta. 
- En otro caso, explica porque el sistema no podría ser hamiltoniano. 

#### Inciso 1.1 (1.5 puntos)

$$
\begin{cases}
x'= e^{y}-2x \\
y'= 2y-2x
\end{cases}
$$

#### Inciso 1.2 (1.5 puntos)

$$
\begin{cases}
x'=x+y\\
y'=-x+y
\end{cases}
$$



### Problema 2

- Dibuja los diagramas del plano fase para cada uno de los siguientes sistemas. 
- Determina los puntos críticos y clasifícalos.

#### Inciso 2.1 (2.5 puntos)

```math
\begin{bmatrix}
x' \\
y'
\end{bmatrix}
= 
\begin{bmatrix}
0 & 4 \\
-4 & 0 
\end{bmatrix}
\begin{bmatrix}
x \\
y
\end{bmatrix}
```

#### Inciso 2.2 (2.5 puntos)

```math
\begin{bmatrix}
x' \\
y'
\end{bmatrix}
= 
\begin{bmatrix}
0 & 4 \\
-1 & 0 
\end{bmatrix}
\begin{bmatrix}
x \\
y
\end{bmatrix}
```

#### Inciso 2.3 (2.5 puntos)

```math
\begin{bmatrix}
x' \\
y'
\end{bmatrix}
= 
\begin{bmatrix}
-8 & 10 \\
-4 & 4 
\end{bmatrix}
\begin{bmatrix}
x \\
y
\end{bmatrix}
```

#### Inciso 2.4 (2.5 puntos)

```math
\begin{bmatrix}
x' \\
y'
\end{bmatrix}
= 
\begin{bmatrix}
-1 & -5 \\
2 & 5 
\end{bmatrix}
\begin{bmatrix}
x \\
y
\end{bmatrix}
```

### Problema 3 (2 puntos)

Encuentra las constantes $\alpha$ y $\beta$ de manera que 
```math
V(x,y) := \alpha x^2 + \beta y^2 
```
defina una función de Liapunov para el sistema
```math
x' = -x-5y \\
y' = 3x-y^3
```

## Problemas adicionales

### Problema 4 

#### Inciso 4.1 (2 puntos extras)

Encuentra una función de Liapunov para el sistema 
```math
x'=-x-y^2\\
y'=-\dfrac{1}{2}y+2xy
```

#### Inciso 4.2 (1 punto extra)

Identifica una familia de conjuntos positivamente invariantes

## Bibliografía

1. Fuhrer,     C., Solem, J. E., Verdier, O. (2021). Scientific Computing with Python -     Second Edition: High-Performance Scientific Computing with NumPy, SciPy,     and Pandas. India: Packt Publishing.
2. Hirsch, M.     W., Smale, S., Devaney, R. L. (2004). Differential Equations, Dynamical     Systems, and an Introduction to Chaos. Germany:     Elsevier Science.
3. Johansson,     R. (2018). Numerical Python: Scientific Computing and Data Science     Applications with Numpy, SciPy and Matplotlib. Germany: Apress.
4. Kelley, W. G., Peterson, A. C. (2010). The Theory of Differential Equations: Classical and Qualitative. United States: Springer New York.
5. Stewart, J. (2016). Calculus: Early Transcendentals. United States: Cengage Learning.
