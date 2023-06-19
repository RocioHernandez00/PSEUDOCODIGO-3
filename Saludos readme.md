### saludos 

``` psc Algoritmo saludos
	Imprimir "///SALUDOS///"
	Definir continuar Como Caracter
	continuar = "si"
	Mientras continuar = "si" Hacer
		Imprimir "ingrese la hora actual (0-23):"
		leer hora
		si hora <= 12 Entonces
			Imprimir " buenos dias"
		SiNo
			si hora <= 18 Entonces
				Imprimir "buenas tardes"
			SiNo
				Imprimir "buenas noches"
			FinSi
		FinSi
		Imprimir " desea continuar? si/no"
		leer continuar
	
	FinMientras
	
FinAlgoritmo
	
			
	
	
FinAlgoritmo

