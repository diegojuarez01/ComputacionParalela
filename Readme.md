# Sesion 0

Version notepad ++ 7.4.2 32 bits.

usuario: cp_2017_20

Ssh version: 3.2.9

#!/bin/bash

#$ -N NOMBRE_CORTO

#$ -o Salida.out

#$ -e Error.err

#$ -q cp6.q  // Numero maximo de colas

#$ -pe mpi 4 // Numero procesos

#$ -cwd

. /etc/profile.d/modules.sh
mpirun ./ej 

Comandos basicos
===
qsub MI_SCRIPT (lanzara el script)

qstats (estado de cola)

qdel id_job (para borrar de cola)

# PRACTICA 1

1º operacion se envian repartidos

2º se suman los resultados de cada y se suman.

# PRACTICA 2

$ -pe smp 3 //reserva 3 hilos

export omp_num_threads

//Automatizadores for paralelos o reducciones.

para que funcione la raiz cuadrada en la ejecucion hay que poner -lm.

//Creando ejecutable openmp

gcc -fopenmp -o ejemplo ejemplo1.c

