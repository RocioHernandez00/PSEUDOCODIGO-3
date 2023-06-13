### Tablas de Multiplicacion con Bucle For

``` psc Algoritmo TablasdeMultiplicacionBucleFor
	Imprimir "///Tablas de Multiplicacion///"
	Imprimir "Ingrese la tabla a calcular"
	leer Tabla
	Para iterador <- 1 Hasta 10 Con Paso 1 Hacer
		Imprimir ConvertirATexto(tabla) ' *  ' + ConvertirATexto(iterador) + ' = ' ConvertirATexto(tabla * iterador)
	Fin Para
FinAlgoritmo
