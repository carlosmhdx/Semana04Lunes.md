# Semana04Lunes.md
Semana 04 - Día Lunes - 12/12/2022

# Promedio de ventas y comisiones

Algoritmo VentaComision
	
	Imprimir " Por favor introduzca la cantidad de ventas: "
	Leer CanVentas
	
	Para i<- 1 Hasta CanVentas Con Paso 1 Hacer
		
		Imprimir " Introduzca el monto de la venta ", i
		Leer MonVentas
		TotVentas = TotVentas + MonVentas
				
	FinPara
	
	Imprimir " El promedio de ventas es: ", TotVentas/CanVentas
	
	Si CanVentas <= 5 Entonces
		
		Imprimir " La comisión sobre las ventas es de: ", (TotVentas * 10) / 100
		
	FinSi
	
	Si CanVentas > 5 Entonces
		
		Imprimir " La comisión sobre las ventas es de: ", (TotVentas * 15) / 100
		
	FinSi
	
FinAlgoritmo

# Par o Impar

Algoritmo ParoImpar
	
	Repetir 
		
		Imprimir " Introduzca un número entre 1 y 50 "
		Leer Num
		
	Hasta Que Num <= 50 Y Num >= 1
	
	Resto <- Num % 2
	
	Si Resto = 0 Entonces
		
		X = 2
		
	SiNo
		
		X = 1
		
	FinSi
		
	Para i <- X Hasta Num Con Paso 2 Hacer
		
		Imprimir X
		X = X + 2
		
	FinPara
	
FinAlgoritmo
