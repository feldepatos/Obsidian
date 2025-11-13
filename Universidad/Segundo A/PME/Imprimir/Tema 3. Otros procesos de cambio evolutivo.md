# Desviaciones del apareamiento aletaorio

## Endogamia
La endogamia es la reproducción entre parientes genéticos. Su efecto es aumentar la proporción de homozigosidad en comparación con lo esperados según HWE.
Por consiguiente, la consanguinidad en si misma no es un mecanismo evolutivo. Sin embargo, como veremos, la consanguinidad puede tener consecuencias evolutivas importantes.
### Autofecundación

En una población en HWE con los alelos A1 y A2 con una frecuencia inicial de 0'5 para cada uno. La frecuencia de los individuos

| A1A1 | A1A2 | A2A2 |
| ---- | ---- | ---- |
| 0'25 | 0'5  | 0'25 |
Imaginemos que hay 1000 individuos en la población, por tanto, 250 A1A2, 500 A1A2 y 250 A2A2.
Si todos los individuos de la población se reproducen por autofecundación, los padres heterozigotos producirán la mida de los descendientes homozigotos, mientras que loas padres heterozigotos producirán la mitad de los descendientes homozigotos y la otra mitad heterozigotos. En los 1000 descendientes de nuestra población habrá 

| A1A1 | A1A2 | A2A2 |
| ---- | ---- | ---- |
| 250  | 375  | 375  |
Si la población continúa autofecundandose durante dos generaciones más, entonces entre los 1000 individuos de la última generación habrá 468'75 de cada tipo y 62'5 heterozigotos. La frecuencia de los heterozigotos se habrá reducido a la mitad en cada generación y la frecuencia de los homozigotos se habrá incrementado.
La conclusión 2 del análisis de HW no se cumple, ya que no podemos predecir las frecuencias genotípicas multiplicando las frecuencias alélicas. Advierta que en la generación tercera, las frecuencias alélicas para A1 y A2 son todavía 0'5.
No obstante, la frecuencia de los heterozigotos está lejos de 2(0'5)(0'5). Comparando con las previciones de HW, hay un déficit de heterozigotos y un exceso de homozigotos. 
¿Qué pasa con la conclusión 1 de HW?¿Han cambiado las frecuencias alélicas de una generación a la siguiente con consanguinidad? En nuestro ejemplo no ha ocurrido. Podemos comprobar el caso general calculando la frecuencia del alelo A1 en el conjunto de genes producidos por la población y que se muestra en la última fila de la tabla del caso general de autofecundación. La frecuencia del alelo A1 en el conjunto de genes es igual a la frecuencia de los adultos *A1A1* de la población más la mitad de la frecuencia de *A1A2*, lo que da:
$$
p²+\frac{15pq}{16}+\frac{1}{2}\left[ \frac{pq}{8} \right]
$$
### Caso general de autofecundación
La frecuencia del alelo A1 es *p* y la frecuencia del alelo A2 es *q*. Advierta que las frecuencias alélicas no cambian de generación en generación, sólo las frecuencias genotípicas. Según Crow(1983).


| Generación | A1A1         | Frecuencia de A1A2 | A2A2         |
| ---------- | ------------ | ------------------ | ------------ |
| 0          | p²           | 2pq                | q²           |
| 1          | p²+(pq/2)    | pq                 | q²(pq/2)     |
| 2          | p²+(3pq/4)   | pq/2               | q²(3pq/4)    |
| 3          | p²+(7pq/8)   | pq/4               | q²(7pq/8)    |
| 4          | p²+(15pq/16) | pq/8               | q²+(15pq/16) |

### Cálculo de la F (Grado de consanguinidad)
Necesitamos genealogía, o sea un esquema que muestre las relaciones de parentesco de los individuos donde llega a una hembra que es hija de medios hermanos. 
Hay dos vías por las que esta hembra puede recibir alelos que son idénticos por ascendencia. Una es que reciba dos copias del alelo "triángulo verde" de su abuela. Esto sucederá si la abuela pasa el alelo triángulo tanto a su hija como a su hijo y tanto la hija como el hijo lo pasen a la nieta.
La otra vía sería que pueda recibir las dos copias del alelo "diamante azul" de su abuela. La probabilidad total de esto es 1/16. La probabilidad de que la hija de medios hermanos reciba dos alelos idénticos por ascendencia en cualquiera de los dos casos es 1/16+1/16=1/8.
$$
F_{I}=\left( \frac{1}{2} \right)^{n-1}(1+F_{A})
$$

