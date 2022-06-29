# trabajo-tsp-algogen
Trabajo Practico de la catedra Sistemas Paralelos y Distribuidos de la carrera de Ingenieria Informatica de la UCA - Asuncion.

El trabajo consiste en la solucion del Problema del Vendedor Viajante (TSP) utilizando la heuristica de los algoritmos geneticos y paralelizando la ejecucion a nivel de hilos utilizando la herramienta OpenMP.

### Instrucciones para ejecutar el programa

1. Como requisito previo se debe tener instalado el compilador g++.
2. Para compilar ejecutar ejecutar la siguiente linea de comando en la  terminal: 
    `g++ -g -Wall -fopenmp -o tsp_[numero_ciudades] omp_main.cpp`
el numero de ciudades se edita en la variable global *CITIES* en *allinc.h*.
3. Para ejecutar escribir la siguiente linea de commando en la terminal, estableciendo el *numero de hilos*:
    `./tsp_[numero_ciudades] [numero de hilos]`

