# Enunciado 

Contar Vocales en una Cadena: Leer una cadena de texto (palabra o frase corta) y contar cuántas vocales contiene. Mostrar el total.

# Analisis

Para este pseudocódigo hice que el texto recorriera letra por letra para detectar las vocales ya definidas antes, si encuentra una vocal este le va sumando 1 al contador y al final nos muestra la cantidad de vocales que había

# Pseudocodigo

Algoritmo ContarVocalesCadena

	Definir frase Como Caracter
	Definir cantidad, i, contador Como Entero
	contador <-0
	
	Escribir "Ingresa una frase"
	Leer frase
	cantidad <- Longitud(frase)
	Para i<-0 Hasta cantidad+1 Hacer
		segun Subcadena(frase, i, i) Hacer
			"a", "e", "i", "o", "u", "A", "E", "I", "O", "U":
				contador<-contador+1
			De Otro Modo:
				Escribir Subcadena(frase, i, i) Sin Saltar
		FinSegun
	FinPara
	Escribir " "
	Escribir "La cantidad de vocales es: ", contador

FinAlgoritmo

# Diagrama de flujo

![Diagrama de flujo - Contar Vocales](../../Diagramas/ContarVocales.png)

[← Volver al README](../../README.md)