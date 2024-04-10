<!-- DRIVE -->
https://drive.google.com/drive/folders/1Ch_SanU-f4Yzugo-z2v0gY4IzaHBRNRG

<!-- 2DA CLASE  -->

LOGICA 
<!-- Es un lenguaje preciso, claro y formal que estudia a las proposiciones. Su objetivo es interpretar, desarrollar  razonamientos y distinguirlos de los incorrectos.
En resumen, es un lenguaje que interpreta, desarrolla un razonamiento por el que evalúa si una proposición es V o F. -->

¿Qué es una proposición?
<!-- Un enunciado que puede ser verdadero o falso. 
Las proposiciones pueden clasificarse, renombrarse. No toda oración es una proposición, para que lo sea se le debe poder asignar un valor booleano. Si no podemos es simplemente una oración.  -->

<!-- Ejemplo: -->
"Hoy es lunes" <!--Se puede determinar si es verdadero o falso. Falso, hoy es martes. Entonces es una proposición-->

<!-- Las proposiciones se suelen representar por las letras p, q, r, i, s. -->
<!-- Ejemplos:  -->
p: 15 + 5 = 20. <!--Se le puede asignar TRUE por lo tanto es proposición y no una ordinaria oración. -->
q: 10 es un número primo <!--Es FALSE. Se puede dividir por 1, 5 y 10. --> 
r: el cielo es verde <!--Es FALSE. Es celeste. -->

<!-- Notación para asignar el valor booleano de la proposición. Hacemos referencia a la proposición con su letra dentro de los () -->
V(p) = V 
V(q) = F
V(r) = F 


<!-- Las oraciones exclamativas, interrogativas e imperativas no tienen valor booleano asignable, por lo tanto son oraciones sin más. No proposiciones -->
¿Cómo estás?
¡Qué lindo día!
Despertate


<!-- CLASIFICACIÓN DE LAS PROPOSICIONES -->
Las proposiciones pueden ser simples/atómicas o las proposiciones compuestas/moleculares. Las identificamos por la cantidad de variables en la oración. Si tienen una sola variable son simple si tienen más son compuestos. Las variables simples (una única variable) no tienen conectivos lógicos, ya que estos sirven para UNIR variables.  

<!-- Simples -->
Hoy voy al cine.
El martes llueve.
Ana es buena estudiante.

<!-- Compuestas -->
Hoy voy al cine o al teatro.
Si hoy llueve, entonces voy al cine.

<!-- Como vemos la diferencia entre ellas es que en las compuestas hay un conectivo que une dos proposiciones simples. Los conectivos son "O" y "Entonces"  -->

En la siguiente imagen veremos como las proposiciones compuestas tienen dos variables y un conectivo lógico entre ellas. 
<img src="SimplesCompuestas.png">
<!-- En la imagen vemos como en las compuestas hay dos letras que representan a las dos variables/proposiciones. 
En la primer proposición compuesta no se ve bien donde se ubica el conector, en la segunda se ubica en la segunda proposición. Preguntar al profe o a chat si se puede ubicar el conector en cualquier variable/proposición o si debe ir en alguna específicamente.  -->
Hoy voy al cine o al teatro.
Si hoy llueve, entonces voy al cine.
<!-- Al costado de las oraciones se nos muestra la forma simbólica que es con la que trabajaremos.. Esta forma consiste en la letra que representa a la oración con el conectivo donde corresponda. En el primer caso se encuentra entre medio de ambas oraciones y el conectivo utilizado es el O. En el segundo caso usamos el conectivo implicación/condicional y también lo ubicamos entre medio   -->


<!-- CONECTIVOS LÓGICOS -->
Sirven para unir variables. Si la oración tiene un conectivo lógico separará dos variables. Si tiene 2 conectivos lógicos separará 3 variables. Siempré una variable más de la cantidad de conectivos. Si no tiene ningun conectivo lógico, significa que tiene solo una variable. Los conectivos son:
1. Negación                                     ~           no
2. Conjunción                                   ∧           y
3. Disyunción inclusiva                         ∨           o
5. Implicación/Condicional                      →           Implica condición
6. Doble Implicacion/Doble Condicional          ↔           Implica equidad o doble condición

<img src="ConectivosLogicos.png">
<img src="ConectivovsLogicos2.png"> <!--Falta la disyuncion exclusiva en este cuadro que es el mismo signo que la inclusiva pero con una plataforma debajo del signo. -->

