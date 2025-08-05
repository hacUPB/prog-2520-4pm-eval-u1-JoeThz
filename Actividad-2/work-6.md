## El director de una escuela está organizando un viaje de estudios, y requiere determinar cuánto debe cobrar a cada alumno y cuánto debe pagar a la compañía de viajes por el servicio. La forma de cobrar es la siguiente: si son 100 alumnos o más, el costo por cada alumno es de $65.00; de 50 a 99 alumnos, el costo es de $70.00, de 30 a 49, de $95.00, y si son menos de 30, el costo de la renta del autobús es de $4000.00, sin importar el número de alumnos.

### Análisis.

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


## Pseudocódigo

Inicio
Leer valor_compra > 250000
     descuento = valor_compra * 0.15
Si no
     descuento = valor_compra * 0.08
Fin Si
precio_final = valor_compra - descuento
Escribir "Total a pagar:", precio_final
Fin