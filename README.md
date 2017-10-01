# ComputacionParalela

# Tarea 1. Esquema iterativo

Desarrollar un programa que implemente el siguiente esquema iterativo para k=0..q:
    
 xk+1 = M xk

 xk+1 = (alpha * xk+1) + ((1 - alpha) * xk

Tras cada iteración se calculará la norma euclidea de ||xk+1 - xk||2 y se mostrará en pantalla.
La matriz deberá ser simétrica, con 0 en la diagonal y con un 50% (aproximadamente) de elementos
nulos.



#Tarea 2. Multiplicación Matriz-Matriz

Desarrollar un programa que implemente la multiplicación matriz-matriz. Para ello tomaremos un
tamaño de N=1000.

El cálculo deberá realizarse:

 1. Calculando en 5 funciones diferentes con nombres diferentes, de tal modo que en cada
función se calculan 200 filas de la matriz resultado
 2. Calculando llamando a una misma y única función 12 veces de modo que en cada llamada se
calculen 90 filas, excepto en la última llamada.
ATENCIÓN = Los datos de las matrices y vectores se generarán a elección del programador y
serán de tipo DOUBLE. 
