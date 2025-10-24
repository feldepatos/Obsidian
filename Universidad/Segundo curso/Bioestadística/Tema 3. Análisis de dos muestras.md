# Muestras relacionadas
## Análisis estadístico de dos muestras

En el tema anterior hemos considerado el análisis de una muestras de datos numéricos para hacer inferencia sobre la media de la población a la que pertenece la muestra.
En muchas situaciones prácticas, la investigación requiere la comparación de  dos o más  muestras obtenidas  de la misma o diferentes poblaciones.
En este tema introducidemos métodos para el análisis y la comparación de dos medias poblacionales:
- Muestras relacionadas/emparejadas
	- Cada individuo/unidad observacional de la segunda muestra corresponde a un individuo de la primera. Por tanto, el tamaño de las dos muestras es el mismo y tenemos un conjunto de parejas de datos.
- Muestras independientes:
	- Los individuos o unidades observacionales de una muestra no tienen ninguna relación específica con los de la otra muestra. Además, el tamaño de ambas muestras puede ser diferente.
## Diseño de experimentos con obsevaciones relacionadas
cuando hay una clara relación entre las  2 muestres puede ser el mismo individuos, lo más común→le realizamos 2 mediciones  antes y el después.
el tamaño de la muestra es el mismo
Se  observará como un parejas de datos→en comparación las independientes 

En un diseño emparejado los datos se presentan por parejas, por tanto, las dos muestras tienen el mismo tamaño: *n*.
Las unidades observacionales de cada pareja de datos(x1,x2) están relacionadas entre sí de alguna forma, es decir, tienen en común alguna relación que no tienen con los miembros de otras parejas.
Dentro de cada muestra los individuos son independientes.

**Definición**
Puesto que las medidas se toman sobre el mismo individuo/unidad observacional, podemos definir la variable X_d=X1-X2. Esta nueva variable es la diferencia entre las dos variables originales.
Se puede demostrar que mud=mu1-mu2, donde mu es la media de Xd.
$$
\text{El estudio de} \ \mu_{1}-\mu_{2} \ \text{es equivalente al estudio de} \ \mu d.
$$
### Métodos  paramétricos vs no paramétricos
1. Métodos paramétricos
	- Calcular los intervalos de confianza para la diferencia de medias poblacionales mu1-mu2.
	- Resolver contrastres de hipótesis para la igualdad de medias poblacionales mu1=mu2.
2. Métodos no paramétricos
	- Son una alternativa a los métodos paramétricos cuando estos no puede utilizarse, y nos permiten:
		- Resolver contrastes de hipótesis para la igualdad de las dos distribuciones mediante el test de Wilcoxon.

### Aplicabilidad de los métodos paramétricos
La potencia de las pruebas paramétricas es siempre mayor a la de las pruebas no paramétricas, por lo cual los métodos paramétricos son preferibles.
**Condiciones de validez del análisis basado en la distribución t de Student**
-  Si el tamaño de las muestras es pequeño, hemos de exigir que la distribución de la variable Xd=X1-X2 sea Normal.
- SI el tamaño de las muestras es grande (n>=30), la distribución de la variable Xd no necesita ser normal, porque lo asumimos para su media muestral en virtud del teorema central del límite.
### Ejemplos
el formato de los datos→antes y después para cada individuo
no se observa en conjunto sino de manera individual
se trabajará con lamedia →nuestra muestra de 12 individuos que para cada uno se calculatodoslos datos pero queremos concluir sobre las mu 1, mu2 

| LD  | Antes | Después |
| --- | ----- | ------- |
| 1   |       |         |
| 2   |       |         |
| 3   |       |         |
| 4   |       |         |
| 12  |       |         |
|     |       |         |
media+desviación+tamaño  muestral para construir un intervalo de confianza
Cafeína
tener el mismo  tamaño muestral=estén relacionadas
dentro de cada muestra los individuos son independientes
¿Cómo trabajamos?
se define la variable diferencial
$$
X_{d}=x_{1}-x_{2}
$$
es la  diferencia entre  las dos variables→esmuy importante pero se puede demostrar 
$$
\mu_{d}=\mu_{1}-\mu_{2}
$$
en vez de tener que estudiar 2 parámetros pasamos a  que sea uno

$$
\mu_{1}=\mu_{2}\iff \mu_{1}-\mu_{2}=0\iff \mu_{d}=0
$$
Aplicabilidad de los métodos paramétricos
tamaño muestral grande  
$$
\bar{X}_{d}-N\left( \mu_{d},\left( \frac{\sigma_{D}}{\sqrt{ n }} \right) \right)
$$

