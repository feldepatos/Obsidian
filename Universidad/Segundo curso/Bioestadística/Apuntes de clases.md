# Tema 1. Análisis exploratorio de datos
población
	estudiar ciertas características→variables 
		pueden tomar diferentes  valores en función del individuo, nos referimos a un elemento  de la población
			ej. diámetro del árbol.
		En  la vida  real no puede acceder a toda la población, por tanto, seleccionamos una muestra→m(tamaño muestral)
Muestreo aleatorio+propiedades que presenta esa muestra para que sea representativa de la población
La necesidad de una buena muestra nos permite inferir sobre la población.
Otra cosa, donde hacer énfasis son los diferentes métodos para obtener la muestra 
	prácticamente será a nivel teórico una muestra aleatoria, se aceptan ciertos sesgos en los resultados
![[Pasted image 20250128122633.png]]

30-1-25
Ejemplos de la diapositiva 9
	1. Objetivo→ variable de interés es la diferenciación de Tº
	2. población→adultos con síntomas gripales
	3. muestra→adultos con síntomas gripales antes y después de la toma del medicamento

| Ejemplos  | 1                                                                        | 2   | 3   | 4   | 5   |
| --------- | ------------------------------------------------------------------------ | --- | --- | --- | --- |
| Objetivo  | variable de interés es la diferenciación de Tº                           |     |     |     |     |
| Población | adultos con síntomas gripales                                            |     |     |     |     |
| Muestra   | adultos con síntomas gripales antes y después de la toma del medicamento |     |     |     |     |
**Error en la extracción de la muestra**
Ejemplo de longitud de peces
hay que identificar ciertos sesgos que condicionen la media de la muestra→entonces presentaremos un error, hay que saber cuantificarlos
Sacarosa en raíces de remolacha
hay que elegir plantas de diferentes zona de nuestra área 
A realizar :
	![[Pasted image 20250130114521.png]]
	para comprender el muestro y como arreglar el problema que identifiquemos
## Tipos de variables
¿Qué es una variable?
	Una variable es una característica de un individuo de la población a la que
	se le puede asignar un número o una categoría.
Ejemplos
	Grupo sanguíneo: A, B, AB, O
	Número de hijos: 0,1,2,3,. . .
	Sexo: M, F
	Nivel de estudios: sin certificar, elemental, medio, superior
	Glucosa en sangre basal: [70,400]
Tipos:
1. Categóricas
2. Numéricas
	1. Discretas→sólo un número finito de posibles valores
		1. Nº enteros
	2. Continuas
## Descripción gráfica de variables

| Tipos de variables | Formas                                              |
| ------------------ | --------------------------------------------------- |
| Categóricas        | Tabla de frecuencias, diagrama de sectores y barras |
| Numérica discretas | Tabla de frecuencias, diagrama de barras            |
| Numérica continuas | Histograma de cajas                                 |
### Tabla de frecuencias
contamos el nº de veces que aparece  esa categoría=frecuencia absoluta
$$
f_{i}=\frac{n_{i}}{n}  
$$
$$
n_{i}=es\ el\ nº de\ repetición\ de\ n\ ; frecuencia\ relativa
$$
### Diagrama de sectores

### Diagrama de barras
las categorías están puestas en el eje x
Además es muy fácil compararlas
Variables cuantitativas discretas
Características
- El **orden está presente** y debe verse en la gráfica.
- En caso de tener un gran nº de categorías podemos tratarlas como si fueran contínuas.
Ejemplo→proteína en leche de vaca
podemos hacer frecuencias agrupadas porque si lo hacemos individual es más engorroso y no proporciona información
como calcular la amplitud resta del máximo y el mínimo/ N
$$
amplitud=\frac{máximo-mínimo}{N}
$$
![[Pasted image 20250130120906.png]]
	Muestra frecuencia absoluta
	para cada intervalo levantemos una barca
	a diferencia del barra, carece de espacio en cada barra
		esto representa la continuidad→histograma
			![[Pasted image 20250130121126.png]]
