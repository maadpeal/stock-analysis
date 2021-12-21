# stock-analysis
analysis of green power companies

## Purpose

    Ayudar a los padres de steve a determinar si la empresa "DAQO
    New Energy Corp", cumple los requisitos minimos de rentabilidad
    para hacer una inversion y si hay otras empresas que puedan 
    tener un atractivo parecido o incluso mayor que la elegida por 
    los padres de steve, se buscara determinar esto por el retorno
    de las empresas.

## Results

### Comparing "DQ" on 2017 vs 2018

    Si observas en el analisis del 2017 esta empresa tiene un gran
    retorno para ese ano (image A-1), es la que mejor retorno tiene de todas
    las analizadas pero si la vemos un ano despues tiene un comportamiento
    negativo de hecho es la que mas fuerte cae de todas lo cual nos indica 
    que posiblemente estaba por sobrecompra (image A-2).
    
![](https://github.com/maadpeal/stock-analysis/blob/main/Resources/A-1.png) A-1
![](https://github.com/maadpeal/stock-analysis/blob/main/Resources/A-2.png) A-2
  
### Comparing the others companies

    Si observamos el cuadro resumen de todas las empresas nos daremos cuenta
    que solo hay dos que mantuvieron su retorno en numeros positivos como son 
    "ENPH" y "RUN". ENPH tiene un retorno en el 2017 de 129,5% y el 2018 81,9%
    lo cual la podria hacer mas atractiva, por su parte "RUN" en el 2017 tiene
    un retorno de 5,5% y el 2018 de 84%, la hace una opcion viable pero no tan
    atractiva como la anterior (images B1, B2).
    
![](https://github.com/maadpeal/stock-analysis/blob/main/Resources/B-1.png) B-1
![](https://github.com/maadpeal/stock-analysis/blob/main/Resources/B-2.png) B-2

### Anothers observation

    Trate de determinar si exista algun patron evidente para tomar una decision
    sobre cual era la mejor opcion para invertir, si por ejemplo tomamos en cuenta
    el factor de volumen diario nos encontramos que aquellas que tenian mayor
    volumen tambien sufrieron perdidas en el retorno y aquellas que tenian menor
    volumen tambien cayeron, las dos empresas que lograron escapar el retroceso del
    retorno tienen volumenes diarios parecidos en el 2017, sin embargo "" SEDG tiene
    un volumne parecido sin embargo presento un retroceso, minimo pero igual lo sufrio,
    lo cual parece no ser el mejor de los indicadores para evaluar una empresa de 
    inversion, por ende lo mejor en este caso es obtener 
    mas data para que nos ayude a tomar una decision mas informada y claro esta, 
    mas cantidad de empresas para analizar si podremos encontrar un patron en alguna
    otra (image C-1, C-2).
    
![](https://github.com/maadpeal/stock-analysis/blob/main/Resources/C-1.png) C-1
![](https://github.com/maadpeal/stock-analysis/blob/main/Resources/C-2.png) C-2

### Executions

    Original code 2017 (image D-1)
    Refactor code 2017 (image D-2)
    
![](https://github.com/maadpeal/stock-analysis/blob/main/Resources/base_2017.png) D-1
![](https://github.com/maadpeal/stock-analysis/blob/main/Resources/VBA_Challenge_2017.png) D-2

    Original code 2018 (image E-1)
    Refactor code 2018 (image E-2)
    
![](https://github.com/maadpeal/stock-analysis/blob/main/Resources/base_2018.png) E-1
![](https://github.com/maadpeal/stock-analysis/blob/main/Resources/VBA_Challenge_2018.png) E-2

## Summary

    - What are the advantages or disadvantages of refactoring code?


#### Ventajas

     1. Nos permite optimizar codigo que consume recursos en exceso.
     2. Podemos hacer mas claro el codigo con comentarios y nombres de variables mas explicativas
     3. Agregar funcionalidad

#### Desventajas

    1. Debes tener conocimiento del funcionamiento general del codigo
    2. Podrias romper el codigo generando outputs equivocados o simplemente puede dejar de funcionar

    - How do these pros and cons apply to refactoring the original VBA script?

    El de optimizar los tiempos de ejecucion ya que ahora corre aproximadamente 3 veces mas rapido, tambien el de agregar funcionalidad por que generamos arrays adicionales para usarlos de manera mas optima.

    En lo que podria ser contras esta el del conocimiento general del codigo, tuve
    que realizar todo el modulo para saber de que iba el codigo para poder refactorizarlo
    con confianza.


    
