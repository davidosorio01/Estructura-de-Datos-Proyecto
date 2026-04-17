# Complejidad Algorítmica (Big-O)

## Descripción

Este proyecto tiene como objetivo analizar la **complejidad algorítmica** de distintos algoritmos, utilizando la notación **Big-O** para evaluar cómo crece el tiempo de ejecución a medida que aumenta el tamaño de los datos de entrada.
El análisis de complejidad es fundamental en ciencias de la computación, ya que permite estimar el rendimiento de un algoritmo sin depender del hardware, enfocándose en la cantidad de operaciones necesarias según el tamaño de entrada.


## Objetivos

### Objetivo General

Analizar el comportamiento y rendimiento de diferentes algoritmos mediante la notación **Big-O**, identificando cuál presenta mejor eficiencia computacional.

### Objetivos Específicos

* Comprender el concepto de complejidad algorítmica.
* Implementar algoritmos con diferentes órdenes de complejidad.
* Medir y comparar tiempos de ejecución.

## Dataset

Se utilizaron listas y valores generadas aleatoriamente para simular diferentes tamaños de entrada, permitiendo medir el comportamiento de los algoritmos bajo distintos tamaños de datos.

Los tamaños evaluados fueron variables, aumentando progresivamente para observar cómo escala el tiempo de ejecución.


## Tecnologías Utilizadas
Librerías:
  * time para medir el tiempo de ejecución.
  * random para medir el tiempo de ejecución.


## Implementación

Se implementaron algoritmos con diferentes complejidades temporales:

* **Búsqueda Lineal** O(n)
* **Búsqueda Binaria** O(log n)

La búsqueda lineal recorre secuencialmente los elementos hasta encontrar el valor deseado.
La búsqueda binaria divide repetidamente el conjunto de datos en mitades, reduciendo significativamente el número de comparaciones.

## Resultados

La búsqueda binaria fue más rápida que la lineal, demostrando que los algoritmos O(log n) son más eficientes para manejar grandes volúmenes de datos.

## Equipo

* David Osorio 
* Daniel Sanchez
* Stiven Romero