### Depresión por endogamia
Esta situación se produce por la exposición de alelos recesivos deletéreos a la selección donde incluso puede haber una pérdida de función.
Estos alelos son a menudo recesivos, ya que un solo alelo tipo silvestre puede producir, en muchos  casos, suficientes proteína funcional  como para dar  lugar al fenotipo normal. Aun cuando en heterozigosis  pueden no tener en absoluto consecuencias en la eficacia, las mutaciones de pérdida de función pueden ser letales en homozigosis. Al aumentar la proporción de individuos homozigotos en una población, la consaguinidad aumenta la frecuencia de aquellos recesivos deletéreos que afectan al fenotipo. 
**La depresión consaguínea se refiere al efecto que estos alelos tienen sobre la eficacia media de los descendientes en una población.**

Existen mecanismos que evitan la consanguinidad como la elección de la pareja, la autoincompatibilidad genéticamente controlada y la dispersión. Pero en ciertas circunstancias, la consanguinidad puede ser inevitable.

En resumen, los aparemientos no aleatorios no alteran por sí mismos las frecuencias alélicas. Por consiguientes, no es un mecanismo evolutivo. Sin embargo, alteran las frecuencias genotípicas, por tanto, las frecuencias fenotípicas y alterar el patrón de selección natural y de evolución de la población. 

Ejemplo I
Se puede observar en los hijos de primos hermanos presentan una mayor tasa de mortalidad que las de los hijos de padres no emparentados. También se ha observado frecuentemente una elevada depresión consanguínea en poblaciones de animales en cautividad.
![[Pasted image 20251104120224.png]]
Ejemplo II
Una clase de herrerillos existe una correlación entre el nivel de consanguinidad de la pareja y el número de huevos que no eclosionaban de una puesta.

![[Pasted image 20251104120847.png]]

# Poblaciones finitas: deriva genética
Introducción
La variación generada por mutación es aleatoria  en el sentido de que cuando la mutación sustituye un aa por otro en una proteína, lo hace sin considerar si el cambio mejorará la funcionalidad de la proteína. Pero la selección natural en si misma no se produce al azar. Es precisamente la no aleatoriedad de la selección al escoger las mutaciones lo que da lugar a la adaptación.
Entre los mecanismos no selectivos de la evolución hay uno que es absolutamente aleatorio. Dicho mecanismo es la deriva genéica. La deriva genética no da lugar a adaptación, pero da lugar a cambios en las frecuencias alélicas. En el modelo de HW, la deriva genética se produce como consecuencia de que el tamaño de población infinito no se cumple.

## Modelo de deriva genética
Es necesario imaginar una población ideal, similar a las que a las anteriores, pero de tamaño finito, de hecho, de pequeño tamaño. Como siempre nos fijamos en un solo locus con dos alelos, *A1* y *A2*. El conjunto de genes de la generación actual, el alelo *A1* tiene una frecuencia de 0'6 y el alelo *A2* de 0'4. Dejemos que los gametos de este conjunto de genes se combinen al azar para dar lugar exactamente 10 zigotos. Estos constituirán toda la población de la siguiente generación.
Podemos simular la producción de 10 zigotos de nuestro conjunto de genes mediante un modelo físico. Una bolsa con 100 alubias representa el conjunto de genes. 60 de las alubias son negras y representan al alelo *A1* ; 40 son blancas y representan al alelo *A2*. Constituiremos cada zigoto agitando la bolsa, cerrando los ojos y sacando alubias. Primero sacaremos una alubia que represente al óvulo, anotaremos su genotipo y la devolveremos su genotipo y la devolvemos a la bolsa. Sacamos alubias de la bolsa y la vamos anotando. Los genotipos de los 10 zigotos son:

