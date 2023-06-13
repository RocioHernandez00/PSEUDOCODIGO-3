### Calculadora simple 

``` pcs Algoritmo CalculadoraSimple
	Imprimir "Calculadora Simple"
	Escribir "¿Que operacion deseas realizar? (Suma,Resta,Multiplicacion, Divisio) "
	leer operacion 
	
	Escribir  "Ingrese primer Numero"
	leer PrimerNumero
	
	Escribir "Ingrese segundo Numero"
	leer SegundoNumero
	
	segun operacion Hacer
		"Suma": 
			Escribir PrimerNumero + SegundoNumero
		"Resta": 
			Escribir PrimerNumero - SegundoNumero
		"Multiplicacion":
			Escribir PrimerNumero * SegundoNumero
		"Division": 
		Escribir PrimerNumero / SegundoNumero
	De Otro Modo:
		Escribir operacion no valida 
		
	FinSegun
