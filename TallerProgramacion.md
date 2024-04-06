<!-- Entradas -->
Entrada verde == Sysout.println();
Entrada roja == scanner.nextLine/int()

<!-- Bloques -->
instruccion == cualquier lógica a desarrollar.  Ej: i++; 
variable <- expresion == asignacion de alguna variable 

<!-- Selección -->
condicion v/f == SENTENCIA IF.
variable/valor/valor/default == SENTENCIA SWITCH (variable == var temporal que almacenará los resultados); 

<!-- CICLOS -->
While
Do while == 
FOR == int i <- 0, 10, 1
FOREACH


<!-- JAVA SENTENCIAS -->
<!-- SELECCION -->
<!-- CONDICION -->
    if(numero % 2 == 0) //Si el resto de la división entre el numero y 2 da 0, es par.
		{
			System.out.println("El numero es par");
		}
		else //Si no, es impar.
		{
			System.out.println("El numero es impar");
		}
<!-- SWITCH -->
<!-- TP21 -->
if(numero >= 1 && numero <= 7) 
		{
			switch (numero) {
	            case 1:
	                diaDeLaSemana = "Domingo";
	                System.out.println("El dia de la semana correspondiente al numero seleccionado es: " + diaDeLaSemana);
	                break;
	            case 2:
	                diaDeLaSemana = "Lunes";
	                System.out.println("El dia de la semana correspondiente al numero seleccionado es: " + diaDeLaSemana);
	                break;
	            case 3:
	                diaDeLaSemana = "Martes";
	                System.out.println("El dia de la semana correspondiente al numero seleccionado es: " + diaDeLaSemana);
	                break;
	            case 4:
	                diaDeLaSemana = "Miércoles";
	                System.out.println("El dia de la semana correspondiente al numero seleccionado es: " + diaDeLaSemana);
	                break;
	            case 5:
	                diaDeLaSemana = "Jueves";
	                System.out.println("El dia de la semana correspondiente al numero seleccionado es: " + diaDeLaSemana);
	                break;
	            case 6:
	                diaDeLaSemana = "Viernes";
	                System.out.println("El dia de la semana correspondiente al numero seleccionado es: " + diaDeLaSemana);
	                break;
	            case 7:
	                diaDeLaSemana = "Sábado";
	                System.out.println("El dia de la semana correspondiente al numero seleccionado es: " + diaDeLaSemana);
	                break;
			}
		}
		else 
		{
			System.out.println("Error. Dije entre 1 y 7.");
		}