| *A2A1* | *A1A1* | *A1A1* | *A1A1* | *A2A2* |
| ------ | ------ | ------ | ------ | ------ |
| *A1A1* | *A2A2* | *A1A2* | *A1A1* | *A1A1* |
![[Pasted image 20251113090856.png]]
Contando los genotipos, tenemos que *A1A1* tiene una frecuencia de 0'6, *A1A2* una frecuencia de 0'2 y *A2A2* una frecuencia de 0'2. Contando los alelos vemos que cuando estos zigotos crezcan y se reproduzcan, la frecuencia del alelo *A1* en el nuevo conjunto de genes será 0'7 y la frecuencia del alelo *A2* será 0'3.
Hemos completado una generación en el ciclo de vida de nuestra población modelo. No parece que haya sucedido gran cosa, pero advierte que no se cumplen las dos conclusiones de HWE. Las frecuencias alélicas han cambiado de una generación a la siguiente y no podemos calcular las frecuencias genotípicas  multiplicando las frecuencias alélicas. La razón de que nuestra población no haya cumplido el principio  de HW es simplemente porque es pequeña.
En una población pequeña, el azar da lugar a resultados que difieren de las esperanzas teóricas. El azar en nuestra población simulada fue la extracción de alubias de la bolsa para formar zigotos. Cogimos alubias negras y alubias blancas no en la proporción exacta predicha de 0'6 y 0'4, sino en una proporción que resultó ser un poco mayor en alubias negras y un poco menor en alubias blancas. Este tipo de discrepancias aleatorias entre esperado teóricamente y los resultados reales se denominan errores de muestreo. El error de muestreo en la formación de zigotos a partir de un conjunto de genes se denomina deriva genética. Debido a que se trata sólo del efecto acumulativo de sucesos aleatorios, la deriva genética no puede dar lugar a adaptación. Pero puede dar lugar, como hemos visto, a que las frecuencias alélicas no cambian. La suerte ciega es, por sí misma, un mecanismo evolutivo.
A veces es difícil ver la diferencia entre deriva genética y la selección natural. En nuestro modelo de población pequeña, las copias del alelo *A1* tuvieron más éxito en pasar a la siguiente generación que las copias del alelo *A2*. El éxito reproductivo diferencial es selección¿ o no lo es? En este caso no lo es. Si hubiera sido selección, el éxito diferencial de los alelos de nuestra población modelo hubiera sido explicable en términos de los fenotipos que los alelos confieren a los individuos que los llevan. Los individuos con una o dos copias del alelo *A1* deberían haber sido mejores en supervivencia, en encontrar alimento en atraer a la pareja. Sin embargo, los individuos que llevan copias del alelo *A1* no fueron de hecho ninguna de esas cosas. Sólo tuvieron suerte;  dio la casualidad de que sus alelos se extrajeron del conjunto de genes más a menudo. La selección es éxito reproductio diferencial que sucede por alguna razón. La deriva genética es éxito reproductivo diferencial que simplemente sucede.
Otra  forma de ver que la deriva genética es diferente de la selección  es reconocer que las frecuencias alélicas y  genotípicas en nuestros 10 zigotos fácilmente podrían  haber sido diferentes de lo que fueron. Para probarlo, podemos repetir el ejercicio extrayendo alubias de nuestra bolsa para formar 10 zigotos. Esta vez, los genotipos de los zigotos son:

| *A1A1* | *A1A1* | *A1A1* | *A2A1* | *A1A2* |
| ------ | ------ | ------ | ------ | ------ |
| *A2A2* | *A1A2* | *A1A1* | *A2A1* | *A2A2* |

En este conjunto de zigotos las frecuencias genotípicas son 0'4 para *A1A1*, 0'4 para *A1A2* y 0'2 para *A2A2*. Las frecuencias alélicas son 0'6 para *A1* y 0'4 para *A2*.
Repitiendo el ejercicio una tercera vez se reproducen estos zigotos:
| *A1A1* | *A1A1* | *A1A1* | *A2A1* | *A1A2* |
| ------ | ------ | ------ | ------ | ------ |
| *A2A2* | *A1A2* | *A1A1* | *A2A1* | *A2A2* |