<!-- Ejs de cada uno -->
1. Negacion (no)
p: Hoy llueve.
<!-- Simbólico:  -->
~p 
==
No llueve.
No es cierto que llueve.


2. Conjunción (y)
<!-- Simbólico. -->
p∧q 
==
Hoy llueve y voy al teatro. 
p: Hoy llueve
q: voy al teatro


3. Disyunción (o)
<!-- Simbólico -->
p∨q
==
Hoy voy al teatro o al cine.
p: Hoy voy al teatro
q: al cine  <!--Sospecho esta es la correcta-->
q: Hoy voy al cine <!--Sospecho esta es la incorrecta-->

¿Cuál es el valor de la variable q (la oración simple)?


4. Condicional (Implica que se cumpla una condición para la ejecución de una acción posterior)
Si hoy llueve entonces no voy al teatro
<!-- Simbólico -->
p→~q
==
p: Si hoy llueve
q: no voy al teatro

<!-- También agregamos el conectivo de negación, ya que se usó en la oración compuesta. Usamos dos conectivos para unir dos variables. -->


5. Doble Condicional (Implica que se deba cumplir una condición mediante una única posibilidad y no haya múltiples que la puedan hacer cumplir)

Dos rectas son paralelas, si y solo si, sus pendientes son iguales.
<!--Simbólico: -->
p↔q
==
p: Dos rectas son paralelas
q: sus pendientes son iguales. 

<!-- Tambíen podemos usar este conectivo para cosas equivalentes, ejemplo. -->
Oso es equivalente a bear.
<!-- Simbólico:  -->
p↔q
==
p: Oso es
q: a bear




<!-- TABLAS DE VALORES DE VERDAD  -->
Una tabla de valores de verdad de una proposición compuesta es una tabla que se arma con los posibles valores de verdad de las proposiciones simples que la componen, con la finalidad de obtener el valor de verdad de la proposición dada.
La cantidad de valores de verdad de la tabla se determinará por elevar al 2 la cantidad de proposiciones simples que la conforman. ¿Por que por 2? Por que recordemos que son dos los valores booleanos que podrán ser devueltos. Y por eso se eleva ese número por la cantidad de proposiciones de la tabla. Es decir si tengo p∧q. Tengo dos proposiciones en un conector de unión (conjunción). Entonces multiplicamos 2 a la 2. Nos da 4. Esta será la cantidad total de valores booleanos posibles. 2 por cada proposición. Si fuesen 3 proposiciones 2 a la 3 lo que nos da 6 y así. Básicamente se multiplican por 2 la cantidad de proposiciones simples. 
En la tabla, a la primer letra se la llamará antecedente, a la segunda consecuente. 


<!-- Mitad de valores diferentes letras  -->
En las tablas de valores las letras siguientes tendrán la mitad de valores de verdad que la anterior. Ejemplo de esto
p ∧ q
v   v
v   f
f   v   
f   f
<!-- Esto sucederá hasta que quede vfvf, siempre se dividirá en dos la cantidad de verdaderos, ejemplo si el consecuente tuviese vvff deberá existir otra letra si o si para obtener el vfvf final. EJEMPLO:  -->
r ∧ s ∧ p
V   V   V    
V   V   F
V   F   V   
V   F   F
F
F
F
F


<!-- IMÁGENES DE LAS TABLAS Y SU DESARROLLO: -->
<!-- NEGACIÓN (NO): -->
<img src="tablaNegacion.png"> <!-- 
P   ~P                        -->
V   F
F   V
<!-- Si p es verdadero, su negación es falsa y viceversa. Esto siempre será así. Es imposible que la proposición tenga un valor de verdad equivalente al de su negación. Siempre serán != -->



<!--CONJUNCIÓN (Y):  -->
<img src="TablaConjuncion.png"><!--
P  P∧Q  Q                      --> Se nos dan 2 proposiciones, es decir 4 valores de verdad en la tabla.
V   V   V
V   F   F
F   F   V  
F   F   F

<!-- La conjunción solo será verdadero cuando se cumplan ambas proposiciones, equivalente al operador && (AND).  -->

p: Estoy estudiando
q: Estoy viendo la tele.

p∧q = Estoy estudiando y estoy viendo la tele



