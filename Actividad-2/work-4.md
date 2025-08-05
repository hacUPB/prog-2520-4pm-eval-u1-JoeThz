## Realice un algoritmo para determinar cuánto se debe pagar por equis cantidad de lápices considerando que si son 1000 o más el costo es de $85 cada uno; de lo contrario, el precio es de $90. Represéntelo con el pseudocódigo y el diagrama de flujo.

### Analisis.

| Variable de entrada | Descripción |
|---------------------|-------------|
|cant_lapices | Cuántos lápices se compran |

| Variables de salida | Descripción |
|---------------------|-------------|
|precio | Valor que hay que pagar |

| Variables Intermedias | Descripción |
|-----------------------|-------------|
|valor_unidad | Valor usado dentro del codigo |

| Constantes | Descripción |
|---------------------|-------------|
|1000 | Cantidad limite de lápices |
|$85 | Valor individual según la cantidad |

## Pseudocódigo.

Inicio
Leer cant_lápices >=1000
    valor_unidad = 85
Si no
    valor_unidad = 90
Fin Si
precio = valor_unidad * cant_lápices
Escribir "valor total:", precio
Fin