Ahora las frecuencias genotípicas son 0'4 para *A1A1* , 0'3 *A1A2* y 0'3 para *A2A2*, y las frecuencias alélicas son 0'55 para *A1* y 0'45 para *A2*.

Los tres conjuntos de zigotos nos demuestran que si comenzamos con un conjunto de genes en el que el alelo *A1* está a una frecuencia de 0'6 y formamos exactamente una población de 10 zigotos, la frecuencia de *A1* puede aumentar, mantenerse o disminuir. De hecho, la nueva frecuencia de *A1* en un conjunto de 10 zigotos extraídos de nuestro conjunto de genes puede ser cualquiera entre 0 y 1'0, aunque dentro de este rango los resultados extremos no son probables. La gráfica de la imagen anterior muestra la probabilidad teórica de cada uno de los resultados posibles. En conjunto, hay alrededor del 40'5% de probabilidad de que caiga a un valor menor y alrededor del 41'5% de que aumente a un valor mayor. Los lectores no debería acepta tal cual lo que decimos, debería proporcionarse su propia de alubias y formar una serie de conjuntos de zigotos. Insistimos, el tema es que la deriva genética es evolución que simplemente sucede por azar.
## Sampling effects: la distribución binomial
![[Pasted image 20251113091004.png]]
## Estudio experimental de la fijación o pérdida aleatoria de heterozigosidad
Se comprobó en poblaciones pequeñas de *Drosophila melanogaster*. Adoptando un esquema que había sido utilizado por Kerr y Wright, Buri fundó 107 poblaciones de moscas, cada una de ellas a partir de ocho hembras y ocho machos. Todas las moscas fundadoras eran heterozigóticas para alelos de un gen para el color de los ojos llamado *brown*. Todas las moscas tenían el mismo genotipo : *bw75/bw*. Así, en las107 poblaciones, la frecuencia inicial del alelo *bw75* fue de 0'5. Buri mantuvo estas poblaciones durante 19 generaciones. En cada población y en cada generación, Buri mantuvo el tamaño poblacional en 16, extrayendo 8 hembras y 8 machos al azar como padres de la generación siguiente.
¿Qué resultados esperaríamos que la frecuencia del alelo *bw75* y *bw*, confiere ventaja selectiva, entonces esperaríamos que la frecuencia del alelo *bw75* oscilara al azar por deriva genética en cada generación. 19 generaciones serían suficientes, en poblaciones con 16 individuos, para que muchas poblaciones quedaran fijadas para uno u otro alelo. Debido a que el alelo *bw75* tiene una frecuencia inicial de 0'5 esperaríamos  que  este alelo se perdiera tan a menudo como se fijase. A medida que el alelo *bw75* se fija o se pierde por deriva en cada población, esperaríamos la disminución de la heterozigosidad en el conjunto de las poblaciones. La tasa de disminución de la heterozigosidad seguiría la ecuación de Wright, dada en la sección anterior.
Los resultados de Buri confirman estas predicciones. Cada uno de los pequeños gráfi-
cos de la Figura 6.14 son histogramas que resumen las frecuencias alélicas de las 107 poblaciones en una generación concreta. El eje horizontal representa la frecuencia del alelo *bw75*, y el eje vertical representa el número de poblaciones en cada una de las  frecuencias. La frecuencia del alelo *bw75* era 0'5 en la generación cero de todas las poblaciones, que no se muestran en la figura. Después de una generación de deriva genética, muchas poblaciones todavía presentan una frecuencia cercana a 0'5, aunque una de las poblaciones tenía una frecuencia alélica de 0'22 y otra de 0'69. A medida que la frecuencia del alelo *bw75*  aumenta en unas poblaciones y disminuye en otras, la distribución  de las frecuencias alélicas  se ensancha  rápidamente. En la generación cuarta, la frecuencia de *bw75* alcanza 1 por primera vez en una población. En la generación 6 la frecuencia de *bw75* alcanza 0 por primera vez en una población. A medida que la frecuencia alcanza 0 o 1 en más y más poblaciones, la distribución de las  frecuencias adquiere una forma de U. Hacia el final del experimento, *bw75* se había perdido en 30 poblaciones y se había fijado en 28. La proporción 30:28 de pérdida y fijaciones está muy próxima a la proporción 1:1 que habíamos predicho con deriva genética. Durante el expermiento de Buri, hubo una evolución espectacular en casi todas las 107 poblaciones  de mosca de la fruta, pero la selección natural no tuvo nada que ver con esto.
## Conclusión
- La deriva genética ocurre en todas las poblaciones y sus efectos son más intensos cuanto menor es el tamaño de la población.

