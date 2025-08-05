## Un almacén de ropa tiene una promoción: por compras superiores a $250 000 se les aplicará un descuento de 15%, de caso contrario, sólo se aplicará un 8% de descuento. Realice un algoritmo para determinar el precio final que debe pagar una persona por comprar en dicho almacén y de cuánto es el descuento que obtendrá. Represéntelo mediante el pseudocódigo y el diagrama de flujo.

## Análisis

| Variable de entrada | Descripción |
|---------------------|-------------|
|valor_comprar | Costo parcial de las prendas |

| Variables de salida | Descripción |
|---------------------|-------------|
|precio_final | Valor que hay que pagar |
|descuento | Valor del descuento |

| Constantes | Descripción |
|---------------------|-------------|
|250000 | Valor con que se aplíca el descuento |
|8%, 15% | Descuentos |

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