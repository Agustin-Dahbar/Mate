<!-- DRIVE -->
https://drive.google.com/drive/folders/1Ch_SanU-f4Yzugo-z2v0gY4IzaHBRNRG

<!-- 1RA CLASE -->
Sistemas de númeración. Veremos los distintos tipos de númeración (decimal, binario, hexadecimal, octal) y las conversiones de un sistema a otro. Además veremos el teorema fundamental de la numeración (cuando y como aplicarlo).   

<!-- Sistemas de númeración -->
Son un conjunto de simbolos y reglas que se utilizan para la representación de datos númericos o cantidades.

Número con su base (el (10 va pequeño por debajo, como la potencia pero en la parte inferior)) :
1936(10                                                                                                     )
Este número esta en el sistema decimal ya que tiene base 10.

1. <!-- SISTEMA DECIMAL  -->
Es un sistema posicional que usa los primeros 10 carácteres (del 0 al 9)
<!-- Como aplicar el teorema fundamental de la numeración cuando queramos hacer la conversión de un numero en x base a base 10. -->
<!-- (En la guía hay muchos ejs de este teorema) 
Ejemplo aplicandolo en un número con base 10: -->
23,1416(10 =                        )
<!-- Habiamos dicho que el sistema decimal es un sistema posicional, es decir sus digitos tienen una posición. Estas posiciones las identificamos referenciandonos con la coma, los números a su derecha, es decir los decimales, son negativos, y los números de su izquierda son positivos. El número antes de la coma vale 0 y el número después de la coma vale -1. -->
<!-- En este caso las posiciones son:  -->
2 = 1
3 = 0
,
1 = -1
4 = -2
1 = -3
6 = -4
<!-- Ahora con los números, sus posiciones y la base del número podemos llevar a cabo el teorema, que consiste en sumar los productos. 
Pero, ¿los productos de que? De una multiplicación que se hará por cada número existente. 
Esta será: el digito * su base elevado a la posición. Las multiplicaciones pueden ser desde atras o desde adelante.--> Teorema: digito * base a la posición
6 * 10 a la -4 + 
1 * 10 a la -3 + 
4 * 10 a la -2 + 
1 * 10 a la -1 + 
3 * 10 a la 0 + 
2 * 10 a la 1 == resultado.

<!-- A esto se le llama aplicarle el teorema fundamental a un número.. Pero ahora queremos ver la definición expresada correctamente, la siguiente: -->
<img src="TeoremaExpresado.png">
<!--
Que es similar pero remplazando los digitos con una X acompañada del número de su posición en la esquina inferior derecha, y reemplazando también el número de la base por una B con el número de la posición como potencia 
-->
X(3 * B(3  +                                                )) 
<!-- Y sigue con el resto de multiplicaciones según la cantidad de dígitos. Será una multiplicación por cada dígito. Recordemos, se multiplica a el por su base elevada en por la posición en la que se encuentre. Y recordemos también que las posiciones se identifican desde la coma, los números de su izquierda son números + comenzando desde 0, y hacia su derecha son números negativos comenzando desde -1.  -->

Ahora daré un número al azar y lo escribiré en ambas fórmulas.
10,516 a la 10

<!-- Aplicación -->
1 * 10 a la 1
0 * 10 a la 0
5 * 10 a la -1
1 * 10 a la -2
6 * 10 a la -3

<!-- Definición -->
1(1 * 10(1  +  0(0 * 10(0  +  5(-1 * 10(-1  +  1(-2 * 10(-2  +  6(-3 * 10(-3                         )))))))))) 


CONVERSIÓN DE DECIMAL A BINARIO 
<!-- Hay 3 casos. Cuando el número es entero, cuando es decimal sin parte entera (menor a 1), cuando tiene ambas entero y decimales (la más díficil) -->

Número entero. Divisiones sucesivas
<!-- Usaremos el 19. Debemos usar el método de las divisiones sucesivas. Esto consiste en dividir al número sucesivamente por la base a la que lo queremos llevar (en este caso la base 2 del sistema binario) debemos continuar dividiendo los cocientes de la división hasta que encontrar el cociente 0, sin importar el resto final. Ejemplo:  -->

19 / 2    
1   9 / 2
    1   4 / 2
        0   2 / 2
            0   1 / 2
                1   0
