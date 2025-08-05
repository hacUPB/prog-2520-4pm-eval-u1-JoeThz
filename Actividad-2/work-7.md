## Una tienda de ropa tiene la siguiente promoción: por la compra de tres productos, la prendas de menor valor, tiene un 70% de descuento. Calcular cúal fue el descuento aplicado y cuánto tiene que pagar la persona.

### Análisis.

| Variable de entrada | Descripción |
|---------------------|-------------|
| pto1 | Costro prenda 1 | 
| pto2 | Costro prenda 2 | 
| pto3 | Costro prenda 3 | 

| Variables de salida | Descripción |
|---------------------|-------------|
|precio_final | Valor que hay que pagar |
|descuento | Valor del descuento |

| Constantes | Descripción |
|---------------------|-------------|
|0.70 | Descuento |

### Pseudocódigo.

Inicio
Leer pto1, pto2, pto2
Si pto1 < pto2 y pto 1 < pto 3
     descuento = pto1 * 0.70
     precio_final = descuento + pto2 + pto3
Si pto2 < pto1 y pto 2 < pto 3
     descuento = pto2 * 0.70
     precio_final = descuento + pto1 + pto3
Si pto3 < pto1 y pto 3 < pto 2
     descuento = pto3 * 0.70
     precio_final = descuento + pto1 + pto2
Fin Si
Mostrar "Total a pagar:", precio_final, descuento 
Fin