# Proyecto final materia Aprendizaje no supervisado.

Integrantes: Edgar Balaguera, Maria Paula Cortes, Alexis Abreu y Ricardo Pretelt.

Título del proyecto: ¿Cómo determinar la estructura del mercado de valores en términos de la correlación condicional entre instrumentos financieros para la ayuda en la toma de decisiones de inversión?

## Resumen
Se implementará un algoritmo de clustering que a partir de analizar las correlaciones condicionadas entre los precios de cierre de las acciones seleccionadas en el período de 1 de enero de 2018 a 30 de junio de 2022 se logra encontrar patrones similares en los movimientos del precio de las acciones y determinar a través de estas similitudes que acciones tienen los mismos comportamientos para diversificar las inversiones.
Se parte de la agrupación de las acciones por el comportamiento en su precio en el mercado, analizar su rendimiento y así poder establecer una medida de comparación con las demás. Una vez se establecen las medidas de comparación se realizará un proceso de clustering con GraphicalLassoCV. Para que el clustering de resultado sea graficado se utiliza un embedding de 2 dimensiones. 
El objetivo del proyecto es identificar los instrumentos financieros con comportamientos similares e identificar, por ende, las posiciones de mayor rentabilidad al momento de tomar una decisión de inversión. Estos agrupamientos permiten aumentar la posibilidad de rentabilidad positiva a partir del entendimiento de más de 1 cluster, es decir diversificar el portafolio de inversión.
En el proceso de clustering estos grupos con comportamientos similares deben ser mutuamente excluyentes; es decir, cada instrumento debe pertenecer a un sólo grupo y cada grupo debe estar formado por empresas en el que su comportamiento sea lo más parecido posible y a la vez, con comportamientos diferentes entre grupos. En la práctica, se busca encontrar grupos con elementos lo más homogéneos posibles pero heterogéneos entre ellos.

## Video del proyecto
[https://youtu.be/pXtEo1KKN4c](click para ir a youtube)

## Contenido
En el repositorio encontrarás
1. Carpeta con datos
2. Notebook de jupyter con código del modelo
3. Documento final.