<!-- Restos: 1 1 0 0 1 (en el orden obtenido, se deberán invertir para formar el número convertido) -->
<!--Los restos obtenidos por las divisiónes del número principal y los cocientes formarán al número convertido en el sistema deseado. 
Los restos se deben ordenar del último hacia el primero, en este caso el 19 en decimal convertido a binario nos dió 10011(2  -->


Número decimal (menor a 1). Múltiplicaciones sucesivas. 
0,75(10                                                                                                                 )
<!-- El metodo a usar consiste en multiplicar por la base a la que lo queremos llevar (2 en esta caso) al número y luego a los decimales del resultado. Similar al metodo anterior pero en vez de dividiendo cocientes multiplicando decimales. 
Se comienza operando al número inicial y luego se continúa multiplicando a los décimales del resultado hasta obtener un número entero como resultado, sin decimales. Los números enteros que se obtendrán en las multiplicaciones serán los números que formarán al número de la conversión, y estarán ubicados en la posición negativas, es decir las decimales. El primer número entero se ubicará en la posición -1, el siguiente en la posición -2. Resolvemos la conversión de este número para que se comprenda. -->

0,75 * 2 = 1,50 <!--Como dijimos, el número entero es el primer número decimal de la conversión final que se ubicará en P-1 -->
0,50 * 2 = 1    <!--Se frenan las múltiplicaciones sucesivas ya que no tenemos más decimales que multiplicar.-->
<!-- Entonces el número 0,75 en decimal convertido a binario es:  -->
0,11 (2                                     )
<!-- Recordemos que esta elevado a la base del sistema al que lo queremos convertir (binario en este caso) -->
0,75(2 == 0,11(2                                                    ))


<!-- FIN SISTEMA DECIMAL Y SUS CONVERSIONES A BINARIO.-->




2. <!--SISTEMA BINARIO-->
Si un número está en sistema binario su base es 2. Este sistema solo utiliza los números 0 y 1. Es el sistema que usa la pc, el compilador traduce nuestro código a binario para que ella lo entienda.
Si hiciesemos una conversión de binario a decimal estariamos pasando un número de base 2 a base 10.
Un número binario debe tener como dígitos a 1 y/o a 0 y tener de base 2.

<!-- Conversión de un número binario a decimal. Aplicamos el teorema fundamental. Recordemos, este teorema se usa CUANDO QUEREMOS PASAR A DECIMAL, ES DECIR A BASE 10. Por eso lo usamos en este caso. -->
Para realizar la conversión el primer paso es obtener las posiciones de los dígitos, usaremos el número 1101(2                      )
Este número no tiene coma eso significa que estará al final, no tiene decimales. Entonces la posición del último digito 1 es 0, y suma 1 hacia su izquierda. Entonces las multiplicaciones a las que debemos sumar sus productos quedarían así: 

<!-- Cuentas -->
1 * 2 a la 0
0 * 2 a la 1 
1 * 2 a la 2
1 * 2 a la 3

<!-- Formula -->
1(0 * 2(0 + 0(1 * 2(1 + 1(2 * 2(2 + 1(3 * 2(3                                       )))))))) 
    1     +     0      +     4      +      8    = 13
                    
<!-- Este resultado nos informa que el número 1101 en sistema binario equivale al número 10 en sistema decimal -->
1101(2 === 13(10                                                                                                 ))








<!-- 2DA CLASE  -->
<!-- LOGICA -->
Es un lenguaje preciso, claro y formal que estudia a las proposiciones. Su objetivo es interpretar, desarrollar  razonamientos y distinguirlos de los incorrectos.


<!-- ¿Qué es una proposición? -->
Un enunciado que puede ser verdadero o falso. 
Las proposiciones pueden clasificarse, renombrarse. No toda oración es una proposición, para que lo sea se le debe asignar un valor booleano. Si podemos determinar la veracidad de esa oración es una proposición o una oración proposicional. Si no podemos determinar si es verdadera o falsa, esa oración será no proposicional o simplemente una oración. 

<!-- Ejemplos: -->
"Hoy es lunes" <!--Se puede determinar si es verdadero o falso. Falso, hoy es martes. Entonces es una proposición-->