<!-- DISYUNCIÓN (O): -->
<img src="TablaDisyuncion.png"><!--
P   P∨Q   Q                                   --> Son 2 proposiciones por lo tanto 2 a la 2 = 4 valores booleanos en la tabla.
V    V    V
V    V    F
F    V    V
F    F    F 

<!-- En la disyunción solo se dará false cuando ambas proposiciones sean false. Si una o ambas tienen valor true dará true. 
Con que cualquiera de las proposiciones simples sea TRUE ya tendría un valor de verdad de TRUE-->

p: Ire a comer.
q: Ire al cine.

pVq = Ire a comer o al cine.



<!-- CONDICIONAL (→):  -->
<img src="TablaCondicional.png"><!--
P   P→Q   Q                      -->
V    V    V
V    F    F
F    V    V
F    V    F

<!-- La condicional solo es falsa cuando su antecedente es verdadero y su consecuente falso. -->



<!-- DOBLE CONDICIONAL (↔): -->
<img src="TablaDobleCondicional.png"><!--
P   P↔Q   Q                           -->
V    V    V
V    F    F
F    F    V  
F    V    F

<!-- La doble implicación será verdadera cuando las proposiciones tengan el mismo valor booleano. (Ambas F o ambas V). -->
Doble condicional significa que p↔q, es decir que se necesitan una a la otra.
Esa sintaxis de p↔q es el equivalente a (p→q)∧(q→p) que se lee p implica q y q implica p. 
El signo de conjunción representa a la 'y', las otras dos formulas equivalen a p↔q. Por lo tanto la unión de ambas es p↔q.







<!-- Tablas resumen -->
<!-- Conjunción (Y) -->
La conjunción solo será verdadero cuando se cumplan ambas proposiciones, equivalente al operador && (AND).
<!--
P  P∧Q  Q                                                                                                           --> 
V   V   V

<!-- Disyunción (O) -->
En la disyunción solo se dará false cuando ambas proposiciones sean false. Si una o ambas tienen valor true dará true.
<!--
P   P∨Q   Q                                                                                                     -->
F    F    F

<!-- Condicional (entonces) -->
La condicional solo es falsa cuando su antecedente es verdadero y su consecuente falso.
<!--
P   P→Q   Q                                                                                                                     -->
V    F     F
 
<!-- Doble condicional(si y solo si, equivalentes) -->
Será verdadero cuando ambas proposiciones simples tengan el mismo valor booleano. (Ambas F o ambas V).
<!--
P   P↔Q   Q     ||     P   P↔Q   Q                                                                                              -->
V    V    V            F    V    F                                                                                                       

FIN TABLAS


SIGNOS: ↔ → ∧ ∨ ~ 

<!-- CLASIFICACIÓN DE LAS TABLAS -->
De acuerdo a lo que obtengamos en la conclusión del valor booleano de las tablas podremos obtener su clasificación que podrían ser tautología, contradicción o contingencia.

<!-- Tautología -->
Se clasificara así cuando en la conclusión de la tabla todos los valores booleanos sean verdaderos, refiriendonos a la columna importante, los valores de las proposiciones simples no importan. Ejemplo:

<!--    
P       Q       P∧Q        P∧Q → P                        -->
V       V        V           V
V       F        F           V
F       V        F           V
F       F        F           V 

<!-- Contradicción -->
Es al revés a tautología. La conclusión nos deberá dar todos los valores como falsos. Ejemplo:
<!--    
P       ~P     P∧~P                        -->
V       V       V
V       F       V
F       V       V
F       F       V 


<!-- Contingencia -->
Esta clasificación se darán cuando los valores de la columna importante de la tabla son variados y no todos equivalentes, es decir cualquier caso diferente a los anteriores dos.
Ejemplo:
<!--
P       Q       P∨Q      P∨Q → Q          -->
V       V        V          V
V       F        V          F
F       V        V          V
F       F        F          V



↔ Doble Condicional (Si y solo si. Equivalente).
→ Condicional (Entonces)
∧  Conjunción (Y) 
∨ Disyunción (O) 
~ Negación (No)

<!-- SUPER RESÚMEN -->
∧  verdadero cuando se cumplan ambas proposiciones, equivalente al operador && (AND).

∨ false cuando ambas proposiciones sean false. Si una o ambas tienen valor true dará true.

→ falsa cuando su antecedente es verdadero y su consecuente falso.