- La fijación (y pérdida) de alelos es una consecuencia necesaria de la deriva genética, y el tiempo que tarda en producirse depende del tamaño de la población.

- La probabilidad de fijación de un alelo por deriva es igual a su frecuencia.

- La deriva genética conduce a un aumento de la homocigosis.

- Los modelos de deriva genética se basan en las poblaciones ideales de Wright-Fisher, pero pueden aplicarse a poblaciones reales si se reemplaza el tamaño censal por el tamaño efectivo.

- Existen varias expresiones para calcular el tamaño efectivo de una población.

- La endogamia puede tratarse matemáticamente como deriva genética, ya que ambas generan homocigosis mediante autozigosis.
# La mutación como fuerza evolutiva
## Mutagenesis letal

# Equilibrio mutación-selección
# Equilibrio mutación-selección y carga genética
## Principio Haldane-Muller
## Conclusión
- La mutación es un proceso físico-químico que puede producir diferentes tipos de cambios genéticos.

- La mutación es la última fuente de variación genética.

- Las tasas de mutación se pueden medir mediante la prueba de fluctuación de Luria-Delbrück u otros métodos,
- y son diferentes de las frecuencias de mutación.

- Las tasas de mutación varían ampliamente entre los organismos.

- Se puede alcanzar un equilibrio entre mutación y selección, el cual dependerá de la tasa de mutación,
- el coeficiente de selección y el modo de herencia.

- La carga mutacional es independiente del coeficiente de selección (principio de Haldane-Müller).
# Efectos de la migración o flujo génico
La migración es el movimiento de alelos entre poblaciones. Puede estar causada por cualquiera cosa que desplace alelos lo bastante lejos como para ir de una población a otra.
Hay diferentes modelos :
- Modelo continente-isla
- Modelo isla infinito
- Modelo en una dimensión→Separación por la distancia
- Modelo en dos dimensiones→ "Stepping-stone"
## Demostración de la migración como fuerza evolutiva(Continente isla)
Sea la p1 la frecuencia del alelo A1 en una población de una isla. Y pc la frecuencia del alelo A1 en la población continental. Imagine que en cada generación un grupo de individuos se desplaza de la población continental a la isla, en donde constituyen la fracción *m* de la población de la isla. Queremos conocer cómo consecuencia de la migracón, y si hay una frecuencia de equilibrio para A1 que no cambie más incluso si continúa la migración.
En primer lugar, habrá que obtener la expresión para *pI'*, la frecuencia de A1 en la isla en la generación siguiente. Una fracción *(1-m)* de los individuos de la generación siguiente ya está en la isla. En estos individuos de la generación siguiente viene del continente. En ellos la frecuencia de A1 es *pC*. Así, la nueva frecuencia de A1 en la población de la isla es el promedio ponderado de la frecuencia entre los residentes y la de los inmigrantes.
$$
p'_{I}=(1-m)(p_{I})+(m)(p_{C})
$$
Podemos obtener una expresión para el ApI, que es el cambio en frecuencia alélica en la isla de una generación a la siguiente:
$$
\vartriangle p_{I}=p'_{I}-p_{I}
$$
Sustituyendo pI' por nuestra expresión anterior y simplificando, tendremos:
$$
\vartriangle p_{I}=(1-m)(p_{I})+(m)(p_{C})-p_{I}=m(p_{C}-p_{I})
$$
Finalmente, podemos determinar la frecuencia en el equilibrio del alelo A1 en la isla. La condición de equilibrio es que no cambie pI. Es decir,
$$
\vartriangle p_{I}=0
$$
si resolvemos la ecuación para ApI igual a 0, tendremos:
$$
m(p_{C}-p_{I})=0
$$
Esta expresión muestra que la frecuencia de A1 permanecerá constante en la isla si no hay migración (*m=0*), o si la frecuencia de A1 en la isla es idéntica a su frecuencia en el continente (pC=pI). En otras palabras, sin ninguna fuerza que se oponga, la migración igualará finalmente las frecuencias de las poblaciones de la isla y del continente.

