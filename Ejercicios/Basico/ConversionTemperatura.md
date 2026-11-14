# Enunciado 

Conversión de Temperatura: Leer una temperatura en grados Celsius y convertirla a grados Fahrenheit. Mostrar el resultado.

# Analisis

Usando la fórmula de °F = °C * 1.8+32 definí ambos como variables, una contiene el dato de 1.8 y la otra el de 32, cuando se escribe el número de grado celsius este suma ambos datos y los multiplica de acuerdo al número de grado celsius

# Pseudocodigo

Algoritmo ConversionTemperatura

	Definir variable1 Como Real
	Definir varianle2 Como Real
	Definir celsius Como Real
	Definir respuesta Como Real
	
	variable1 <- 1.8
	varianle2 <- 32
	
	Escribir "Ingresa los grados celsius"
	Leer celsius
	respuesta <- celsius *variable1 + varianle2
	Escribir "La conversion de celsius a fahrenheit es: ", respuesta
	
FinAlgoritmo

# Diagrama de flujo

![Diagrama de flujo - Conversión de Temperatura](../../Diagramas/ConversionTemperatura.png)

[← Volver al README](../../README.md)