↔ verdadero cuando ambas proposiciones simples tengan el mismo valor booleano. (Ambas F o ambas V).

<!-- EJERCICIOS -->
(4) a b == V
    c d == F

A. (a ∨ b) ∧ (c ∨ d) 
B. (a ∨ c) ∧ (b ∨ d)
C. (a ∧ c) ∨ (b ∧ d)
D. (a ∨ c) → b              (si a || c entonces b)
E. (a ∧~ c) → c             (si a && != c entonces c)

<!-- Respuestas -->
Para resolver los problemas debemos obtener los valores de verdad en los () y luego el resultado final entre esos valores según el signo que tengan de por medio

1. TRUE ∧ FALSE == FALSE. 
<!-- Da false ya que la conjunción pide que ambas proposiciones tengan un valor de TRUE -->
2. TRUE ∧ TRUE == TRUE.
<!-- Da true ya que se cumplen ambas proposiciones -->
3. FALSE V FALSE == FALSE
<!-- False ya que la disyunción exige que al menos se cumpla una proposición simple. En este caso ninguna se cumple. -->
4. TRUE → TRUE == TRUE
<!-- True ya que la condicional es false cuando su antecedente es T y su consecuente F. No se cumple lo del consecuente. -->
5. TRUE → FALSE == FALSE
<!-- False ya que el antecedente es T y el consecuente es F. -->

(a ∧~ c) 
Por qué esto da true? porque la negación que precede a 'C' provoca que debamos invertir su valor, por negarla.
Entonces ahora ambas proposiciones tienen el valor booleano de TRUE lo que hace que se cumpla la conjunción.




(5)Justificar si la información dada es suficiente para determinar el valor de verdad de la proposición indicada.
<!--Cuando no podamos obtener el valor de una proposición simple, debemos evaluar si con el valor que ya tenemos da la otra nos basta para averiguar el valor booleano de la evaluación que se esta haciendo entre ambas. Haremos esto a lo largo de los ejs, por lo tanto lo veremos con ejemplos. -->

1. (p → q) ∧ r
2. (p ∧ q) → (p ∨ r) 
3. (~p ∧ ~q) ↔ (p ∨ q)
4. (p → q) → r
5. (p → r) ∨ q

<!-- Info necesaria para determinar el valor de las proposiciones. -->
1. v(r → q) = V 
2. v(p) = V
   v(r) = F
3. v(p) = V
4. v(p) = v(r) = F
5. v(p → r) = V

<!-- Resoluciones -->
2. (p ∧ q) → (p ∨ r)
(TRUE ∧ unknow) → (TRUE ∨ FALSE)
     TRUE ∧ unknow  → TRUE
            == TRUE
<!--Precindimos de obtener el valor de q para averiguar el valor final del antecednete de la condicional ya que su consecuente tiene un valor de TRUE, lo que nos asegura un mismo resultado. Esta valor será TRUE.-->

3. (~p ∧ ~q) ↔ (p ∨ q)
    FALSE ∧ unknow ↔ (TRUE ∨ unknow)
          FALSE ↔ TRUE
            == FALSE
<!-- En este caso sucede algo similar al anterior. La conjunción pide que ambas proposiciones sean T para dar T por lo tanto prescindimos de averiguar el valor de q ya que negación p dio false por lo que la primer conjunción dará false si o si.
Con la siguiente evaluación sucede lo mismo, al ya tener un valor de TRUE la disyunción nos dará obligatoriamente true ya que uno se cumple. 
El resultado de la evaluación final (doble condición) da falso ya que para que de true los valores de las proposiciones deben ser equivalentes.-->
 

<!-- SIGNOS y SUPER RESÚMEN -->
∧  verdadero cuando se cumplan ambas proposiciones, equivalente al operador && (AND).
∨ false cuando ambas proposiciones sean false. Si una o ambas tienen valor true dará true.
→ falsa cuando su antecedente es verdadero y su consecuente falso.
↔ verdadero cuando ambas proposiciones simples tengan el mismo valor booleano. (Ambas F o ambas V).

↔ → ∧ ∨ ~






LEYES LÓGICAS 
<!-- Son leyes para reducir código. En los casos que veremos la doble condición significará equivalente. Estas son: -->

