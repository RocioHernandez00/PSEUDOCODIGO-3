### Calculadora Simple Switch
``` pcs Algoritmo CalculadoraSimpleswitch
	Imprimir 'Ingrese primer numero'
	Leer n1
	Imprimir 'Ingrese segundo numero'
	leer n2
	imprimir 'Ingrese una operacion: +,-,*,/ '
	leer op 
	si op == '+' | op == '-' | op == '*' | op == '/' Entonces
		imprimir 'procesando: ' + ConvertirATexto(n1) + ' ' + op + ' ' + ConvertirATexto(n2)
		segun op Hacer
			'+': 
				Imprimir ' Resultado: ' + ConvertirATexto(n1 + n2)
			'-':
				Imprimir ' Resultado: ' + ConvertirATexto(n1 - n2)
			'*':
				Imprimir ' Resultado: ' + ConvertirATexto(n1 * n2)
			'/': 
				Imprimir ' Resultado: ' + ConvertirATexto(n1 / n2)
				
		FinSegun
	SiNo
		Imprimir 'la operacion no es valida'
	FinSi
	
	
FinAlgoritmo
