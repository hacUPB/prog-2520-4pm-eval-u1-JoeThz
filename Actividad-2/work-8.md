## Un profesor tiene un salario inicial de $1500, y recibe un incremento de 10 % anual durante 6 años. ¿Cuál es su salario al cabo de 6 años? ¿Qué salario ha recibido en cada uno de los 6 años? Realice el algoritmo y represente la solución mediante el diagrama de flujo, el pseudocódigo y el diagrama N/S, utilizando el ciclo apropiado.

### Análisis.

| Variables de entrada | Descripción |
|----------------------|-------------|
| | |

| Variables de salida | Descripción |
|----------------------|-------------|
|anual | Valor del salario cada año |
|total | Valor del salario a los 6 años |

| Control | Descripción |
|----------------------|-------------|
|año | 

### Pseudocódigo.
``````
Inicio
año = 1
sal = 1500
total = 0
Mientras año <= 6
     anual = sal * 1.1
     total = total + sal
     sal = anual
     año = año + 1
     Mostrar anual
Fin Mientras
Mostrar total
Fin