variable aleatoria vs e lparámetro
hacer la diapostiva 14→representaciones 
Cafeína
	
## Intervalo de confianza
### Intervalo de confianza para la diferencia de dos medias poblacionales
Para hacer inferencias sobre la media mu_d=mu1-mu2 a partir de dos muestras relacionadas utilizaremos la muestra de las diferencias. Es decir, trabajaremos con una única muestra.
**Definición**
El  intervalo de confianza, con una confianza del 100(1-alpha)%, para la diferencia de medias poblacionales es:

donde x_d, es la media muesrtal de las diferencias, n es el número de diferencias, s_d es la desviación típica muestral de las diferencias, alpha es el nivel de significación y t_1-alpha/2 es el percentil de orden 1-alpha/2 de una t de Student con n-1 grados de libertad.

![[Pasted image 20250601190427.png]]
El intervalo anterior nos indica que el nivel medio de glucosa en sangre después de tomar una pieza de fruta es mayor que el nivel medio de glucosa en sangre antes. La diferencia de niveles medios está entre 21.45 y 67.72 mg/dl, con una confianza del 95%.
## Test t para la comparación de 2 medias poblacionales→carecen de relación alguna
**Definición**
El contraste para la comparación de dos medias poblacionales emparejadas se define de la siguiente manera
![[Pasted image 20250601190705.png]]

El estadístico de contraste utilizado para resolver el contraste utilizado para resolver el contraste de hipótesis es t_s- SI H0 es cierta, ts tiene una distribución T de Student con n-1 grados de libertad.
Criterio de decisión: rechazar la H0 si el p-valor<alpha.

## Alternativas no paramétrica
### Test de los rangos con signo de Wilcoxon
Si no se cumplen las condiciones de validez de los métodos basados en la t de Student, hemos de aplicar un test no paramétrico para muestras relacionadas: el test de rangos con signo de Wilcoxon, que nos permite comprobar si hay diferentes entre las distribuciones poblacionales correspondientes a las dos muestras relacionadas.

Podemos contrastar que:
$$
\begin{align}
H_{0}: \text{La distribución de las variables continuas} X_{1} \ y\  X_{2} \  \text{es la misma}. \\
H_{A}: \text{La distribución de las variables  continuas} X_{1} \ y \ X_{2}\   \text{NO es la misma}.
\end{align}
$$
###  Intervalo de confianza mediante el test de Wilcoxon para la mediana de la diferencia
Para calcular el intervalo de confianza es necesario utilizar una HA bilateral y añadir a la instrucción generado la opción conf.int=TRUE.
Para un nivel de confianza de 95%, la mediana poblacional de la diferencia esperamos que sea positiva y que sus valores estén entre 0.00 y 1.67

--- 
# Muestras independientes

## Diseño de experimentos con observaciones independientes

¿Entre qué valores, y con una confianza alta, estará la diferencia de medias poblacionales?
$$
\text{Estudiamos el intervalo de confianza para} \ \mu_{1}-\mu_{2}
$$
¿Son los datos compatibles con la hipótesis de que las medias poblacionales son iguales?
$$
\text{Planteamos un contraste de hipótesis para} \ \mu_{1}=\mu_{2}
$$
En un diseño de experimento con observaciones independientes:
- Las observaciones de cada muestra han  de ser independientes entre sí.
- Las dos muestras han de ser independientes una con respecto a la otra. Es decir, las unidades observacionales que forman la primera muestra no tienen ninguna relación con las unidades observacionales de la segunda muestra.
Por tanto, el tamaño de las muestras, *n1, n2* , puede ser distinto.
Además, si se quieren aplicar métodos paramétricos, hará falta que *n1 y n2* sean suficientemente grandes o comprobar la normalidad de la variable de interés en ambas poblaciones.

**Métodos paramétricos vs no paramétricos**
Los métodos paramétricos (basados en la distribución t de student) nos permiten dar respuesta a las preguntas anteriores.
- Calcular intervalos de confianza para la diferencia de medias.
- Contrastar hipótesis sobre la igualdad de las dos medias poblacionales.

