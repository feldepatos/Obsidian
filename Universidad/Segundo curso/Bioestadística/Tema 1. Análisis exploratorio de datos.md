# Población y muestra
## Muestreo aleatorio
Definiciones
	Una población
		Es un conjunto de sujetos o elementos que presentan características comunes
	Una variable (atributo)
		Es la características de interés, que puede tomar  diferentes valores  según el individuo
	Una muestra
		Es un subconjunto de *n* individuos de la población para los que se observa  la variable de interés.
Muestreo aleatorio
	Muestra aleatorio simple de *n* elementos es una muestra en la que:
		1. Todos los miembros de la población tienen las misma oportunidades de ser incluidos en las muestras (representatividad)
		2. Los miembros de la muestra se escogen independientemente entre sí(independencia).
	El requisito (2) significa que las oportunidades de que un determinado miembro de la población sea elegido no dependen de que otros miembros de la población son elegidos.
## Error en la extracción de la muestra
Ejemplo: Longitudes de peces
Un biólogo planea estudiar la distribución de la longitud del cuerpo de una
cierta población de peces en la Bahía Chesapeake. La muestra se recoge
utilizando una red de pesca.
*Será entonces más probable que los peces pequeños escapen por los
agujeros de la red. Por tanto, será menos probable recoger peces pequeños
que grandes, por lo que el procedimiento de muestreo está sesgado.*
Ejemplo 2: Sacarosa en raíces de remolacha
Una agrónomo planea muestrear raíces de remolacha en un campo de
cultivo para medir su contenido de sacarosa. Supongamos que toma todos
sus especímenes de una zona pequeña del campo de cultivo seleccionada
aleatoriamente.
*El procedimiento de muestreo no estaría sesgado pero tendería a producir
una muestra demasiado homogénea, debido a que la muestra no reflejaría
las variaciones ambientales y de entorno a lo largo de todo el campo de
cultivo.*

# Tipos de variables
Una variable es una característica de un individuo de la población a la que se le puede asignar un número o una categoría
Tipos:
	Variables cualitativas/Categóricas
	Variables cuantitativas/Numéricas
		Discretas
		Continuas
# Descripción gráfica de variables
## Diagrama de sectores y diagrama de barras
## Histograma y diagrama de cajas→boxplot
# Descripción numérica de una muestra
## Medidas de tendencia central
## Medidas de localización
## Medidas de dispersión
## Medidas de forma
# Descripción de poblaciones mediante modelos probabilísticos
## Sucesos y probabilidad
Definiciones
Un experimento aleatorio
	es un experimento en el que no se puede predecir el resultado exacto de cada realización o prueba.
Una variable aleatoria
	es una características de interés observada en el experimento aleatorio.
El espacio muestral 
	es el conjunto de resultados posibles que puede tomar la variable aleatoria.
Un suceso*E*
	es un subconjunto del espacio muestral cuyos elementos comparten una misma característica.
La probabilidad del suceso E
	es un valor numérico entre 0 y 1 que mide cómo de fácil es que ocurra el suceso *E*.
*Interpretación de la probabilidad como frecuencia: cada vez que se realiza el experimento aleatorio, el suceso E ocurrirá o no. La P(E) se interpreta como la frecuencia relativa de las ocurrencias de E en un número arbitratiamente grande de repeticiones*
*Cuando el espacio muestral es finito y todos sus elementos tienen la misma probabilidad, la probabilidad de cualquier suceso*
## Distribuciones
Bernoulli
Las variables que pueden tomar solo dos valores (categorías) se variables dicotómicas.
*Por ejemplo: Factor Rh{+.-}, sexo{hombre, mujer}*.
Pueden representarse utilizando los valores {0,1}, de manera que:
	X=1 si se cumple la propiedad que interesa→éxito.
	X=0 si no se cumple→fracaso.
Binomial
Supongamos que se realizan *n* repeticiones independientes de un experimento con 2 resultados posibles: éxitos y fracaso. La variable que representa el número de éxitos en las *n* pruebas independientes tiene una distribución Binomial-
$$
X-Bi(n,\pi),donde\ \pi
$$
La distribución Binomial se caracteriza por la siguiente función de probabilidad:
	$$
P(X=k)=\frac{n!}{k!(n-k)!}\pi^{k}(1-\pi)^{n-k},k=0,1,2, n.
$$
La media de X es n pi y la varianza es npi(1-pi)
Normal
Una variable aleatoria continua X tiene una distribución Normal con media ,u y desviación típica σ si la función de densidad es:
$$
 f(x)= \frac{1}{σ \sqrt{ 2\pi }}*e ^{-1/2(x-\mu/σ)^{2}},-\infty<\infty, X-N(\mu,σ).
$$
![[Pasted image 20250214174157.png]]
## Teorema Central del Límite
La media muestral x se puede usar, no solo como la descripción de los datos de la muestra, sino también como un estimador de la media poblacional mu.
¿Cuánto de cerca está x de mu?
*No podemos responder a esta pregunta para la media x de una muestra cocnreta, pero podemos responder si pensamos en términos del modelo de muestreo aleatorio y vemos la media muestral como una variable aleatoria X*.
¿Cuánto de cerca está *X* de mu?
Definiciones
	Media
		La media de las medias muestrales tiende a la media poblacional
	Desviación típica
		La desviación típica de la distribución en el muestreo de de *X* tiende a la desviación típica poblacional dividida por la raíz cuadrada del tamaño de la muestra.
	Forma
		Si la distribución poblacional de *X* es normal, entonces la distribución en el muestreo de X es normal, independientemente del tamaño de la muestra *n*.
		Teorema Central del límite:
			Si *n* es  grande, entonces la distribución en el muestreo de *X* es aproximadamente normal, incluso aunque la distribución de la muestra *n*
Consecuencia del teorema central del límite:
	Si el tamaño de la muestra *n* es grande, la media muestral se comporta como si procediese de una distribución Normal, con la misma media que la población pero con varianza dividida por n. 

# Resumen
El análisis exploratorio de los datos es el  primer paso de todo análisis estadístico, pues nos permite resumir la información obtenida.
Debemos tener en cuenta si la variable o variables de interés son categóricas o  numéricas, pues el  tipo de variable afecta la forma de resumir/ describir los datos observados a partir de la muestra.
Podemos dar información mediante gráficas y diagramas, pero también mediante estadísticos de tendencia central, de localización, de dispersión.
Tenemos herramienta informáticas muy útiles que nos proporcionan la información necesaria (gráficas y numérica) de manera fácil y segura. En particular, utilizaremos el programa R bajo su interfaz.