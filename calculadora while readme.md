Algoritmo CalculadoraSimpleWhile
	Imprimir "Calculadora Simple"
	Imprimir "ingrese primer numero"
	leer primerNumero
	Imprimir "ingrese segundo numero"
	leer segundoNumero
	Imprimir "ingrese una operacio: +,-,*,/' 
	leer op
	Si op == '+' | op == '-' | op == '*' | op == '/' Entonces
		
		Imprimir 'Procesando: ' + ConvertirATexto(primerNumero) + ' ' + op + ' ' + ConvertirATexto(segundoNumero)
		segun op Hacer
			'+' : Imprimir  'Resultado: ' + ConvertirATexto(primerNumero + segundoNumero)
			'-' : imprimir  'Resultado: ' + ConvertirATexto(primerNumero - segundoNumero)
			'*' : Imprimir  'Resultado: ' + ConvertirATexto(primerNumero * segundoNumero)
			'/' : Imprimir  'Resultado: ' + ConvertirATexto(primerNumero / segundoNumero)
				
		FinSegun
		
	SiNo
		Imprimir ' la operacion no es valida'
	FinSi
	
	Imprimir 'Desea continuar con otra operacion? si/no'
	Leer continuar
Hasta Que continuar == 'No' | continuar == 'no'
FinAlgoritmo
