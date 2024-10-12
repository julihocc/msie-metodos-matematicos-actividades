# 3A Actividad: Sistemas dinámicos aleatorios

- Maestría en Sistemas Inteligentes Embebidos
- Materia: Métodos Matemáticos
- Unidad: Probabilidad y estadística
- Docente: Dr. Juliho Castillo Colmenares
- Puntaje total: 15

## Objetivo

Analizar sistemas dinámicos aleatorios de forma cualitativa y cuantitativa

## Instrucciones 

1. **Consulta** [Taha], capítulo 17
2. **Recopila** y **analiza** tu información
3. **Descarga** el archivo[ 3A Actividad](https://github.com/julihocc/msie-metodos-matematicos-actividades/tree/main/u3-actividad) y  **redacta** tus respuestas en formato Markdown
4. **Documenta** cada paso de tu proceso de resolución, incluyendo las ecuaciones utilizadas, los cálculos realizados y las soluciones obtenidas
5. **Utiliza** Python o SageMath para realizar los cálculos necesarios. 
6. **Redacta** tu trabajo en una libreta Jupyter.
7. **Exporta y entrega** tu trabajo en formato PDF.
8. **Considera** los [criterios de evaluación](https://github.com/julihocc/msie-metodos-matematicos-actividades/tree/main/u3-actividad)

## Problema 1

Considera una cadena de Markov representada por la siguiente matriz:
```math 
P = 
\begin{bmatrix}
0.88 & 0.12 \\
0.15 & 0.85
\end{bmatrix}
```
que actua por la derecha.

1. Traza la gráfica a la cadena de Markov
2. Explica porque la matriz es estocástica
3. Explica porque la matriz es regular
4. Explica porque la matriz es ergódica
5. Calcula $\lim_{n\to \infty} P^n$

## Problema 2
 
Hay tres categorías de contribuyentes de impuestos sobre la renta en los Estados Unidos: los que nunca evaden impuestos, los que a veces lo hacen y los que siempre lo hacen.

Un examen de las declaraciones de impuestos auditadas de un año al siguiente muestra que de aquellos que no evadieron impuestos el año pasado, el 95% continúa en la misma categoría este año, el 4% pasa a la categoría "a veces" y el resto se mueve a la categoría "siempre".

Para aquellos que a veces evaden impuestos, el 6% pasa a "nunca", el 90% permanece igual y el 4% pasa a "siempre". En cuanto a los evasores “siempre”, los porcentajes respectivos son 0%, 10% y 90%.

1. Expresa el problema en términos de una cadena de Markov, justificando detalladamente la elección de tu modelo. 
2. Calcula la distribución estacionaria utilizando eigenvectores. 
3. Calcula la distribución estacionaria, de forma numérica, iterando la matriz de transición.
4. Verifica que ambos resultados coincidan y explica este resultado en términos de nuestro problema de impuestos.
5. Las estadísticas muestran que un contribuyente en la categoría "a veces" evade impuestos aproximadamente $\$5000$ por declaración y en la categoría "siempre" sobre alrededor de $\$12,000.$ Suponiendo que la población de contribuyentes es de 70 millones y que la tasa de impuesto sobre la renta promedio es del 12%, determinar la reducción anual de los impuestos recaudados por evasión.

## Bibliografía

- Hoel, P. G., Port, S. C., Stone, C. J. (1971). Introduction to Probability Theory. Taiwan: Houghton Mifflin.
- Hoel, P. G. (1954). Introduction to mathematical statistics. United Kingdom: Wiley.
- Hoel, P. G., Port, S. C., & Stone, C. J. (1986). Introduction to Stochastic Processes. Waveland Press.
- Taha, H. A. (2018). Operations Research: An Introduction, Global Edition. United Kingdom: Pearson Education.