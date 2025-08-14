## En una pista de pruebas de aeronaves, el sistema debe verificar si el peso total de la aeronave, incluyendo combustible y carga, supera el límite máximo permitido para el despegue. Dependiendo del resultado, el sistema deberá indicar si la aeronave está lista para despegar o si debe reducir carga o combustible.

### Análisis.

| Variables de entrada | Descripción |
|----------------------|-------------|
|carga | El peso de la carga de la aeronave |
|combustible | El peso que carga la aeronave en combustible  |

| Variables Intermedias | Descripción |
|-----------------------|-------------|
|peso_total | El peso total que carga la aeronave |

| Constante | Descripción |
|----------------------|-------------|
|5000 | Peso limite en Kilogramos |

### Pseudocódigo.

``````
Inicio

Leer carga, combustible

peso_total = carga + combustible

Si peso_total > 5000
     Mostrar "La aeronave no está lista para el despegue"
Si no
     Mostrar "La aeronave está lista para despegar"
Fin Si
Fin
``````
---

## Durante una inspección de rutina, se mide la temperatura de un motor de turbina. Si la temperatura es mayor a un valor crítico, se debe indicar "Peligro: sobrecalentamiento". Si está dentro del rango seguro, indicar "Operación normal". Si es demasiado baja, indicar "Motor frío – Calentar antes de operar".

### Análisis.

| Variable de entrada | Descripción |
|---------------------|-------------|
|temperatura | La temperatura del motor |

| Constantes | Descripción |
|---------------------|-------------|
|1500 | Temperatura critica del motor, en grados Celsius |
|400 | Temperatura miníma del motor, en grados Celsius |

### Pseudocódigo.

``````
Inicio

Leer temperatura

Si temperatura > 1500
     Mostrar "Peligo: sobrecalentamiento"
Si no
     Si temperatura < 1500 y temperatura > 400
     Mostrar "Operación normal"
     Si no
         Mostrar "Motor frío-Calentar antes de operar"
Fin Si

Fin
``````

---
## Un sistema debe registrar la altitud de vuelo cada 10 minutos durante una hora y mostrar todas las mediciones al final.

### Análisis.

| Variable de entrada | Descripción |
|---------------------|-------------|
|altitud |  |

| Variables de salida | Descripción |
|---------------------|-------------|
|altitud |  |

| Variables Intermedias | Descripción |
|-----------------------|-------------|
|datos |  |

| Control | Descripción |
|----------------------|-------------|
|i | |

| Constante | Descripción |
|----------------------|-------------|
|10 |  

### Pseudocódigo.

``````
Inicio

i = 0

Mientras i < 6
     Leer datos
     datos [i] = altitud
     i = i + 1
Fin Mientras

Fin
``````
