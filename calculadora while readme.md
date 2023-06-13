### calculadora Simple While

´´´´ psc Algoritmo CalculadoraSimpleWhile
	Imprimir "Calculadora Simple"
	Repetir
	Imprimir "ingrese primer numero"
	leer primerNumero
	Imprimir "ingrese segundo numero"
	leer segundoNumero
	Imprimir "ingrese una operacion: +,-,*,/' 
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
	Imprimir 'Deseas continuar con otra operacion ? Si / No'
	Leer continuar
Hasta Que continuar == 'No' | continuar == 'no'
