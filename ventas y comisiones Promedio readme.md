 ``` pcs Algoritmo ventasyComicionesPromedio
	Escribir "escribe el numero total de ventas a ingresar"
	leer cantidadDeVentas
	IngresoTotal = 0
	para ventas =1 hasta cantidadDeVentas Con Paso 1 Hacer
		escribir "escribe el valor de la venta: ", cantidad
		Leer cantidad
		IngresoTotal = IngresoTotal + cantidad
	FinPara
	promedio = IngresoTotal / cantidadDeVentas
	Imprimir "la venta promedio es: ", promedio
	
	si cantidadDeVentas  < 5 Entonces
		imprimir "la comision recibida por el vendedor es: ", IngresoTotal * 0.10
	SiNo
		Imprimir " la comision recibida por el vendedor es. ", IngresoTotal  * 0.15
	FinSi
	
	
	
	
	
	
FinAlgoritmo
