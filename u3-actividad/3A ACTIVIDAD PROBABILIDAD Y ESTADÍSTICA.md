# 3A Actividad: Sistemas dinámicos aleatorios

- Maestría en Sistemas Inteligentes Embebidos
- Materia: Métodos Matemáticos
- Unidad: Probabilidad y estadística
- Docente: Dr. Juliho Castillo Colmenares
- Puntaje total: 15

## Objetivo

Analizar sistemas dinámicos aleatorios de forma cualitativa y cuantitativa

## Instrucciones 

1. **Consulta** [Taha], capítulos 14 y 17
2. **Recopila** y **analiza** tu información
3. **Descarga** el archivo[ 3A Actividad](https://github.com/julihocc/msie-metodos-matematicos-actividades/tree/main/u3-actividad) y  **redacta** tus respuestas en formato Markdown
4. **Documenta** cada paso de tu proceso de resolución, incluyendo las ecuaciones utilizadas, los cálculos realizados y las soluciones obtenidas
5. **Utiliza** Python o SageMath para realizar los cálculos necesarios. 
6. **Redacta** tu trabajo en una libreta Jupyter.
7. **Exporta y entrega** tu trabajo en formato PDF.
8. **Considera** los [criterios de evaluación](https://github.com/julihocc/msie-metodos-matematicos-actividades/tree/main/u3-actividad)

## Problemas

### Problema 1 (5 puntos)

María von Savant es conocida por haber resuelto un problema de probabilidad en la columna "Ask Marilyn" de la revista Parade en 1990. El problema se llamaba "El problema de Monty Hall", y se basaba en un juego de televisión llamado "Let's Make a Deal" en el que un concursante debe elegir una de tres puertas, detrás de una de las cuales hay un premio, mientras que las otras dos puertas esconden algo sin valor. Después de que el concursante elija una puerta, el presentador, Monty Hall, que sabe qué hay detrás de cada puerta, abrirá una de las dos puertas restantes que no ha sido elegida por el concursante, revelando que no hay un premio detrás de ella. Luego, Monty le ofrece al concursante la oportunidad de cambiar su elección original por la otra puerta restante.

El problema se preguntaba si era mejor para el concursante cambiar su elección original después de que Monty abriera una puerta sin premio. Muchas personas intuitivamente creen que no importa si cambian o no, y que tienen una probabilidad del 50% de ganar el premio independientemente de lo que hagan. Sin embargo, Maria von Savant argumentó que cambiar de puerta duplica las posibilidades de ganar, y que la probabilidad de ganar si se cambia de puerta es del 2/3, mientras que si se mantiene la elección original, la probabilidad de ganar es del 1/3.

La respuesta de von Savant causó controversia en ese momento, y algunos matemáticos y estadísticos se opusieron a ella, argumentando que estaba equivocada. Sin embargo, con el tiempo se ha demostrado que su respuesta es correcta y que el cambio de puerta en realidad aumenta las posibilidades de ganar el premio.

La respuesta de von Savant al problema de Monty Hall puede ser demostrada mediante el uso de la teoría de probabilidad y la ley de Bayes. A continuación se presenta una explicación de cómo se puede llegar a la conclusión de que cambiar de puerta aumenta las posibilidades de ganar el premio:

Primero, es importante reconocer que hay tres posibles puertas que el concursante puede elegir, y solo una de ellas contiene el premio. Por lo tanto, la probabilidad inicial de ganar el premio es del 1/3.

Después de que el concursante hace su elección inicial, el presentador Monty Hall abre una de las dos puertas restantes que no tienen el premio detrás. Esto no cambia la probabilidad de que la puerta elegida por el concursante contenga el premio, que sigue siendo del 1/3.

Sin embargo, el hecho de que Monty abra una de las dos puertas restantes proporciona información adicional al concursante. En particular, revela que una de las puertas restantes no tiene el premio detrás. Como resultado, la probabilidad de que la puerta no elegida por el concursante contenga el premio se convierte en 2/3, ya que solo hay dos posibles puertas que no han sido elegidas.

Por lo tanto, si el concursante cambia de puerta después de que Monty haya abierto una de las dos puertas restantes, la probabilidad de ganar el premio aumenta a 2/3. Si el concursante decide quedarse con su elección original, la probabilidad de ganar sigue siendo del 1/3.

En resumen, la respuesta de von Savant es correcta porque si el concursante cambia de puerta después de que Monty abra una de las dos puertas restantes, la probabilidad de ganar el premio aumenta del 1/3 inicial a 2/3. Esta conclusión se puede demostrar matemáticamente utilizando la teoría de probabilidad y la ley de Bayes.

A continuación, diseñarás un experimento numérico que verifique el resultado anterior. 

1. Escribe una función para similar un juego de Monty Hall que realice las siguientes instrucciones:

   1.   Crea un lista con las tres puertas

   1.   Escondemos el premio detrás de una de las puertas de manera aleatoria    

   1.   Monty abre una puerta que no tiene el premio ni ha sido elegida por el concursante

   1.   Si el concursante cambia de puerta, elegimos la puerta que no ha sido elegida y que no ha sido abierta por Monty

   1.   Si el concursante cambia de puerta, elegimos la puerta que no ha sido elegida y que no ha sido abierta por Monty 

   1.   Devolvemos True si el concursante ha ganado el premio, False en caso contrario 


1.   Escribe una función para simular varios juegos de Monty Hall y calcular la probabilidad de ganar el premio
2.   Simula 10,000 juegos de Monty Hall
3.   Calcula la probabilidad de ganar el premio sin cambiar de puerta
4.   Calcula la probabilidad de ganar el premio cambiando de puerta

### Problema 2

Hay tres categorías de contribuyentes de impuestos sobre la renta en los Estados Unidos: los que nunca evaden impuestos, los que a veces lo hacen y los que siempre lo hacen.

Un examen de las declaraciones de impuestos auditadas de un año al siguiente muestra que de aquellos que no evadieron impuestos el año pasado, el 95% continúa en la misma categoría este año, el 4% pasa a la categoría "a veces" y el resto se mueve a la categoría "siempre".

Para aquellos que a veces evaden impuestos, el 6% pasa a "nunca", el 90% permanece igual y el 4% pasa a "siempre". En cuanto a los evasores “siempre”, los porcentajes respectivos son 0%, 10% y 90%.

1. Expresa el problema en términos de una cadena de Markov, justificando detalladamente la elección de tu modelo. 
2. Calcula la distribución estacionaria utilizando eigenvectores. 
3. Calcula la distribución estacionaria, de forma numérica, iterando la matriz de transición.
4. Verifica que ambos resultados coincidan y explica este resultado en términos de nuestro problema de impuestos.
5. Las estadísticas muestran que un contribuyente en la categoría "a veces" evade impuestos aproximadamente $\$5000$ por declaración y en la categoría "siempre" sobre alrededor de $\$12,000. $Suponiendo que la población de contribuyentes es de 70 millones y que la tasa de impuesto sobre la renta promedio es del 12%, determinar la reducción anual de los impuestos recaudados por evasión.

## Bibliografía

- Hoel, P. G., Port, S. C., Stone, C. J. (1971). Introduction to Probability Theory. Taiwan: Houghton Mifflin.
- Hoel, P. G. (1954). Introduction to mathematical statistics. United Kingdom: Wiley.
- Hoel, P. G., Port, S. C., & Stone, C. J. (1986). Introduction to Stochastic Processes. Waveland Press.
- Taha, H. A. (2018). Operations Research: An Introduction, Global Edition. United Kingdom: Pearson Education.