¿Cuántos intervalos escojo?
	las frecuencias relativas, entonces si elegimos pocos intervalos
		que apenas se ven algún dato
		![[Pasted image 20250130121251.png]]
		Muchos intervalos
			![[Pasted image 20250130121217.png]]
				los huecos blancos representas intervalos sin individuos que cumplan esas condiciones
## Descripción numérica de una muestra
Media muestral:
	es la observada por nosotros
	es una dependencia central, nos proporciona un valor por donde giran la media.
	$$
\bar{x}=Media\ muestral
$$
$$
\mu=media\ poblacional
$$
Media poblacional→nosotros la estimados, porque su valor real nunca lo conoceremos
$$
x_{n}=tamaño\ muestral 
$$
Mediana→el valor que ocupa  la posición central en la muestra ordenada
si el tamaño muestral  es impar, es el valor de n+1/2
pero si es par→n/2 y n/2+1
Moda
	el valor más frecuente de la muestra
Diferencias entre la media y mediana
media→construir intervalos de confianza...
problema →es sensible a valores extremos
la mediana no cambia, se puede calcular una **mediana cortada**.
MEDIDAS DE LOCALIZACIÓN
quartiles
50% de los valores centrales→IQR→te da la amplitud
alpha→vamos a generalizar el concepto del quartil, es para diferentes quartil del 25 o 50.

6-2-25
## Sucesos y probabilidad

Teorema central del límite
es el mejor estimador de la media poblacional de μ
	variable aleatoria
		la solemos dotar  como x
	la media poblacional→X(variable aleatoria)
		presenta una distribución común es del tipo normal
		tendrá una desviación típica+media+forma
			su desviación será más ↓ respecto 
n>30→podemos establecer el  teorema del límite central
act→2,3,4,7,8

# Tema 2.Población y muestra
6-2-6
Parámetros de la población+desviación típica
$$
\sigma→ desviación\ típica \ poblacional  
$$

13-2-25
Tipos de hipótesis
	bilateral
		= siempre esta en la nula
- $$
H_{0} :\emptyset = \emptyset_{0}
$$
	unilateral
		necesitamos otro concepto más
			p valor
				para resolver el contraste
				1. test estadístico
					1. hay que verificar si los datos son  compatibles  de la hipótesis 
						1. lo es→acepta 
			ts  mide la distancia del valor  de la muestra
			n-1→t
El p-valor
	¿cómo  calcularlo?
		se representa la t student
	es la suma de las áreas en un contraste de **hipótesis bilateral**
	en el caso de una **hipótesis unilateral** solo será **una cola**
	es una probabilidad esta [0-1]
		cercano a 1, está cerca de la parte central
		<0, está en una de las colas→los datos son incompatibles
- $$
p\ valor\ < \alpha \rightarrow rechazamos
$$
$$
p \ valor \geqq \alpha \rightarrow No \ rechazamos \ H_{0}
$$
Solo controlaremos el error tipo 1
Esquema del contraste de hipótesis
	1. Establecer el nivel de significación alpha
		1. para evitar cualquier error con el p-valor
	2. Especificar las hipótesis del contraste
		1. segun el tipo  de estudio
	3. Calcular el valor del test
		1. a partir de aquí intervienen los datos
		2. observar si los datos son compatibles con la hipótesis establecida
	4. Calcular p-valor
	5. decidimos si rechazamos la hipótesis nula
	6. Presentar las conclusiones del contraste

![[Pasted image 20250213121417.png]]
	el p-valor<< del alpha→rechazo de la hipótesis nula
		existe suficiente evidencia a  favor de la hipótesis alternativa
		- 4 no  pertenece al intervalo  de confianza mu
20-2-25
Ejercicios
Problema 1.

# Tema 3.Inferencia de 2 muestras
 

# Tema 4. Análisis de *k* muestras independientes
# Tema 5. Análisis de datos categóricos
# Tema 6.Regresión lineal