| Condiciones de validez del análisis basado en la distribución t de student                                                                                                                                            |
| --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| - Si el tamaño de las dos muestras es pequeño, la distribución poblacional de la variableX ha de ser Nomal en las dos poblacionales.                                                                                  |
| - Si el tamaño de las muestras es suficientemente grande, la distribución de la variable es suficientemente grande, la distribución  de la variable en cada población no es necesita ser Nomal (aplicación del  TCL). |

Cuando los métodos paramétricos no sean válidos, utilizaremos métodos no paramétricos: test de Wilcoxon para muestras independientes, que nos permitirán resolver contrastes de hipótesis para la igualdad de las  dos distribuciones.

### Errores estándar(SE) para la diferencia de dos medias muestrales
La diferencia entre las medias muestrales, es una estimación puntual de la diferencia  de las medias poblacionales.
Esta estimación está sujeta a  error, el  error estándar, que nos indica la precisión de la estimación. Este error dependerá de la variabilidad en las poblacionales y del tamaño de las dos muestras.
La  estimación del error estándar a partir de los datos de las dos muestras  independientes depende de las varianzas poblacionales.
- SI las varianzas son iguales: método combinado
- Si las varianzas son distintas: métodos no combinado.
Por otra parte el intervalo de confianza para la diferencia de  las medias poblacionales, nos indicará  de una forma más sencilla cuál es la precisión de la estimación.

**Definición**
Definamos el error estándar para la diferencia de dos medias muestrales para muestras independientes como
![[Pasted image 20250601180617.png]]
- Si con sigma1=! debemos usar s1 para estimar sigma1 y s2 para estimar sigma1(método no combinado).
- Si sigma1  =sigma 2 entonces puede usarse s_c como estimador de ambas desviaciones típicas sigma 1 y sigma 2(método combinado).

¿Cómo podemos saber si las varianzas son iguales?
Para saber si las varianzas poblacionales son iguales o no  utilizaremos el test de levene:
$$
\begin{align}
H_{0}:  \text{Las varianzas de las dos poblaciones son iguales} \ (\sigma_{1}=\sigma_{2}) \\
H_{A}: \text{Las varianzas de las dos poblaciones son diferentes} \ (\sigma_{1} \neq \sigma_{2})
\end{align}
$$
$$
\begin{align}
\text{Si p-valor}<\alpha(=0.05)→\text{Rechazamos la igualdad de varianzas}(H_{0}) \\
\text{Si p-valor}\geq \alpha→\text{No rechazamos la igualdad de varianzas}(H_{0}.)
\end{align}
$$


## Intervalo de confianza para la diferencia de dos medias poblacionales

**Definición**
El intervalo de confianza al 100(1-alpha)% para mu1-mu2 se calcula utilizando la expresión:
![[Pasted image 20250601182700.png]]
donde *t_(1-alpha/2)* se corresponde con  el percentil  1-alpha/2 de una t de Student con *n1+n2-2* grados de libertad(en el caso de homogeneidad  de varianzas). Si  las varianzas son diferentes, los grados de libertad también.
El error estándar de  la diferencia de las medias  muestrales SE_x1-x2 se obtiene  utilizando el  método adecuado en cada caso, según se ha explicado antes(después de aplicar el test de Levene).


## Test t para la comparación de dos medias poblacionales

Las contrastes (unilateral  y bilateral) para la comparación de dos medias poblacionales se define de la siguiente manera:
![[Pasted image 20250601183525.png]]

El estadístico de  contraste utilizado para resolver el contraste de hipótesis  es t_s.
Si  *H_0* es cierta, *t_s* tiene una distribución t de Student con *n1+n2*-2 grados de libertad. Con esta distribución obtendremos  el p-valor de los datos. Criterio de decisión: rechazar la *H_0* si el p-valor es<alpha. 
## Alternativas no paramétricas

Si no se cumplen las condiciones de validez de los métodos basados en la t de student utilizaremos un test no paramétricos para muestras independientes: el test de Wilcoxon.
Contraste bilateral:
$$
\begin{align}
H_{0}: \text{Las dos poblaciones tienen la misma distribución de la variable contínua X}. \\
H_{A}: \text{Las dos poblaciones NO tienen la misma distribución de la variable X}.
\end{align}
$$
Contraste unilateral o  direccional:
$$
\begin{align}
H_{0}: \text{Las dos poblaciones tienen la misma distribución de la variable continua X}. \\
H_{A}: \text{La primera población toma valores de X más grandes (o más pequeños) que la segunda}.
\end{align}
$$

# Resumen

![[Pasted image 20250601172214.png]]