Idempotencia
<!-- Esta ley elimina especificaciones rebundantes. Se utiliza en conjunción o disyunción. -->
(p ∧ p) ↔ p
(p ∨ p) ↔ p 
<!-- p o p && p y p es lo mismo que un solo p por lo tanto utilizamos idempotencia para reducir código. -->

Conmutativa
<!-- Esta ley invierte el orden de las proposiciones. Se utiliza en conjunción o disyunción. -->
p ∧ q ↔ q ∧ p
p ∨ q ↔ q ∨ p


Asociativa 
<!-- Esta ley cambia el lugar de los parentesís, es decir modifica la separación en términos. Al usarla no debemos mezclar a los operadores, deben ser los mismos. Se  usa en conjunción o disyunción.  -->
(p ∧ q) ∧ r ↔ p ∧ (q ∧ r)
(p ∨ q) ∨ r ↔ p ∨ (q ∨ r)


Distributiva
<!-- Ejecutaremos la tradicional distributiva, debemos invertir los conectivos. El que estaba dentro del () ahora estará afuera. 
Lo importante a recordar es que el conectivo principal y su proposición serán los que se repetirán en la expresión extensa, en la corta podemos identificarlos porque son los que están fuera del paréntesis. -->
(p ∨ q) ∧ r ↔ (p ∧ r) ∨ (q ∧ r) <!--De la conjunción respecto a la disyunción-->   
(p ∧ q) ∨ r ↔ (p ∨ r) ∧ (q ∨ r) <!--De la disyunción respecto a la conjunción-->


Leyes de Morgan
<!-- Estas leyes niegan disyunciones o conjunciones. Distribuyen la negación que esta fuera del paréntesis, además invierte el conectivo entre disyunción y conjunción como veremos en el ejemplo. Esto se debe al efecto que tiene la negación antes de los paréntesis.  -->
~(p ∨ q) ↔ (~p ∧ ~q)
~(p ∧ q) ↔ (~p ∨ ~q)


Elemento neutro
<!-- Simplificamos una conjunción o disyunción que incluyen valores booleanos, esto solo si coinciden con su conectivo correspondiente. 
La conjunción (∧)(y) debe estar con V y la disyunción (V)(o) debe estar con F -->
p ∧ (V) ↔ p
p V (F) ↔ p 
<!-- En estos casos eliminaremos el conectivo y el valor booleano, ya que son rebundantes. -->
<!-- Un truco es recordar que no se podrán juntar las V en la misma posición, es decir 'V (V)' si pasa esto es parte de la siguiente ley que veremos. -->

Elemento absorvente
<!-- En esta ley simplificamos también conjunciones o disyunciones que incluyen valores booleanos pero con dos diferencias, reducimos al valor booleano en vez de a la proposición.
Además la compatibilidad entre conectivos y valores booleanos es diferente, en este caso la conjunción (∧)(y) debe estar con F y la disyunción (V)(o) debe estar con V.-->
p ∧ (F) ↔ (F)
p V (V) ↔ (V)


Complementación
<!-- En esta ley podemos tener una proposición y su negación o una propoción y su negación. En cada caso tendrán un resultado diferente. 
El conectivo conjunción(∧)(y) da false. 
El de disyunción(V)(o) da true. -->
p ∧ (~p) ↔ (F)
p V (~p) ↔ (V)

Subsunción
<!-- En esta ley la letra fuera de los paréntesis debe estar también dentro, esa es la manera para diferenciarlo de asociativa y distributiva, además de por su equivalencia, que es la misma proposición repetida de la que estabamos hablando. También debe usar si o si conectivos de conjunción y disyunción.-->
(p V q) ∧ p ↔ p
(p ∧ q) V p ↔ p


Equivalencia importante
<!-- Es en la única ley que aparecerá el conectivo condicional y será el utilizado principalmente
Hasta ahora solo habían sido conjunciones y disyunciones. -->
(p → q) ↔ (~p V q)
<!-- En esta ley vemos que tenemos una implicación entre dos proposiciones, esto equivaldrá a la disyunción (V) (o) entre la negación del antecedente (~p) y el consecuente (q) de la implicación anterior. -->
<!-- Ya que es el único que tiene un entonces (conectivo condicional) lo resolveremos apenas lo veamos por ya tenerlo identificado. -->

<img src="Leyes. png">

<!-- Ejercicios -->








LINK SIMULACRO COMPUTACION
https://aulavirtual.instituto.ort.edu.ar/mod/quiz/view.php?id=95156