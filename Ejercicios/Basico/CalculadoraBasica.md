# Enunciado

Calculadora Básica: Leer dos números enteros y una opción (1: Suma, 2: Resta, 3: Multiplicación, 4: División). Realizar la operación correspondiente y mostrar el resultado. Validar que no se divida por cero.

# Analisis

En este algoritmo hice que se lean 2 números y después se muestre un menú con cuatro opciones, suma, resta, multiplicación y división, de acuerdo a la opción elegida se ejecuta la operación y la muestra en la pantalla

# Pseudocodigo

Algoritmo CalculadoraBasica

	Definir nume1, nume2 Como Real
	Definir opcio Como Entero
	Definir resultado Como Real
	
	nume1 <- 0
	nume2 <- 0
	resultado <- 0
	opcio <- 0
	
	Escribir "Ingresa 2 números: "; leer nume1; leer nume2
	Escribir "1-Suma"
	Escribir "2-Resta"
	Escribir "3-Dividir"
	Escribir "4-Multiplicar"
	Leer opcio
	
	Segun opcio Hacer
		1:
			resultado <- nume1 + nume2
		2:
			resultado <- nume1 - nume2
		3:
			resultado <- nume1 / nume2
		4: 
			resultado <- nume1 * nume2
		De Otro Modo:
			Escribir "Error"
	FinSegun
	Escribir "El resultado de la operacion es: ", resultado
	
FinAlgoritmo

# Diagrama de flujo

![Diagrama de flujo - Calculadora Básica](../../Diagramas/CalculadoraBasica.png)

[← Volver al README](../../README.md)