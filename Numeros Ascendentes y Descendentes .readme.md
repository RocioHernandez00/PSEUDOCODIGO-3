### Numeros Ascendentes y Descendentes 

* Algoritmo NumerosAscendentesyDescendentes
	Imprimir "ingrese un numero"
	leer numero
	Imprimir  "Operaciones Disponibles: "
	Imprimir "1.Imprimir en orden Ascendente"
	Imprimir "2.imprimir en orden Descendente"
	Imprimir "ingrese operacion a ejecutar"
	leer operacion 
	
	segun op Hacer
		1:
			Para iterador <- 0 Hasta numero Con Paso 1 Hacer
				Imprimir ConvertirATexto(iterador)
			Fin Para
		2:
			Para iterador <- numero Hasta 0 Con Paso -1 Hacer
				Imprimir ConvertirATexto(iterador)
			Fin Para
		De Otro Modo:
			Imprimir 'Opcion incorrecta!'

		
	FinSegun
	
	
FinAlgoritmo
