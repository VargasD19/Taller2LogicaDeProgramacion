# Enunciado 

Suma de Números Pares: Leer un número entero N y calcular la suma de todos los números pares comprendidos entre 1 y N. Mostrar el resultado.

# Analisis

Para este código hice que recorriera del 1 al N y usando un MOD 2 este revisa si cada número es par. Si lo es, lo suma a una variable que empieza en 0, y al final muestro el total.

# Pseudocodigo

Algoritmo SumNumPares

	Definir numer Como Entero
	Definir i Como Entero
	Definir suma Como Entero
	
	Escribir "Ingresa un número entero"
	Leer numer
	suma <- 0
	Para i <- 1 Hasta numer Con Paso 1 Hacer
		Si i MOD 2 = 0 Entonces
			suma <- suma + i
		FinSi
	FinPara
	Escribir "La suma es " suma
	
FinAlgoritmo

# Diagrama de flujo

![Diagrama de flujo - Suma de Números Pares](../../Diagramas/SumaNumPares.png)

[← Volver al README](../../README.md)