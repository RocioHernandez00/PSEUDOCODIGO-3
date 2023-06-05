### Opciones/Multiples
* Algoritmo OpcionesMultiples 
	Imprimir "opcion 1. Suma de dos numeros"
	Imprimir "opcion 2. Dia de la semana"
	imprimir "opcion 3. Longitud de un texto"
	imprimir "Ingrese la opcion: "
	leer op
	Segun op Hacer
		1:
			Imprimir "opcion 1. Suma"
			Imprimir "Ingrese el primer numero: "
			leer n1
			Imprimir "Ingrese el segundo numero: "
			leer n2
			Imprimir "Resultado: " ConvertirATexto(n1 + n2)
		2:
			Imprimir "opcion 2. Dia de la semana"
			imprimir "Ingrese el Dia de la semana (1-7)"
			leer dia 
			Segun dia Hacer
				1:
					imprimir "Lunes"
				2:
					Imprimir "Martes"
				3:
					Imprimir "Miercoles"
				4:
					Imprimir "Jueves"
				5:
					Imprimir "Viernes"
				6: 
					Imprimir "Sabado"
				7: 
					Imprimir "Domingo"
					
				De Otro Modo:
					Imprimir "El dia ingresado es incorrecto"
					
			Fin Segun
		3:  
			Imprimir "opcion 3. longitud de un texto"
			Imprimir "Ingrese un texto"
			leer cadena
			Imprimir "Longitud de un texto: " + ConvertirATexto(Longitud(cadena))
			
		De Otro Modo:
			imprimir "la opcion es incorrecta"
	Fin Segun
	
	
	
FinAlgoritmo
