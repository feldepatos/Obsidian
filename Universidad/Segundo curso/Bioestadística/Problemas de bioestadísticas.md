Diapositiva 9
Para cada una de las siguientes, describe el objetivo del estudio
Problema 1.
1. identificar los elementos
	1. población→ ratas
	2. Muestra→12  ratas envenedas
	3. tamaño muestral→12
	4. variable→el  tiempo recuperación del nervio
2. Método diferencial
	1. prueba paramétrica o no→comprobar la normalidad
	2. Condición
		1. por diseño del problema suponemos independencia, que la elección de las ratas es independiente.
			1. se cumple la condición de normalidad →test's T→paramétrico
			2. No paramétrico→de cumplir el método de Wilcpxon
	3. ¿Cómo hacerlo?
		1. es menor de 30→hay que aplicar el test Shapiro-Wilk
			1. hay que escribir sus hipótesis
				1. Normalidad
					1. no provienen de una que proviene de una distribucion normal
				2. NO normalidad→es la opuesta
			2. Para realizar un contraste entre ambas hipótesis necesitamos un p-valor 
				1. p-valor=0.6418
			3. Hay que compararlo con el valor alpha 
				1. NO podemos rechazar la hipótesis nula pq el p-valor>alpha
			4. Podemos poner parámetros →test t
3. Plantea y resuelve el contraste de hipótesis correspondiente
	1. Plantear hipótesis
		1. ↓ del tiempo de recuperación
		2. $$
H_{0}:X \le 13
$$
		**nosotros trabajamos con la población no con la variable pero sí con el parámetro**
			$$
H_{0}\mu \le 13
$$
$$
H_{A}:\mu>13
$$
			necesitamos un p-valor
				la alternativa al contraste es el "greater" y el valor de prueba es 1'3+nivel de confianza 0.95+
				tiene un valor de 0.001984
			Rechazamos la hipótesis nula→aceptamos la otra
				de media el valor de recuparación es mayor que 1'5
	1. Explica las conclusiones  del análisis
	2. un intervalo de confianza del envenamiento de las ratas
		1. estimación
		2. ![[Pasted image 20250220121116.png]]
			1. es una cuota 
		3. Ic_95(mu)=(1'43,1'72)→el tiempo de recuperación de las ratas es () con un intervalo  de confianza .
			1. para resolver contrastes bilaterales, no unilaterales
			2. se puede dar el caso estar cerca del 1'3 y rechazar la hipótesis.
	3. p-valor de la gráfica 3 es la mitad del segundo porque solo nos interesa un valor.
1. se trabaja con la mediana>0 o es menor o igual→nula
A hacer 4,5,6 ,2,3

C→función bino.test
p→solo lo pondriamos→si a mi me preguntan resuelve el siguien contraste es igual que la $$
\mu
$$
