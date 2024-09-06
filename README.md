[![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=luisjavier-ontanon/ParallelBifurcationDynamicalSystem)

# Cálculo de bifurcación de sistema dinámico con Paralelización de núcleos. 

## Autores
Luis Javier Ontañón García Pimentel  
Coordinación Académica Región Altiplano Oeste, Universidad Autónoma de San Luis Potosí.

Juan Gonzalo Barajas Ramírez  
División de Control y Sistemas Dinámicos, Instituto Potosino de Investigación Científica y Tecnológica.

## Resumen de la actividad
Se calcula el diagrama de bifurcación del sistema de Rössler, a partir de la variación de su párametro b = {0.01,...,2}. Se usan dos tipos de proceso iterativo, el primero es a partir de la paralelización del ciclo for mediante la instrucción parfor. No se hace el ajuste del número de núcleos de la computadora, ya que el algorítmo los calcula inmediatamente al correr la función parfor.
El segundo método, es a partir de un for simple. Esto para contrastar los tiempos de simulación, y si es posible realizar la división de actividades del procesamiento de las señales de tiempo continuo en los diferentes núcleos.

## Abstract
The Rössler system's bifurcation diagram is calculated from the variation of its parameters a,b, or c. Generally, the values are set to b = {0.01,...,2}. Two types of iterative processes are used. The first is from the parallelization of the for cycle using the parfor instruction. The number of computer cores is not adjusted since the algorithm calculates them immediately when the parfor function is run.
The second method is simple. It compares the simulation times and, if possible, divides the activities of processing continuous-time signals between the different cores.
 
