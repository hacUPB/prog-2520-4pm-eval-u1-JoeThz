1. Explica, en tus propias palabras, por qué es necesario que las computadoras representen los datos en binario.
2. Convierte el número binario 10011011 a decimal y a hexadecimal.
3. Investiga y describe cómo se representa una imagen en formato PNG en el disco.
4. Analiza la siguiente situación: ¿Qué sucede si intentas almacenar un número mayor al que puede representar un byte (por ejemplo, 300)? ¿Cómo lo maneja Python?

# solución:

1. Las computadoras representan los datos en binario porque solo pueden distinguir dos estados físicos (como encendido/apagado o presencia/ausencia de voltaje). Usar el sistema binario (0 y 1) permite que los circuitos electrónicos sean más simples, confiables y eficientes.

2.  
- Binario 10011011 a decimal:  
  1×128 + 0×64 + 0×32 + 1×16 + 1×8 + 0×4 + 1×2 + 1×1 = 128 + 16 + 8 + 2 + 1 = **155**
- Binario 10011011 a hexadecimal:  
  Agrupando de 4 en 4: 1001 1011  
  1001 = 9, 1011 = B  
  Resultado: **0x9B**

3. Una imagen PNG se guarda en disco como una secuencia de bytes que incluye una cabecera (con información como el tamaño y tipo de imagen), datos comprimidos de los píxeles (usando compresión sin pérdida), y metadatos opcionales. Los colores se representan en formato RGB o RGBA, y la compresión permite que el archivo ocupe menos espacio sin perder calidad.

4. Un byte puede almacenar valores de 0 a 255. Si intentas guardar un número mayor (como 300) en un solo byte, solo se almacenan los 8 bits menos significativos, lo que causa un "desbordamiento" y el valor almacenado será 44 (300 - 256).  
En Python, los enteros no tienen límite fijo de tamaño, así que se pueden trabajar con números grandes sin problema. Pero si se convierte un número grande a un tipo de dato de un byte, Python lanzará un error si el número es mayor a 255.