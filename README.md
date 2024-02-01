# Práctica 4: Algoritmos de ordenamiento

- Candelaria Rivera Emiliano 
- 2223068382
- Estructura de datos lineales

## Introducción

En el siguiente reporte se analizaran los resultados obtenidos durante la práctica experimental de evaluar diversos algoritmos de ordenamiento. La experimentación consistio en la comparación de algoritmos iterativos (Insertion Sort, Selection Sort, Bubble Sort) y algoritmos recursivos (Merge Sort, Quick Sort), con el propósito de verificar de manera experimental la eficiencia y el comportamiento de estos algoritmos frente a conjuntos de datos de diferentes tamaños.

## Objetivos

- El propósito de la práctica es evaluar y comprar el rendimiento de diferentes algoritmos de ordenamiento al clasificar arreglos de diferentes tamaños. 

## 1. Resumen de resultados

### Tamaño de arreglo (n = 5000)

- Tabla de resultados

![](https://github.com/AGN-Teaching/practica-4-algoritmos-de-ordenamiento-Cande99/blob/main/imagenes/tabla%205000.jpg)

- Promedio y desviación estandar 

![](https://github.com/AGN-Teaching/practica-4-algoritmos-de-ordenamiento-Cande99/blob/main/imagenes/pyd%205000.jpg)

### Tamaño de arreglo (n = 10000)

- Tabla de resultados

![](https://github.com/AGN-Teaching/practica-4-algoritmos-de-ordenamiento-Cande99/blob/main/imagenes/tabla%2010mil.jpg)

- Promedio y desviación estandar 

![](https://github.com/AGN-Teaching/practica-4-algoritmos-de-ordenamiento-Cande99/blob/main/imagenes/pyd%2010mil.jpg)

### Tamaño de arreglo (n = 50000)

- Tabla de resultados

![](https://github.com/AGN-Teaching/practica-4-algoritmos-de-ordenamiento-Cande99/blob/main/imagenes/tabla%2050mil.jpg)

- Promedio y desviación estandar 

![](https://github.com/AGN-Teaching/practica-4-algoritmos-de-ordenamiento-Cande99/blob/main/imagenes/pyd%2050mil.jpg)

### Tamaño de arreglo (n = 100000)

- Tabla de resultados

![](https://github.com/AGN-Teaching/practica-4-algoritmos-de-ordenamiento-Cande99/blob/main/imagenes/tabla100mil.jpg)

- Promedio y desviación estandar 

![](https://github.com/AGN-Teaching/practica-4-algoritmos-de-ordenamiento-Cande99/blob/main/imagenes/pyd%20100mil.jpg)

## 2. Graficas y tablas de resultados

- Tabla de resultados de calcular el promedio y la desviación estándar

![](https://github.com/AGN-Teaching/practica-4-algoritmos-de-ordenamiento-Cande99/blob/main/imagenes/tablas%20de%20promedio%20y%20d.%20e..jpg)

- Graficas de resultados

![](https://github.com/AGN-Teaching/practica-4-algoritmos-de-ordenamiento-Cande99/blob/main/imagenes/grafica%205k.jpg)
Grafica 1


![](https://github.com/AGN-Teaching/practica-4-algoritmos-de-ordenamiento-Cande99/blob/main/imagenes/grafica%2010k.jpg)
Grafica 2


![](https://github.com/AGN-Teaching/practica-4-algoritmos-de-ordenamiento-Cande99/blob/main/imagenes/grafica%2050k.jpg)
Grafica 3


![](https://github.com/AGN-Teaching/practica-4-algoritmos-de-ordenamiento-Cande99/blob/main/imagenes/grafica%20100k.jpg)
Grafica 4


## 3. Análisis de resultados

- Los resultados obtenidos muestran claramente que los algoritmos de ordenamiento recursivo tienden a ser mas eficientes. Mientras que los algoritmos iterativos tienen un rendimiento algo mas competitivo en arreglos pequeños, sin embargo, cuando los arreglos incrementan sus tamaño estos tardan mucho mas tiempo.

- Los algoritmos iterativos, al analizar su ejecución muestran una relación de n^2. Esto lo podemos ver en la siguiente grafica comparativa. 

![](https://github.com/AGN-Teaching/practica-4-algoritmos-de-ordenamiento-Cande99/blob/main/imagenes/comparativa%201.jpg)

- Por otro lado, los algoritmos recursivos muestran mas una relación logaritmica lineal, n lg n. Esto se puede apreciar en la siguiente grafica.

![](https://github.com/AGN-Teaching/practica-4-algoritmos-de-ordenamiento-Cande99/blob/main/imagenes/comparativa%202.jpg)

- La desviación estándar es una medida de dispersión que indica cuánto varían los valores en un conjunto de datos con respecto a la media.

- Un aumento significativo en la desviación estándar para los algoritmos iterativos puede sugerir que estos algoritmos son más sensibles a la configuración específica del conjunto de datos. Es decir, pueden comportarse de manera menos consistente para diferentes conjuntos de datos y, por lo tanto, presentar una mayor variabilidad en los tiempos de ejecución.

- Si bien también se observa un aumento en la desviación estándar para los algoritmos recursivos, pero en menor medida que en los iterativos, esto podría indicar que los algoritmos recursivos son más estables y muestran una respuesta más consistente frente a diferentes conjuntos de datos. Es posible que su rendimiento no se vea tan afectado por las particularidades de los datos.

## 4. Conclusiones

- Se observó que, en general, los algoritmos recursivos (Merge Sort, Quick Sort) exhiben un rendimiento más eficiente en conjuntos de datos más extensos, mientras que los algoritmos iterativos (Insertion Sort, Selection Sort, Bubble Sort) pueden ser más competitivos en conjuntos de datos más pequeños.

- Se observó un aumento en la desviación estándar para los algoritmos iterativos en comparación con los algoritmos recursivos. Esto sugiere que los algoritmos iterativos son más sensibles a las variaciones en la configuración de los datos, mientras que los algoritmos recursivos muestran una respuesta más estable.
