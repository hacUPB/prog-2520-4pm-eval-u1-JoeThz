## Calcular los años de unas persona con los siguientes datos de: entrada: dia, mes, año; Salida: dia actual, mes actual, año actual.

## Calcular la edad de una persona

### Enunciado
Se requiere calcular la edad de una persona con los siguientes datos de entrada: día, mes y año de nacimiento, día actual, mes actual y año actual.

### Análisis

| Variable de entrada | Descripción                        |
|---------------------|------------------------------------|
| dia_nac             | Día de nacimiento                  |
| mes_nac             | Mes de nacimiento                  |
| año_nac             | Año de nacimiento                  |
| dia_act             | Día actual                         |
| mes_act             | Mes actual                         |
| año_act             | Año actual                         |

| Variables de salida | Descripción                        |
|---------------------|------------------------------------|
| edad                | Edad de la persona en años         |

### Pseudocódigo

Inicio
Leer dia_nac, mes_nac, año_nac
Leer dia_act, mes_act, año_act

Si mes_act > mes_nac o mes_act == mes_nac y dia_act >= dia_nac
     edad = año_act - año_nac
Si no
     edad = año_act - año_nac - 1
Fin Si
Mostrar "La edad de la persona es:", edad
Fin