## Aplicación del modelo continente-isla
 Este modelo explora los efectos de la migración sobre las dos conclusiones de análisis de HWE.

 Tenemos dos poblaciones, una en un continente y otra en una pequeña isla costera. Debido  a que la población de la isla es relativamente pequeña en relación con la poblcaión continental, cualquier suceso migratorio desde la isla al continente no tendrá consecuencias en las frecuencias alélicas y genotípicas del continente. Por ello, la migración y el flujo génico correspondiente, será efectivo sólo en una dirección, del continente a la isla. Pero, ¿puede la migración del continente  a la isla desplazar las frecuencias alélicas y genotípicas de la isla lejos del equilibrio de HWE?

 Para ello, debemos la frecuencia antes de la migración de A1 es de 0'1(o sea, esta fijado en la población).
 Cuando los gametos de un conjunto de genes en donde está fijado A1 se combina al azar para formar zigotos, las frecuencias genotípicas serán los siguientes:

| A1A1 | A1A2 | A2A2 |
| ---- | ---- | ---- |
| 1    | 0    | 0    |
Si damos a nuestra población un tamaño dado, por lo que imaginemos que había  800 zigotos, que dejaremos que crezcan y se conviertan en adultos.

En otro supuestos en nuestra población continental será el alelo A2 fijado, y que antes de que los individuos de la isla alcancen la madurez, migraron 200 individuos del continente a la isla. Después del proceso migratorio, el 80% de la población de la isla es nativa y el 20% continental. Entonces, las nuevas frecuencias genotípicas serán:

| A1A1 | A1A2 | A2A2 |
| ---- | ---- | ---- |
| 0'8  | 0    | 0'2  |
Cuando los individuos de la isla se reproduzcan, su conjunto de genes tendrá las frecuencias alélicas de 

| A1  | A2  |
| --- | --- |
| 0'8 | 0'2 |
La migración ha cambiado las frecuencias alélicas de la población de la isla, violando la conclusión 1 de HWE. Antes de la migración la frecuencia de A1 en la isla era de 1'0; después de la migración la frecuencia de A1 de 0'8. La población de la isla ha cambiado como consecuencia de la migración. La migración también da lugar a frecuencias genotípicas en los adultos que no están de acuerdo con la conclusión 2 de HWE. Dada las frecuencias alélicas de 0'8 y 0'2, tendría unas frecuencias genotípicas de 0'64, 0'32 y 0'04. 
Comparados con estos valores esperados, la población de la isla tiene, después de la migración, un exceso de homozigotos y un déficit de heterozigotos. Desde luego, con una sola generación de apareamiento aleatorio la población volverá a las frecuencias genotípicas del equilibrio de HWE.

En resumen, la migración consiste en el movimiento de alelos de una población a otra. En una población dada, la migración puede dar lugar a cambios en las frecuencias alélicas de una generación a la siguiente. En poblaciones pequeñas, reciben inmigrantes de poblaciones grandes, la migración puede ser un potente mecanismos evolutivo. A lo largo de grupos de poblaciones, el flujo génico tiende a homogeneizar las frecuencias alélicas. Por eso, la migración tiende a evitar la divergencia evolutiva de las poblaciones.
##  Aplicación del modelo continente-isla II
Investigación experimental sobre la migración como mecanismos evolutivo
La serpiente de agua *Nerodia sipedon* proporcionan un ejemplo de migración desde una población continental a una isla. Estas serpientes viven en los alrededores del lago Erie y en las islas del lago. El patrón de color viene determinado por un solo locus con dos alelos, siendo el alelo para bandas dominantes sobre el alelo sin bandas.
En el continente casi todas son bandeadas, mientras que en las islas muchos carecen de bandas. La diferencia en la composición de las poblaciones del continente respecto de las de las islas que es consecuencia de la selección natural promovida por los predadores. 
Si la selección favorece a las serpientes sin bandas en las islas, entonces se esperaría las poblaciones isleñas estuvieran formadas sólo por serpientes sin bandas. Cosa que no sucede, debido que en cada generación varias serpientes con bandas se desplazan del continente a las islas. Los migrantes traen consigo alelos para el patrón a bandas. Cuando las serpientes migrantes se cruzan con las serpientes de la isla contribuyen con copias del alelo para bandas al conjunto de genes de la isla.
Este caso sería un ejemplo de la migración actúa como fuerza evolutiva en oposición a la selección natural, evitando que en las poblaciones de las islas quede fijado el alelo sin bandas.
![[Pasted image 20251104112141.png]]

