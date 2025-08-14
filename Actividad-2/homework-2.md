## Tarea 2: Tienen una tarjeta de $10.000.000. Calcular el valor de todas las cuotas sabiendo:
# Valor de la compra
# Tasa de interés del 2%
# Número de cuotas. Máximo 36. 

### Análisis

| Variable de entrada | Descripción                        |
|---------------------|------------------------------------|
| valor_compra        | Valor total de la compra           |
| num_cuotas          | Número de cuotas (máximo 36)       |

| Variables de salida | Descripción                        |
|---------------------|------------------------------------|
| valor_cuota         | Valor de cada cuota                |
| total_pagar         | Total a pagar al final             |

| Variables intermedias | Descripción                      |
|-----------------------|----------------------------------|
| interes_mensual       | Interés aplicado cada mes (2%)   |
| i                     | Contador para el bucle de cuotas |

| Constantes            | Descripción                      |
|-----------------------|----------------------------------|
| tasa_interes          | 0.02 (2% mensual)                |
| cupo_tarjeta          | $10,000,000                      |

### Pseudocódigo

``````
Inicio
Leer valor_compra
Leer num_cuotas
Si num_cuotas > 36
     Mostrar "El número maximo de cuotas es 36"
     Fin
Fin si

Si valor_compra > cupo_tarjeta entonces
    Mostrar "La compra excede el cupo de la tarjeta"
    Fin
Fin Si

interes_mensual = tasa_interes
total_pagar = valor_compra * (1 + interes_mensual * num_cuotas)
valor_cuota = total_pagar / num_cuotas

Para i = 1 hasta num_cuotas hacer  
      Mostrar "Cuota", i, ":", valor_cuota  
Fin Para 

Mostrar "Valor de cada cuota:", valor_cuota
Mostrar "Total a pagar:", total_pagar
Fin