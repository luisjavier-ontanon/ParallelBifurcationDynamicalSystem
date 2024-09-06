[![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=luisjavier-ontanon/ParallelBifurcationDynamicalSystem)

# Cálculo de bifurcación de sistema dinámico con Paralelización de núcleos. 

## Autores
Luis Javier Ontañón García Pimentel  
Coordinación Académica Región Altiplano Oeste, Universidad Autónoma de San Luis Potosí.

Juan Gonzalo Barajas Ramírez
División de Control y Sistemas Dinámicos, Instituto Potosino de Investigación Científica y Tecnológica.

## Resumen de la actividad
Se calcula el diagrama de bifurcación del sistema de Rössler, a partir de la variación de su párametro . Se usan dos tipos de proceso iterativo, el primero es a partir de la paralelización del ciclo for mediante la instrucción parfor. No se hace el ajuste del número de núcleos de la computadora, ya que el algorítmo los calcula inmediatamente al correr la función parfor.
El segundo método, es a partir de un for simple. Esto para contrastar los tiempos de simulación, y si es posible realizar la división de actividades del procesamiento de las señales de tiempo continuo en los diferentes núcleos.
 