## La migración como fuerza evolutiva homogeneizadora entre las poblaciones

 Éste es el efecto general de la migración: tiende a homogeneizar las frecuencias alélicas a lo largo de las poblaciones. En las serpientes de agua, a esta homogeneización se opone la selección natural.
¿Hasta dónde iría la homogeneización si no se opusiera la selección? El modelo anterior demuestra el flujo génico desde un continente a una isla, llevará finalmente las frecuencia alélicas de la isla a un valor exactamente igual al que hay en el continente. Es decir, si se permite que prosiga la migración sin oposición de cualquiera otra fuerza evolutiva, finalmente homogeneizará totalmente las frecuencias alélicas en las poblaciones.

## Estructura población
La migración tiene un efecto homogeneizador sobre las diferencias genéticas entre poblaciones.

Sin embargo, cuando actúan mecanismos evolutivos diferentes y el flujo genético
se reduce o desaparece, cada población se vuelve genéticamente diferente, una situación denominada: Estructura poblacional.

Como se observa, la deriva genética aleatoria conduce a una disminución de la heterocigosidad:

## Efecto Wahlund
Es una reducción en la heterocigosidad observada en una población que ha sido subdividida en subpoblaciones con diferentes frecuencias alélicas.
En la gráfica se observa como la heterozigosidad esperada bajo el HWE es la mitad(0'3) pero debido a la migración ese valor de heterozigosidad este ser verá incrementado o reducido.


En palabras, el efecto de Wahlund provoca una disminución de la frecuencia de homocigotas recesivos luego de la mezcla de poblaciones y apareamiento bajo panmixia igual a la varianza de frecuencias alélicas (del alelo recesivo) entre poblaciones.


## Conclusión
- La migración es un proceso que puede cambiar las frecuencias alélicas y genotípicas muy rápidamente.

- Existen varios modelos de migración; el modelo continente-isla es uno de los
- más básicos.

- En el modelo continente-isla se puede obtener un modelo de migración-selección polimórfico.

- En ausencia de migración, la estructura poblacional se construye bajo la acción de la deriva genética.

- El efecto Wahlund es la pérdida de heterocigosidad debido a la estructura poblacional y es importante en biología de la conservación.

- Los efectos fundadores son un caso extremo de estructura poblacional debido a la migración/aislamiento.

# Desequilibrio de ligamiento: falta de independencia

## Utilizar el LD como evidencia de selección reciente
## Conclusión
- El desequilibrio de ligamiento es la falta de independencia entre alelos de
- diferentes loci y tiene importantes consecuencias evolutivas.

- Las frecuencias de haplotipos (gametos) en apareamientos aleatorios no se mantienen constantes, sino que varían según el desequilibrio de ligamiento y la tasa de recombinación genética.

- La recombinación disipa el desequilibrio de ligamiento.

- La selección multilocus, la mezcla poblacional o la selección de un alelo ventajoso en poblaciones finitas pueden generar desequilibrio de ligamiento.

- En presencia de desequilibrio de ligamiento, la selección que actúa sobre un locus afecta las frecuencias alélicas en loci ligados (arrastre genético) y produce una pérdida local de variabilidad (barrido selectivo).

- El desequilibrio de ligamiento se utiliza como indicador de episodios recientes de selección de nuevos alelos ventajosos.