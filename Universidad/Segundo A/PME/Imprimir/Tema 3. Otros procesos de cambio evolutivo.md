# Desviaciones del apareamiento aletaorio

## Endogamia

La endogamia es la reproducción entre parientes genéticos. Su efecto es aumentar la proporción de homozigosidad en comparación con lo esperados según HWE.

Por consiguiente, la consanguinidad en si misma no es un mecanismo evolutivo. Sin embargo, como veremos, la consanguinidad puede tener consecuencias evolutivas importantes.
### Autofecundación

La **autofecundación** es un tipo de reproducción sexual en la que **un mismo individuo produce los gametos masculinos y femeninos que se fusionan entre sí**, dando origen a la descendencia.

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

¿Qué pasa con la conclusión 1 de HW?¿Han cambiado las frecuencias alélicas de una generación a la siguiente con consanguinidad? En nuestro ejemplo no ha ocurrido. Podemos comprobar el caso general calculando la frecuencia del alelo A1 en el conjunto de genes producidos por la población y que se muestra en la última fila de la tabla del caso general de autofecundación. La frecuencia del alelo *A1* en el conjunto de genes es igual a la frecuencia de los adultos *A1A1* de la población más la mitad de la frecuencia de *A1A2*, lo que da:
$$
p²+\frac{15pq}{16}+\frac{1}{2}\left[ \frac{pq}{8} \right]
$$
### Caso general de autofecundación

La frecuencia del alelo A1 es *p* y la frecuencia del alelo A2 es *q*. Advierta que las frecuencias alélicas no cambian de generación en generación, **sólo las frecuencias genotípicas. Según Crow(1983).**


> [!success] Experimento de Crow
> Afirmaba que la autofecundación solo cambia las frecuencias genotípicas y no las alélicas porque este tipo de reproducción no introduce nuevos alelos ni elimina los existentes, sino que únicamente modifica la forma en que los alelos se combinan dentro de los individuos.

Cuando ocurre la autofecundación, los gametos que se unen provienen del mismo individuo. Como consecuencia, los alelos presentes en la población siguen siendo los mismos y mantienen sus proporciones, por lo que las frecuencias alélicas permanecen constantes de una generación a otra.

Sin embargo, la autofecundación sí afecta la estructura genotípica de la población. En cada generación disminuye la frecuencia de los heterocigotos y aumenta la de los homocigotos, tanto dominantes como recesivos. Esto se debe a que los alelos idénticos tienen mayor probabilidad de encontrarse al provenir del mismo genotipo.

En ausencia de otras fuerzas evolutivas como mutación, migración, selección o deriva genética, la autofecundación por sí sola no puede cambiar las frecuencias alélicas. Por esta razón, Crow señalaba que su efecto se limita a alterar las frecuencias genotípicas, rompiendo el equilibrio de Hardy-Weinberg, pero sin modificar la composición alélica de la población.


| Generación | A1A1         | Frecuencia de A1A2 | A2A2         |
| ---------- | ------------ | ------------------ | ------------ |
| 0          | p²           | 2pq                | q²           |
| 1          | p²+(pq/2)    | pq                 | q²(pq/2)     |
| 2          | p²+(3pq/4)   | pq/2               | q²(3pq/4)    |
| 3          | p²+(7pq/8)   | pq/4               | q²(7pq/8)    |
| 4          | p²+(15pq/16) | pq/8               | q²+(15pq/16) |

> [!success] Consecuencias de la autofecundación
> Cambio en las frecuencias genotípicas, NO alélicas


### Cálculo de la F (Grado de consanguinidad)

> [!NOTE] Grado de consanguinidad
> Es la forma de clasificar **qué tan cercanas son dos personas dentro de una misma familia**, según el número de generaciones que las separan de su antepasado común.


Necesitamos genealogía, o sea un esquema que muestre las relaciones de parentesco de los individuos donde llega a una hembra que es hija de medios hermanos. 

Hay dos vías por las que esta hembra puede recibir alelos que son idénticos por ascendencia. Una es que reciba dos copias del alelo "triángulo verde" de su abuela. Esto sucederá si la abuela pasa el alelo triángulo tanto a su hija como a su hijo y tanto la hija como el hijo lo pasen a la nieta.
La otra vía sería que pueda recibir las dos copias del alelo "diamante azul" de su abuela. La probabilidad total de esto es 1/16. La probabilidad de que la hija de medios hermanos reciba dos alelos idénticos por ascendencia en cualquiera de los dos casos es 1/16+1/16=1/8.
$$
F_{I}=\left( \frac{1}{2} \right)^{n-1}(1+F_{A})
$$
### Coeficiente de parentesco


> [!NOTE] Coeficiente de parentesco
> Es un valor que cuantifica el grado de vínculo biológico entre dos individuos, indicando la probabilidad de que un gen tomado al azar en uno de ellos sea idéntico por descendencia a un gen tomado al azar en el otro, debido a que ambos proceden de un mismo antepasado.

Supongamos una población de tamaño Ne donde, inicialmente, hay 2N alelos diferentes y, por lo tanto, el coeficiente de endogamia en la generación inicial (t = 0) es: F₁ = 0

Todos los individuos contribuyen por igual al acervo genético de la población y, por lo tanto, aunque habrá muchos gametos que portarán el mismo alelo (como consecuencia del proceso de replicación que acompaña a la formación de estos gametos), cada alelo (o gametos) tendrá una frecuencia de 1/(2Ne) en la población.

Imaginemos que tomamos un gameto al azar.

> [!question] ¿Cuál es la probabilidad de que al extraer otro gameto al azar, este lleve exactamente el mismo alelo que el primero?
> 1/(2Ne)


Si 1/(2N) es la probabilidad de que dos gametos lleven alelos idénticos en la primera generación, por lo tanto: F₁ = 1/(2Ne)

El cálculo de F en la segunda generación (F2) es más complejo porque, ahora, hay dos maneras en que pueden surgir homocigotos idénticos:

1. Como consecuencia de una nueva replicación génica

2. Como consecuencia de una replicación de una generación anterior

De nuevo, la probabilidad de que en un cigoto se unan gametos que porten alelos idénticos de nueva replicación es 1/(2N).

El resto de los cigotos (1-1/(2N)) portarán alelos que son independientes en el origen con respecto a la generación 1, pero que pueden ser idénticos en el origen con respecto a la generación 0 y que, por lo tanto, tendrán el coeficiente F de la generación anterior (F₁)

Por lo tanto, la probabilidad total de homocigotos idénticos en la generación 2 será la suma de ambos términos:
$$
F_{2}=\left( \frac{1}{2N} \right)+\left( 1-\frac{1}{2N_{e}} \right)F_{1}
$$

Lo mismo se aplica para las siguientes generaciones, por lo tanto, el coeficiente F en la generación t será:
$$
F_{t}=\left( \frac{1}{2Ne} \right)+\left( 1-\frac{1}{2Ne} \right)F_{t-1}
$$

Esta expresión nos dice que el coeficiente de endogamia implica dos fracciones:

1. Un incremento 1 / (2N) correspondiente a la nueva endogamia, que se genera en cada generación.

2. Y el resto: (1-1/(2N)) Ft₁ correspondiente a la endogamia previa, acumulada hasta la generación anterior (F-1).

Por lo tanto, si en un momento dado no hay un aumento en la endogamia, como ocurriría si la población se expandiera repentinamente, la endogamia previa no se pierde, ya que es el resultado de la pérdida irreparable de alelos generación tras generación.
$$
1-F=(1-F_{0})\left( 1-\frac{1}{2N} \right)^{t}
$$

> [!NOTE] Población efectiva
> Es el número de individuos de una población ideal que **contribuirían genéticamente a la siguiente generación de la misma manera que lo hace la población real**. No coincide necesariamente con el tamaño real de la población,


> [!TIP] Diferencias entre grado de consaguinidad y coeficiente de parentesco
> El grado de consanguinidad indica **qué tan cerca están dos personas en el árbol familiar**, mientras que el coeficiente de parentesco indica **cuánto material genético comparten**

### Depresión por endogamia

Esta situación se produce por la exposición de alelos recesivos deletéreos a la selección donde incluso puede haber una pérdida de función.

Estos alelos son a menudo recesivos, ya que un solo alelo tipo silvestre puede producir, en muchos  casos, suficientes proteína funcional  como para dar  lugar al fenotipo normal. Aun cuando en heterozigosis  pueden no tener en absoluto consecuencias en la eficacia, las mutaciones de pérdida de función pueden ser letales en homozigosis. Al aumentar la proporción de individuos homozigotos en una población, **la consaguinidad aumenta la frecuencia de aquellos recesivos deletéreos que afectan al fenotipo.**

**La depresión consaguínea se refiere al efecto que estos alelos tienen sobre la eficacia media de los descendientes en una población.**

Existen mecanismos que evitan la consanguinidad como la elección de la pareja, la autoincompatibilidad genéticamente controlada y la dispersión. Pero en ciertas circunstancias, la consanguinidad puede ser inevitable.



> [!NOTE] Depresión por endogamia
> Es la **reducción de la eficacia biológica** de una población como consecuencia del **apareamiento entre individuos emparentados**. Ocurre porque la endogamia aumenta la **homocigosidad**, lo que permite que se expresen **alelos recesivos deletereos** y reduce la ventaja del heterocigoto, provocando menor supervivencia, fertilidad o crecimiento de los individuos


> [!EXAMPLE] Consaguinidad en humanos
> Se puede observar en los hijos de primos hermanos presentan una mayor tasa de mortalidad que las de los hijos de padres no emparentados. También se ha observado frecuentemente una elevada depresión consanguínea en poblaciones de animales en cautividad
> ![[Pasted image 20251104120224.png]]



> [!EXAMPLE] Huevos que no eclosian de herrerillos
> Una clase de herrerillos existe una correlación entre el nivel de consanguinidad de la pareja y el número de huevos que no eclosionaban de una puesta.

> [!SUCCESS] Conclusiones de las desviaciones del apareamiento aleatorio
> Los aparemientos no aleatorios no alteran por sí mismos las frecuencias alélicas. Por consiguientes, no es un mecanismo evolutivo. Sin embargo, alteran las frecuencias genotípicas, por tanto, las frecuencias fenotípicas y alterar el patrón de selección natural y de evolución de la población. 


---
# Poblaciones finitas: deriva genética
## Introducción

La variación generada por mutación es aleatoria en el sentido de que cuando la mutación sustituye un aa por otro en una proteína, lo hace sin considerar si el cambio mejorará la funcionalidad de la proteína. Pero la selección natural en si misma no se produce al azar. Es precisamente la no aleatoriedad de la selección al escoger las mutaciones lo que da lugar a la adaptación.

Entre los mecanismos no selectivos de la evolución hay uno que es absolutamente aleatorio. Dicho mecanismo es la deriva genéica. La deriva genética no da lugar a adaptación, pero da lugar a cambios en las frecuencias alélicas. En el modelo de HW, la deriva genética se produce como consecuencia de que el tamaño de población infinito no se cumple.

## Modelo de deriva genética

Es necesario imaginar una población ideal, similar a las que a las anteriores, pero de tamaño finito, de hecho, de pequeño tamaño. Como siempre nos fijamos en un solo locus con dos alelos, *A1* y *A2*. El conjunto de genes de la generación actual, el alelo *A1* tiene una frecuencia de 0'6 y el alelo *A2* de 0'4. Dejemos que los gametos de este conjunto de genes se combinen al azar para dar lugar exactamente 10 zigotos. Estos constituirán toda la población de la siguiente generación.

Podemos simular la producción de 10 zigotos de nuestro conjunto de genes mediante un modelo físico. Una bolsa con 100 alubias representa el conjunto de genes. 60 de las alubias son negras y representan al alelo *A1* ; 40 son blancas y representan al alelo *A2*. Constituiremos cada zigoto agitando la bolsa, cerrando los ojos y sacando alubias. Primero sacaremos una alubia que represente al óvulo, anotaremos su genotipo y la devolveremos su genotipo y la devolvemos a la bolsa. Sacamos alubias de la bolsa y la vamos anotando. Los genotipos de los 10 zigotos son:

| *A2A1* | *A1A1* | *A1A1* | *A1A1* | *A2A2* |
| ------ | ------ | ------ | ------ | ------ |
| *A1A1* | *A2A2* | *A1A2* | *A1A1* | *A1A1* |
![[Pasted image 20251113090856.png]]
Contando los genotipos, tenemos que *A1A1* tiene una frecuencia de 0'6, *A1A2* una frecuencia de 0'2 y *A2A2* una frecuencia de 0'2. Contando los alelos vemos que cuando estos zigotos crezcan y se reproduzcan, la frecuencia del alelo *A1* en el nuevo conjunto de genes será 0'7 y la frecuencia del alelo *A2* será 0'3.

Hemos completado una generación en el ciclo de vida de nuestra población modelo. No parece que haya sucedido gran cosa, pero advierte que no se cumplen las dos conclusiones de HWE.


> [!TIP] Primeras observaciones de la deriva genética
> Las **frecuencias alélicas han cambiado** de una generación a la siguiente y no podemos calcular las frecuencias genotípicas  multiplicando las frecuencias alélicas. La razón de que nuestra población no haya cumplido el principio  de HW es simplemente porque es pequeña.


> [!TIP] ¿Por qué ocurre?
> Porque en una población pequeña, el azar da lugar a resultados que difieren de las esperanzas teóricas. El azar en nuestra población simulada fue la extracción de alubias de la bolsa para formar zigotos. 

Cogimos alubias negras y alubias blancas no en la proporción exacta predicha de 0'6 y 0'4, sino en una proporción que resultó ser un poco mayor en alubias negras y un poco menor en alubias blancas. Debido a que se trata sólo del efecto acumulativo de sucesos aleatorios,**la deriva genética no puede dar lugar a adaptación.** Pero puede dar lugar, como hemos visto, a que las frecuencias alélicas no cambian. **La suerte ciega es, por sí misma, un mecanismo evolutivo.**

> [!TIP] Nueva definición de la deriva genética→Error de muestro
> Las discrepancias aleatorias entre lo esperado teóricamente y los resultados reales se denominan **error de muestreo**. El error de muestreo en la formación de zigotos a partir del conjunto de genes se denomina deriva genética.
> Además, la deriva genética es un proceso puramente aleatorio, por tanto, no puede dar a la adaptación.


A veces es difícil ver la diferencia entre deriva genética y la selección natural. En nuestro modelo de población pequeña, las copias del alelo *A1* tuvieron más éxito en pasar a la siguiente generación que las copias del alelo *A2*. El éxito reproductivo diferencial es selección¿ o no lo es? En este caso no lo es. Si hubiera sido selección, el éxito diferencial de los alelos de nuestra población modelo hubiera sido explicable en términos de los fenotipos que los alelos confieren a los individuos que los llevan. 

Los individuos con una o dos copias del alelo *A1* deberían haber sido mejores en supervivencia, en encontrar alimento en atraer a la pareja. Sin embargo, los individuos que llevan copias del alelo *A1* no fueron de hecho ninguna de esas cosas. Sólo tuvieron suerte;  dio la casualidad de que sus alelos se extrajeron del conjunto de genes más a menudo. **La selección es éxito reproductio diferencial que sucede por alguna razón. La deriva genética es éxito reproductivo diferencial que simplemente sucede.**

> [!QUESTION] ¿Cómo diferenciar entre deriva genética y la selección natural
> Ambas cambian las frecuencias de los alelos de manera diferente. 
> La deriva genética es aleatoria, causada por el azar, y tiene más efecto en poblaciones pequeñas; puede fijar alelos neutros o incluso deletéreos y reduce la diversidad genética al azar. La selección natural es no aleatoria, favorece alelos que aumentan la aptitud biológica, funciona en poblaciones de cualquier tamaño y tiende a aumentar la frecuencia de alelos beneficiosos y disminuir la de alelos perjudiciales de manera predecible. La deriva produce cambios impredecibles entre generaciones y entre poblaciones, mientras que la selección produce cambios consistentes según la ventaja adaptativa.


> [!tip] Deriva genética
> Es éxito reproductivo diferencial que simplemente sucede


Otra  forma de ver que la deriva genética es diferente de la selección  es reconocer que las frecuencias alélicas y genotípicas en nuestros 10 zigotos fácilmente podrían  haber sido diferentes de lo que fueron. Para probarlo, podemos repetir el ejercicio extrayendo alubias de nuestra bolsa para formar 10 zigotos. Esta vez, los genotipos de los zigotos son:

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

> [!SUCCESS] Primeras conclusiones de la deriva genética
> Las frecuencias alélicas fluctúan aleatoriamente.
La intensidad de las fluctuaciones es inversamente proporcional al tamaño de la población.
La deriva cambia tanto el genotipo como las frecuencias alélicas, aunque la forma podría mostrar proporciones HWE si el apareamiento es panmíctico.
Tarde o temprano, la deriva conducirá a la fijación de un alelo.
Por lo tanto, la deriva es una condición suficiente para la evolución.
El tiempo de espera hasta la fijación de un alelo aumenta con el tamaño de la población.
La probabilidad de fijación de un alelo es igual a su frecuencia en ese momento.

## Efecto fundador

Si queremos observar deriva genética en la naturaleza, el mejor sitio donde buscarla es
en las poblaciones pequeñas. Las poblaciones son a menudo pequeñas cuando se acaban de fundar por un pequeño grupo de individuos, que se han desplazado, o han sido desplazados, a una nueva localidad. Las frecuencias alélicas en la nueva población son, probablemente, diferentes de las de la población de origen, simplemente por azar. A esto se denomina efecto fundador.

> [!tip] Rasgo diferencial del efecto fundador
> **El efecto fundador es el resultado directo del error de muestreo.**

Por ejemplo, si en una población continental de insectos hay 25 alelos diferentes en un locus, pero en un madero de una balsa que llega a una remota isla sólo se encuentran 10 individuos, hay una probabilidad cero de que la nueva población de la isla tenga todos los alelos presentes en el continente. Si por azar, algunos de los individuos fundadores son homozigotos, las frecuencias alélicas de la nueva población se diferenciarán incluso mucho más. En cualquier suceso fundador, es casi seguro que se producirá algún grado de diferenciación genética aleatoria entre las poblaciones nueva y vieja. En otras palabras, la fundación de una población por un pequeño grupo de individuos representa típicamente no solo el establecimiento de una nueva población sino también la evolución instantánea de diferencias entre la nueva y la vieja población.

> [!NOTE] Efecto fundador
> Es un fenómeno de genética de poblaciones que ocurre cuando una **pequeña parte de una población se separa y forma una nueva población**. Debido a que los fundadores representan solo una **muestra limitada de la variabilidad genética original**, la nueva población puede tener **frecuencias alélicas muy diferentes** de la población original y menor diversidad genética, lo que puede aumentar el efecto de la deriva genética y fijar alelos raros o incluso deletéreos


> [!EXAMPLE] Ejemplos del efecto fundador en humanos I
> la población Amish de Pensilvania oriental desciende de un grupo de unos 200 colonos europeos que llegaron a los Estados Unidos en el siglo XVIII. Uno de los fundadores, bien el marido o la esposa (o ambos) de un matrimonio llamado King,
fue portador del síndrome de Ellis-van Creveld. El síndrome de Ellis-van Creveld es una forma rara de enanismo ocasionada por un alelo recesivo en el cromosoma 4 (Bodmer and McKie 1995). La frecuencia de este alelo en la mayoría de las poblaciones se encuentra alrededor de 0,001, pero en la actualidad, en los Amish es alrededor de 0,07 (Postlethwait and Hopson 1992). La elevada frecuencia del alelo en la población Amish, probablemente no se debe a ninguna ventaja selectiva conferida por el alelo en heterozigosis u homozigosis. Más bien, la elevada frecuencia del alelo se debe al azar. El alelo se encontraba en frecuencia elevada en la pequeña población de fundadores y ha continuado oscilando hacia arriba en las generaciones siguientes. En la sección siguiente consideraremos con detalle el efecto acumulativo de la deriva genética en el curso de muchas generaciones


> [!EXAMPLE] Ejemplos del efecto fundador en humanos II
>Una alta frecuencia de la enfermedad de Huntington entre los afrikaans, colonos holandeses que llegaron por primera vez al Cabo de Buena Esperanza (1652-1795).
Altas frecuencias de polidactilia (síndrome de Ellis-van Creveld) y enfermedad de la orina con olor a jarabe de arce (MSUD) entre los menonitas amish que emigraron a Pensilvania en el siglo XVIII desde el Palatinado (Alemania).
Una alta frecuencia de deficiencia de fumarasa entre los mormones (Iglesia de Jesucristo de los Santos de los Últimos Días), una comunidad que practica tanto la endogamia como la poliginia. Entre el 75 y el 80 % de la comunidad son parientes consanguíneos de solo dos hombres, los fundadores John Y. Barlow y Joseph Smith Jessop.
Una frecuencia 10 veces mayor de retinosis pigmentaria entre 264 descendientes de 15 colonos británicos que fundaron en 1815 un asentamiento en la isla de Tristán da Cunha, en el océano Atlántico Sur



> [!NOTE] Cuello de botella
> Es un fenómeno de genética de poblaciones que ocurre cuando una población **sufre una drástica reducción de tamaño** debido a eventos como desastres naturales, enfermedades o caza excesiva. Durante este periodo, la **diversidad genética se reduce** porque solo sobreviven unos pocos individuos, y las frecuencias alélicas pueden cambiar por azar. Cuando la población se recupera, su variabilidad genética es mucho menor que antes, lo que aumenta la influencia de la **deriva genética** y puede fijar alelos raros o deletéreos

## Tamaño efectivo poblacional

Sewall Wright (1931) introdujo el concepto de tamaño efectivo de la población, que definió rigurosamente como el tamaño de una población idealizada que tendría el mismo efecto del muestreo aleatorio sobre las frecuencias alélicas que el de la población real.

Tamaño real o censal (N): número de individuos en una población (recuento).

Tamaño efectivo (N): tamaño de una población ideal (según el modelo de Wright-Fisher) que experimenta la misma cantidad de deriva que la población real.

La cantidad de deriva se puede medir por:

- El cambio en las frecuencias alélicas entre generaciones.
- La tasa de pérdida de heterocigosidad.

La definición de tamaño efectivo puede parecer circular (usamos la cantidad de deriva para definir un parámetro que permite cuantificar la deriva...). Sin embargo, hay expresiones para Ne que no dependen de la deriva. 

Ne se puede derivar utilizando la definición de autocigosidad:
$$
1-F_{t}=(1-F_{0})\left( 1-\frac{1}{2N_{e}} \right)^{t}
$$

Siendo N1, N2,…, Ni,…, Nt los tamaños de población en cada generación. Pero comúnmente se utiliza la siguiente expresión:
$$
N_{e}= \frac{t}{\frac{\sum^{t}_{i=1}}{N_{i}}}
$$
Ne es la media armónica de los tamaños de población.

Las fluctuaciones en el tamaño de la población son universales y especialmente relevantes en:
- Genética de la conservación (leones marinos, guepardos,...)
- Evolución humana
- Patógenos (las infecciones iniciales representan una reducción drástica del tamaño de la población).

### Ne con números desigual de machos y hembras

El aumento de F en cada generación en una población con Fo = 0 es 1/2N.
Si consideramos machos y hembras por separado, la probabilidad de que las dos copias de un gen en un individuo deriven del mismo progenitor es nula.
Bajo panmixis, la probabilidad de que los dos abuelos de un individuo sean iguales es 1/Nm (la inversa del número de machos).
Si este es el caso, la probabilidad de recibir los dos gametos del mismo abuelo es 1/8.
El mismo razonamiento se aplica a las abuelas (1/N, siendo el número de hembras).
Por lo tanto,
$$
N_{e}=\frac{4N_{m}N_{f}}{N_{m}+N_{f}}
$$


## Fijación al azar de alelos y pérdida de heterozigosidad

La deriva es incluso un mecanismo evolutivo más poderoso cuando sus efectos abarcan a muchas generaciones. 
Podemos investigar los efectos acumulativos de la deriva genética con el mismo modelo físico que utilizamos antes:
una bolsa con alubias negras y blancas. De nuevo, iniciemos la bolsa con 60 alubias negras y 40 blancas, que representa un conjunto de genes en el que los alelos A1 y A2 se encuentran en las frecuencias de 0,6 y 0,4. A los padres que dan lugar a este conjunto de genes los llamaremos generación cero. Como hicimos antes, extraemos alubias de la bolsa para simular la producción de diez zigotos por apareamiento al azar. En ese momento, las frecuencias alélicas entre los zigotos recién formados resultó ser 0,5 para A1 y 0,5 para A2. Llamamos a estos zigotos generación uno.

Para continuar la simulación en otra generación, necesitamos iniciar una nueva bolsa
con 50 alubias negras y 50 alubias blancas, que representa el conjunto de genes de la generación uno. Extrayendo alubias de este conjunto de genes, obtenemos los zigotos de la generación dos. Resulta que las frecuencias alélicas de la generación dos fueron 0,4 para A1 y 0,6 para A2.

Iniciamos ahora una bolsa con 40 alubias negras y 60 blancas y formamos zigotos para obtener la generación tres. Las frecuencias alélicas en la generación tres son 0,45 para A1 y 0,55 para A2.
Ahora necesitamos una bolsa con 45 alubias negras y 55 blancas, y así sucesivamente.
La ventaja de utilizar un computador para simular la extracción de las alubias queda clara enseguida.
Los gráficos (a), (b) y (c) de la Figura 6.13 muestran los resultados de 100 generacio-
nes sucesivas de deriva genética en poblaciones simuladas de tamaños distintos. En cada gráfica se representan las frecuencias alélicas de ocho poblaciones. Cada población comienza con las frecuencias alélicas de 0,5 para A1 y de 0,5 para A2. Las poblaciones representadas en la gráfica (a) tienen exactamente cuatro individuos cada una, las poblaciones representadas en la gráfica (b) tienen 40 individuos y las poblaciones de la gráfica (c) tienen 400 individuos.

> [!SUCCESS] Segundas conclusiones de la deriva genética
> Debido a que las fluctuaciones de las frecuencia alélica de una generación a la siguiente están ocasionadas por el error de muestreo al azar, cada población sigue un camino evolutivo único.
> La deriva genética tiene un efecto más rápido y drástico sobre las frecuencias alélicas en las poblaciones pequeñas que en las poblaciones grandes.
> Dado un tiempo suficiente, la deriva genética puede dar lugar a cambios sustanciales en las frecuencias alélicas,  incluso en poblaciones que sean bastantes grandes.

Advierta que si la deriva genética es la única fuerza evolutiva que actúa en la población (si no hay selección, ni mutación, ni migración) entonces el error de muestreo hace que las frecuencias alélicas oscilen entre 0 y 1. Esta oscilación es particularmente aparente en las poblaciones cuya evolución se destaca en el gráfico de la Figura 6.13b. Durante las primeras 25 generaciones la frecuencia del alelo A1 aumenta de 0,5 a más de 0,9. Entre las generaciones 25 y 40 baja a 0,5. Entre las generaciones 40 y 80 la frecuencia oscila entre 0,5 y 0,8. Luego la frecuencia de A1 disminuye rápidamente, de tal manera que hacia la generación 85 A1 alcanza cero y por consiguiente desaparece de la población. La oscilación de las frecuencias alélicas da lugar a dos efectos relacionados importantes: (1) el que los alelos derivan finalmente hacia la fijación o hacia la pérdida, y (2) que la frecuencia de los heterozigotos disminuye.

### Fijación al azar de alelos

Como la frecuencia de cualquier alelo oscila entre 0 y 1, tarde o temprano el alelo encontrará un destino inevitable: su frecuencia alcanzará un extremo u otro. Si la frecuencia del alelo llega a 0, entonces el alelo se perderá para siempre (suponiendo que la mutación o la migración no lo reintroduzcan). Si la frecuencia del alelo alcanza 1, entonces se dice que el alelo se ha fijado, también para siempre. Entre las ocho poblaciones representadas en la Figura 6.13a, el alelo A1 se fija por deriva en cinco y se pierde en tres. Entre las ocho poblaciones representadas en la Figura 6.13b, el alelo A1 se fija por deriva en una y se pierde en tres. Es sólo cuestión de tiempo que el alelo A1 quede también fijado o perdido en las otras poblaciones. A medida que algunos alelos se fijan y otros se pierden por deriva, la variabilidad alélica de cada población disminuye.
Imaginemos ahora una población finita en la que hay varios alelos presentes en un locus dado: *A1, A2, A3, A4*, y así sucesivamente. Si la deriva genética es el único mecanismo evolutivo que actúa, entonces finalmente uno de los alelos se fijará por deriva. En el mismo momento en que un alelo quede fijado, los otros alelos se perderán.

Nos gustaría poder predecir qué destino alcanzará cada alelo. No podemos hacerlo con certeza, pero podemos dar probabilidades. Sewall Wright (1931) demostró que la probabilidad de que cualquier alelo de una población sea el que se fije por deriva es igual a la frecuencia inicial de dicho alelo (véase el Cuadro 6.3). Por ejemplo, si comenzamos con una población finita en la que A1, tiene una frecuencia de 0,73 y A2 una frecuencia de 0,27, hay un 73% de probabilidad de que el alelo que se fije por deriva sea el A1.

### Pérdida de heterozigosidad

En una población finita, a medida que las frecuencias de los alelos se fija o se pierde por deriva, la frecuencia de los heterozigotos en la población disminuye. Los gráficos (d), (e) y (f) de la figura 6.13 muestran la disminución de la frecuencia de los heterozigotos en nuestras poblaciones simuladas.
Para ver por qué la frecuencia de los heterozigotos disminuye, observe primero el inserto del gráfico (d). En el inserto se representa la frecuencia de los heterozigotos, calculada como 2(p)(1-p), en una población con apareamiento al azar en función de *p*, que es la frecuencia del alelo *A1*. La frecuencia de los heterozigotos tiene su valor más alto, 0'5. Como la frecuencia de *A1* disminuye hacia 0 ó aumenta hacia 1, la frecuencia de heterozigotos disminuirá. Y, desde luego, si la frecuencia de *A1* alcanza 0 ó 1, la frecuencia de heterozigotos caerá hasta 0.


Miremos ahora los gráficos (a), (b) y (c). En cualquier generación, la frecuencia de A1
puede desplazarse hacia o lejos de 0,5 en una población dada (siempre y cuando A1 no se haya fijado o perdido). Así, la frecuencia de los heterozigotos de cualquier población puede aumentar o disminuir. Sin embargo, la tendencia global, en el conjunto de las poblaciones, es que las frecuencias alélicas se alejen por deriva de valores intermedios y hacia 0 ó 1. Por ello, la frecuencia promedio de los heterozigotos, en el conjunto de las poblaciones, tenderá a disminuir. Miremos ahora a los gráficos (d), (e) y (f). La línea gruesa azul de cada gráfico representa la frecuencia promedio de los heterozigotos a lo largo de las ocho poblaciones en cuestión. La frecuencia de los heterozigotos realmente tiende a disminuir, rápidamente en poblaciones pequeñas y lentamente en poblaciones grandes.
Finalmente, uno u otro alelo quedará fijado en cada población y la frecuencia promedio
de los heterozigotos caerá hasta 0.
**La frecuencia de los heterozigotos de una población se denomina a veces como la heterozigosidad poblacional.** Nos gustaría poder predecir lo rápido que puede esperarse que disminuya la heterozigosidad en poblaciones finitas. Sewall Wright (1931) demostró que, promediando muchas poblaciones, la frecuencia de los heterozigotos obedece a la relación

$$
H_{g+1}=H_{g}\left[ 1-\frac{1}{2N} \right]
$$

$$
\begin{align}
H_{g+1}=\text{es la heterozigosidad de la siguiente generación} \\
H_{g}=\text{heterozigosidad actual} \\
N=\text{número de individuos de la población→(0'5-1)}
\end{align}
$$
Por lo que la frecuencia esperada  de heterozigotos de la generación siguiente  es siempre menor que la frecuencia de heterozigotos en la generación anterior. Las curvas grisas de la figura 6.13d,(e) y (f) muestran la disminución de la heterozigotos pronosticada en la ecuación de Wright.

Para apreciar una de las implicaciones de la inevitable pérdida de heterozigosidad en
las poblaciones finitas, imagine que es el responsable de la gestión de una población cautiva de una especie en peligro de extinción. Suponga que hay exactamente 50 adultos reproductores en los zoológicos de todo el mundo. Aunque pudiera disponer del traslado de los adultos o del semen para llevar a cabo un apareamiento aleatorio, todavía apreciaría una pérdida de heterozigosidad del 1% por generación debido a la deriva genética.
## Estudio experimental de la fijación o pérdida aleatoria de heterozigosidad

Peter Buri (1956) estudió este fenómeno experimentalmente, en poblaciones pequeñas de laboratorio de la mosca de la fruta Drosophila melanogaster. Adoptando un esquema que había sido utilizado por Kerr y Wright (1954), Buri fundó 107 poblaciones de moscas, cada una de ellas a partir de ocho hembras y ocho machos.Todas las moscas fundadoras eran heterozigóticas para alelos de un gen para el color de los ojos llamado “brown”.Todas las moscas tenían el mismo genotipo: bw75/bw. Así, en las 107 poblaciones, la frecuencia inicial del alelo bw75 fue de 0,5. Buri mantuvo estas poblaciones durante 19 generaciones. En cada población y en cada generación, Buri mantuvo el tamaño poblacional en 16, extrayendo ocho hembras y ocho machos al azar como padres de la generación siguiente.
¿Qué resultados esperaríamos? Si ninguno de los dos alelos, bw75 y bw, confiere ventaja selectiva, entonces esperaríamos que la frecuencia del alelo bw75 oscilara al azar por deriva genética en cada generación. Diecinueve generaciones serían suficientes, en poblaciones con 16 individuos, para que muchas poblaciones quedaran fijadas para uno u otro alelo.

Debido a que el alelo bw75 tiene una frecuencia inicial de 0,5 esperaríamos que este alelo se perdiera tan a menudo como se fijase.A medida que el alelo bw75 se fija o se pierde por deriva en cada población, esperaríamos la disminución de la heterozigosidad en el conjunto de las poblaciones. La tasa de disminución de la heterozigosidad seguirá la ecuación de Wright, dada en la sección anterior.
Los resultados de Buri confirman estas predicciones. Cada uno de los pequeños gráficos de la Figura 6.14 son histogramas que resumen las frecuencias alélicas de las 107 poblaciones en una generación concreta. El eje horizontal representa la frecuencia del alelo bw75, y el eje vertical representa el número de poblaciones en cada una de las frecuencias.

La frecuencia del alelo bw75 era 0,5 en la generación cero de todas las poblaciones, que no se muestran en la figura. Después de una generación de deriva genética, muchas poblaciones todavía presentan una frecuencia cercana a 0,5, aunque una de las poblaciones tenía una frecuencia alélica de 0,22 y otra de 0,69.A medida que la frecuencia del alelo bw75 aumenta en unas poblaciones y disminuye en otras, la distribución de las frecuencias alélicas se ensancha rápidamente. En la generación cuarta, la frecuencia de bw75 alcanza 1 por primera vez en una población. En la generación sexta la frecuencia de bw75 alcanza 0 por primera vez en una población.A medida que la frecuencia alcanza 0 ó 1 en más y más poblaciones, la distribución de las frecuencias adquiere una forma en U. Hacia el final del experimento, bw75 se había perdido en 30 poblaciones y se había fijado en 28.

**La proporción 30:28 de pérdida y fijaciones está muy próxima a la proporción 1:1 que habíamos predicho con deriva genética**. Durante el experimento de Buri, hubo una evolución espectacular en casi todas las 107 poblaciones de moscas de la fruta, pero la selección natural no tuvo nada que ver con esto.
Las propiedades genéticas del locus “brown” eran tales que Buri podía identificar a los
tres genotipos por sus fenotipos. Así pudo comprobar directamente la frecuencia de los
heterozigotos de cada población. La frecuencia de los heterozigotos en la generación cero fue 1, por lo que la heterozigosidad en la generación uno fue 0,5. A partir de ese momento, Buri anotó en cada generación la frecuencia de los heterozigotos de cada población, obteniendo posteriormente la heterozigosidad media de las 107 poblaciones. En la Figura 6.15 se representan estos valores de heterozigosidad media a lo largo de las 19 generaciones del experimento. Observe primero los puntos rojos que representan los datos reales. De acuerdo con nuestras predicciones teóricas, la frecuencia promedio de los heterozigotos disminuye lentamente.
Sin embargo, la concordancia entre la teoría y los resultados no es perfecta. La curva
gris a trazos de la figura muestra la disminución en heterozigosidad pronosticada, utilizando la ecuación de Wright y una población de tamaño 16. La disminución real en heterozigosidad fue más rápida de lo esperado. La curva gris continua muestra la disminución pronosticada para una población de tamaño 9; encaja bien con los datos. 

Las poblaciones de Buri pierden heterozigosidad como si tuvieran sólo 9 individuos en lugar de 16. En otras palabras, el tamaño poblacional efectivo del experimento de Buri fue 9 (véase el Cuadro 6.4). Una de las explicaciones es que alguna de las moscas de cada población pudo haber muerto por accidente antes de reproducirse, o las hembras pudieron rechazar a algunos machos como pareja.
![[Pasted image 20260109163414.png]]


> [!SUCCESS] Conclusiones del experimento de Buri
> Demuestra que la teoría de la deriva genética nos permite hacer predicciones cualitativamente exactas y predicciones cuantitativas razonablemente exactas, acerca del comportamiento de los alelos en poblaciones finitas, al menos en el laboratorio. En la sección siguiente consideraremos pruebas sobre la fijación al azar de alelos y pérdida de heterozigosidad en poblaciones naturales.

## Fijación o pérdida aleatoria de heterozigosidad en poblaciones naturales

Alan Templeton y sus colegas (1990) comprobaron las predicciones acerca de la fijación al azar de alelos analizando los resultados de un experimento natural en las montañas de Ozark de Missouri. Aunque cubiertas en la actualidad por un bosque de enzimas y nogales, la región de los Ozarks fue parte de un desierto durante un extenso período de clima cálido y seco que abarcó entre hace 8000 años hasta hace 4000 años. El desierto que engulló a los Ozark estaba junto al desierto de Norteamérica. Muchas especies del desierto del sudoeste ampliaron su distribución hacia el este en los Ozarks. Entre éstas se encuentra la lajartija con collar se retrajp de nuevo hacia el oeste y el bosque de encinas y nogales volvió a invadir los Ozarks. Sin embargo, en este bosque, en afloramientos recosos, hay pequeños restos de hábitat desértico llamados claros. Viviendo en algunos de estos claros hay poblaciones reliquia de lajartijas con collar. La mayoría de las poblaciones están lo suficientemente aisladas entre sí que hay poco o ningún flujo génico entre ellas. Las poblaciones reliquia son pequeñas; la mayoría tienen no más de unas docenas de individuos. Debido al pequeño tamaño de las poblaciones de los claros, Templeton y sus colegas predijeron que las lajartijas con collar de los Ozarks presentarían fuertes huellas de deriva genética. En cada población, la mayoría de los loci se habrían fijado para un solo alelo y la variación genética sería muy baja. Sin embargo, qué alelo se hubiera fijado en cada población en concreto sería una cuestión de azar, por lo que habría una considerable diversidad genética entre poblaciones.
Templeton y sus colegas analizaron la variabilidad genética de varias  poblaciones de los claros. Los investigadores examinaron los genotipos de las lajartijas de una serie de loci enzimáticos, de sus genotipos del DNA ribosómico y de sus genotipos de DNA mitocondrial. Entre las lajartijas identificaron 7 genotipos multilocus distintos. Confirmando las consecuencias pronosticadas por el aislamiento y por el pequeño tamaño poblacional, la mayoría de las poblaciones de los claros estaban fijadas para un único genotipo multilocus, con genotipos diferentes fijados en distintas poblaciones.

Andrew Young y sus colegas comprobaron las predicciones acerca del efecto del tamaño poblacional sobre la heterozigosidad con un estudio comparativo en plantas. Los investigadores reunieron datos de la bibliografía y representaron dos medidas de la diversidad genética global frente al tamaño poblacional en tres fanerógamas herbáceas y un árbol. La primera medida de variación genética fue de polimorfismo genético, el porcentaje de loci del genoma que tienen al menos dos alelos con frecuencia superior a 0'01. La segunda fue la riqueza de alelos, el número medio de alelos por locus. Ambas medidas están relacionadas con la heterozigosidad. Si un locus dado tiene más de un alelo, y si un sustancia número de individuos de la población son heterozigotos, entonces el locus contribuye mucho al polimorfismo y a la riqueza alélica. Por el contrario, si el locus está fijado para un único alelo y en la población no hay heterozigotos, entonces el locus empobrece el polimorfismo  poblacional y la riqueza alélica. Debido a  que la  deriva genética es más pronunciada en las poblaciones pequeñas que en las grandes y debido a que da lugar a la pérdida de heterozigosidad, Young y sus colegas predijeron que las poblaciones pequeñas tendrían un menor nivel de polimorfismo y de riqueza alélica. Las representaciones  de Young *ed al.* aparecen en la figura 6.17. De acuerdo con sus predicciones, en casi todos los casos las poblaciones pequeñas albergan realmente menos diversidad genética.

> [!SUCCESS] Conclusiones de Templeton
> Probó que, al menos en algunas poblaciones naturales, la deriva genética da lugar, de acuerdo con lo predicho, a fijación al azar y a reducción de heterozigosidad. La pérdida de diversidad genética en poblaciones pequeñas es de particular interés para los biólogos conservacionistas por dos razones. 
> **Primero,** la diversidad genética es la materia primera para la evolución adaptativa. Suponga una especie reducida a unas pocas poblaciones remanentes por destrucción del hábitat o por algún otro cambio ambiental.
La deriva genética puede derivar a las poblaciones remanentes de su potencial para evolucionar en respuesta a un cambio ambiental, precisamente en los momentos en que el ambiente cambie más drasticamente. 
**Segundo**, la pérdida de heterozigosidad conlleva un aumento de la homozigosidad. Un aumento en homozigosidad  conduce a menudo a una eficacia menor en poblaciones experimentales. 


![[Pasted image 20251116203300.png]]
## La tasa de evolución por deriva genética

La teoría y los experimentos que hemos discutido en esta sección establecen que el error de muestro puede ser un mecanismo importante de evolución. El último aspecto de  la deriva que consideraremos aquí es la tasa de evolución cuando la deriva genética es la única fuerza que actúa.

Primero, necesitamos definir qué significa la tasa de evolución en un locus dado. Definiremos **la tasa de evolución como la tasa a la que los nuevos  alelos originados por mutación son sustituidos por otros alelos ya presentes.** En la figura 6.18 se ilustra el proceso de sustitución y se distingue la sustitución de la mutación. La figura muestra un conjunto de genes de 10 alelos durante 20 generaciones. Inicialmente todos los alelos son idénticos (círculos blancos). En la cuarte generación aparece un nuevo alelo (círculo naranja blancos). En la cuarta generación aparece un nuevo alelo (círculo naranja claro) por la mutación de uno de los alelos originales. Durante varias generaciones este alelo fluctúa hacia una frecuencia elevada. En la generación quince aparece un segundo alelo nuevo (círculo azul), originado por la mutación de un descendiente del primer alelo naranja claro. En la generación 19 se pierde el último de  los alelos blancos. En este punto podemos decir que el alelo blanco ha sustituido por el alelo naranja claro. Así pues, por sustitución evolutiva queremos indicar la fijación de una mutación nueva con o sin cambio mutacional adicional.

Cuando el único mecanismo evolutivo que actúa es la deriva genética, la tasa de sustitución es simplemente igual a la tasa de mutación nueva con o sin cambio mutacional adicional.
Cuando el único mecanismo evolutivo que actúa es la deriva genética, la tasa de sustitución es simplemente igual a la tasa de mutación. Esto es así independientemente del tamaño poblacional, ya que los dos efectos asociados con el tamaño poblacional se cancelan entre sí: en poblaciones grandes se producen más mutaciones, pero en una población grande cada nueva mutación tiene una menor probabilidad de fijarse por deriva. Con deriva genética las poblaciones grandes generan y mantienen más variación genética que las poblaciones pequeñas, pero todas las poblaciones, independientemente de su tamaño, acumulan sustituciones al mismo ritmo.

Por supuesto, a menudo están actuando otros mecanismos evolutivos distintos de la deriva. Podemos permitir algo de selección natural nuestro modelo y obtener todavía resultados similares. Imaginemos que algunas mutaciones son deletéreas mientras que otras selectivamente neutras. Las mutaciones deletéreas serán eliminadas por selección natural y nunca podrán fijarse. La tasa de sustitución será entonces igual a la tasa a la que se producen las mutaciones neutras.

Los biólogos evolutivos están divididos por la revelancia de estos cálculos en las poblaciones reales. Todos están de acuerdo en que se ha omitido un tipo de mutación y un tipo de selección. Algunas mutaciones son ventejosas selectivamente y se han fijado por selección natural con mayor seguridad y mucho más rápidamente que nunca lo hubieran hecho por deriva. Sin embargo, los biólogos evolutivos piensan de dos maneras sobre la frecuencia con la que sucede esto.

Los que apoyan la **teoría neutralista**, largo tiempo liderada por Motoo Kimura
(1983), mantienen que las mutaciones ventajosas son muy raras y que la mayor parte de los alelos de la mayoría de los genes son selectivamente neutros. Los neutralistas predicen que para la mayoría de los genes en la mayoría de las poblaciones, la tasa de evolución será realmente igual a la tasa de mutación neutra.

Los que apoyan la **teoría seleccionista**, principalmente liderada por John Gillespie
(1991), mantienen que las mutaciones ventajosas son lo bastante corrientes como para que puedan ignorarse. Los seleccionistas predicen que para muchos genes en la mayoría de las poblaciones, la tasa de sustitución reflejará la acción de la selección natural sobre las mutaciones ventajosas.

En resumen, la deriva genética no es un mecanismo adaptativo de evolución. Simplemente, como consecuencia del error de muestreo, las frecuencias alélicas pueden cambiar de una generación a la siguiente. La deriva genética es muy potente en poblaciones pequeñas y cuando actúa sobre muchas generaciones. Finalmente, la deriva genética da lugar a la fijación de algunos alelos y a que otros se pierdan, y a una disminución global de la diversidad genética.


> [!SUCCESS] Conclusiones de la deriva genética
> La deriva genética ocurre en todas las poblaciones y sus efectos son más intensos  cuanto menor es el tamaño de la población.
La fijación (y pérdida) de alelos es una consecuencia necesaria de la deriva genética, y el tiempo que tarda en producirse depende del tamaño de la población.
La probabilidad de fijación de un alelo por deriva es igual a su frecuencia.
La deriva genética conduce a un aumento de la homocigosis.
Los modelos de deriva genética se basan en las poblaciones ideales de Wright-Fisher, pero pueden aplicarse a poblaciones reales si se reemplaza el tamaño censal por el tamaño efectivo.
Existen varias expresiones para calcular el tamaño efectivo de una población.
La endogamia puede tratarse matemáticamente como deriva genética, ya que ambas generan homocigosis mediante autozigosis.

---
# La mutación como fuerza evolutiva

Por si misma la mutación, no es en general un mecanismo evolutivo potente. Para ver el porqué, volvamos a nuestro modelo de la población de ratones. Imaginemos un locus con 2 alelos, *A* y *a* , con frecuencia iniciales de 0,9 y 0,1. *A* es el alelo de tipo silvestre y *a* es una mutación recesiva de pérdida de función. Además, imaginemos que las copias de *A* se convierten por mutación en copias nuevas de *a*, a un ritmo de 1 copia cada 10.000 por generación. Ésta es una tasa de mutación muy elevada, pero se encuentra en el rango de tasas de mutación conocidas. Las mutaciones retrógadas, que restauran la función, por lo que ignoraremos las mutaciones que convierten en copias de *a* en *A*. Finalmente imaginemos que todas las mutaciones ocurren cuando los gametos se encuentran en el conjunto de genes.

En la figura 5.22 sigue las frecuencias genotípicas y alélicas desde los adultos de una generación a través del conjunto de genes hasta los zigotos de la generación siguiente. Los genotipos de los adultos se encuentran en las proporciones de HW.


| AA   | Aa   | aa   |
| ---- | ---- | ---- |
| 0,81 | 0,18 | 0,01 |
Cuando los adultos producen gametos, las frecuencias alélicas en el conjunto de genes son los siguientes:


| A   | a   |
| --- | --- |
| 0'9 | 0'1 |
Ahora, una de cada 10.000 mil copias del alelo *A* se convierte en una copia del alelo *a*. La nueva frecuencia de *A* se obtiene a partir de la frecuencia anterior menos la fracción que se pierde por mutación; la nueva frecuencia de *a* resulta de la frecuencia anterior más la fracción que se gana por mutación. Es decir,


| A                          | a                         |
| -------------------------- | ------------------------- |
| 0'9-(0'0001)(0'9)=0'899991 | 0'1+(0'0001)(0'9)=0'10009 |
Finalmente, cuando los gametos se combinan al azar para producir los zigotos; los genotipos tipos zigotos se encontrarán en las nuevas proporciones de HW.

| AA      | Aa      | aa      |
| ------- | ------- | ------- |
| 0'80984 | 0'18014 | 0'01002 |
Advierta que las nuevas frecuencias alélicas y genotípicas son casi idénticas a las anteriores. Como fuerza evolutiva, la mutación no tiene prácticamente efecto.
¿Podría la mutación de *A* hacia *a*, dándose a un ritmo de 1 copia cada 10.000 en cada generación durante muchas generaciones, dar lugar finalmente a un cambio apreciable en las frecuencias alélicas? El gráfico de la figura 5.23 nos proporciona la respuesta. Después de mil generaciones, la frecuencia del alelo *A* de nuestra población ideal será alrededor de 0'81. La mutación puede dar lugar a cambios sustanciales en las frecuencias alélicas, pero lo hace muy lentamente.


> [!SUCCEsS] Primeras conclusiones de la mutación como fuerza evolutiva
> La mutación por si sola es una fuerza evolutiva débil. Sin embargo, la mutación proporciona la variación genética que es la materia prima de la evolución. En algunos casos la aparición constante de nuevos alelos mutantes puede equilibrarse por la selección en contra de esos mismos alelos, y por consiguiente actuar manteniendo a las frecuencias alélicas en equilibrio.


## Fórmulas 
Incluso para tasas de mutación relativamente altas, generalmente se piensa que la mutación es un proceso evolutivo más lento que el resto.

![[Pasted image 20260109154344.png]]
## Mutagenesis letal

El aumento de la tasa de mutación por encima de cierto umbral puede provocar la extinción de una población.
Cuanto mayor sea la tasa de mutación espontánea de un organismo, más cerca estará del umbral de extinción.
Los virus de ARN son muy susceptibles a la mutagénesis letal.

---
# Equilibrio mutación-selección

La selección actúa eliminando mutaciones deletéreas. Sin embargo, los alelos deletéreos perduran porque se están originando de nuevo continuamente. Cuando la tasa de a la que las copias de un alelo deletéreo ésta siendo eliminada por selección es exactamente igual a la tasa de aparición de nuevos alelos por mutación, la frecuencia del alelo se encontrará en equilibrio. La situación se denomina **equilibrio mutación-selección**.

¿Cuál es la frecuencia en el equilibrio de un alelo deletéreo? Si el alelo es recesivo, su frecuencia de equilibrio, q^, será

$$
\hat{q} = \sqrt{ \frac{\mu}{s} }
$$

en donde *mu* es la tasa de mutación y *s* el coeficiente de selección, un número entre 0 y 1 que expresa la fuerza de la selección contra el alelo. Esta ecuación capta con economía lo que la intuición nos dice acerca del equilibrio mutación-selección. 
Si el coeficiente de selección es pequeño y la tasa de mutación es elevada, entonces la frecuencia del alelo en el equilibrio será relativamente elevada. Si el coeficiente de selección es grande y la tasa de mutación baja, entonces la frecuencia del alelo en el equilibrio será baja.

![[Pasted image 20260109160501.png]]
## Enfermedades recesivas letales o subletales en humanos

### Atrofia muscular espinal

La investigación de Brunhilde Wirth y sus colegas (1997) en pacientes con atrofia muscular espinosa proporciona un ejemplo. La atrofia muscular espinosa es una enfermedad neurodegenerativa que se caracteriza por la debilidad y desgaste de los músculos que controlan los movimientos voluntarios. Se produce por deleciones en un locus del cromosoma 5 llamado el gen de la supervivencia telomérica de la neurona motora (telSMN). En algunos casos la enfermedad puede agravarse por otras mutaciones en un gen cercano. La atrofia muscular espinosa es, después de la fibrosis quística, la segunda enfermedad autosómica recesiva letal más común en la raza blanca (McKusick et al. 1999).

En conjunto, los alelos de pérdida de función del telSMN tienen una frecuencia alrededor de 0,01 en poblaciones blancas.Wirth y sus colegas estiman que el coeficiente de selección es alrededor de 0,9. Con tan fuerte selección en contra, esperaríamos que los alelos que causan la enfermedad desaparecieran de la población lenta, pero inexorablemente. Entonces, ¿por qué persisten a una frecuencia del 1 por 100?
Una posibilidad es que los alelos para la enfermedad se estén manteniendo en la población por el equilibrio entre la mutación y la selección. Si sustituimos la frecuencia alélica y el coeficiente de selección por q^ y s en la ecuación de la página 145 y despejamos μ, encontramos que este escenario requiere de una tasa de mutación de
0,9  10–4 mutaciones del alelo telSMN por generación.Wirth et al. analizaron los cromosomas de 340 individuos con atrofia muscular espinosa y los cromosomas de sus
padres y de otros miembros de la familia. Encontraron que 7 de los 340 individuos afectados llevaban una mutación nueva que no se encontraba en ninguno de sus padres. Este dato permitió a los científicos estimar directamente la tasa de mutación del locus telSMN (véase el Cuadro 5.11). Su estima fue de 1,1  10–4. Esta medida directa de la tasa de mutación está bastante de acuerdo con la tasa pronosticada de acuerdo con la hipótesis del equilibrio mutación-selección.Wirth et al. concluyeron que el equilibrio mutación-selección proporciona una explicación suficiente de la persistencia de los alelos para la atrofia muscular espinosa.

**Los alelos que dan lugar a la fibrosis quística, ¿se mantienen por el equilibrio entre la mutación y la selección?

La fibrosis quística está ocasionada por mutaciones recesivas de pérdida de función en un locus del cromosoma 7, que codifica a una proteína llamada el regulador de la conductancia transmembrana de la fibrosis quística (CFTR). La CFTR es una proteína de la superficie celular que se expresa en el mucus de la membrana que tapiza los intestinos y pulmones. Gerald Pier y sus colegas (1997) demostraron que una de las funciones clave de la CFTR es capacitar a las células de la superficie pulmonar a ingerir y destruir a la bacteria Pseudomonas aeruginosa. Estas bacterias dan lugar a infecciones pulmonares crónicas en individuos con fibrosis quística, lo que finalmente provoca graves daños en el pulmón (Figura 5.25). La selección en contra de los alelos que dan lugar a la fibrosis quística parece que es muy fuerte. Hasta hace poco, muy pocos individuos afectados sobrevivían hasta la pubertad; aquellos que sobrevivían eran a menudo estériles. No obstante, los alelos que dan lugar a la fibrosis quística tienen una frecuencia conjunta aproximadamente de 0,02 entre personas con antecedentes europeos.
Los alelos de la fibrosis quística, ¿podrían mantenerse en una frecuencia de 0,02 por
el equilibrio mutación-selección? Si asumimos un coeficiente de selección de 1 y utilizamos la ecuación deducida en el cuadro 5.10, la tasa de mutación para dar lugar a
nuevos alelos debería ser de 4  10–4. La tasa real de mutación de alelos de la fibrosis
quística parece ser considerablemente menor: aproximadamente 6,7  10–7 (véase el
Cuadro 5.11). Podemos concluir que el suministro estable por nuevas mutaciones no
puede, por si mismo, explicar el mantenimiento de los alelos de la fibrosis quística en una frecuencia del 0,02.

Nuestra discusión sobre la superioridad de los heterozigotos sugiere una explicación
alternativa (Figura 5.16 y Cuadro 5.8). Quizá el coste en eficacia que sufren los alelos de la fibrosis quística cuando se encuentran en homozigosis viene equilibrado por la ventaja en eficacia que tienen cuando se encuentran en heterozigosis.
Gerald Pier y sus colegas (1998) hipotetizaron que los heterozigotos para la fibrosis quística podrían ser más resistentes a fiebres tifoideas y por ello tener una mayor eficacia. Las fiebres tifoideas las produce la bacteria Salmonella typhi. La bacteria inicia la infección cruzando la capa de células epiteliales que tapizan el tubo digestivo. Pier y sus colegas sugirieron que la bacteria Salmonella typhi se infiltra en el tubo digestivo utilizando la proteína CFTR como punto de entrada. Si esto es así, los heterozigotos, que tienen menos copias de la CFTR en la superficie de sus células, deberían ser menos vulnerables a la invasión.

Pier y sus colegas comprobaron su hipótesis construyendo células de ratón con tres
genotipos CFTR diferentes: células homozigóticas de tipo silvestre; heterozigóticas, con un alelo funcional para la CFTR, siendo el otro alelo el mutante para la fibrosis quística más común en la especie humana, llamado ΔF508, que consiste en la deleción de un par de bases; y células homozigóticas para el ΔF508. Los investigadores expusieron estas células a Salmonella typhi y luego midieron el número de bacterias que habían entrado en cada tipo de célula. Los resultados fueron espectaculares (Figura 5.26). Como los investigadores habían pronosticado, las células homozigóticas para el ΔF508 fueron casi totalmente resistentes a la invasión por Salmonella typhi, mientras que las células homozigóticas de tipo silvestre fueron altamente vulnerables. Las células heterozigóticas fueron parcialmente resistentes; acumularon un 86% menos de bacterias que las células de tipo silvestre. Estos
resultados están de acuerdo con la hipótesis de que los alelos mutantes para la fibrosis quística se mantienen en las poblaciones humanas debido a que los heterozigotos tienen una mayor eficacia en epidemias de fiebre tifoidea. La investigación de Pier et al. sirve como otro ejemplo en el que un análisis evolutivo es provechoso en la investigación biomédica.


> [!SUCCESS] Primeras conclusiones de la EMA
>  se manifiesta en diversos grados de gravedad, todos ellos con atrofia muscular generalizada y deterioro de la movilidad.
Esta enfermedad autosómica recesiva está causada por una mutación con pérdida de función en el gen SMN1 (supervivencia de las neuronas motoras 1), ubicado en la región subtelomérica del cromosoma 5. Este gen codifica una proteína selectivamente necesaria para la supervivencia de las neuronas motoras.
La AME es la causa genética más común de muerte infantil. La frecuencia del alelo mutante es q = 0,01. Wirth et al. estimaron un coeficiente de selección para la AME de s = -0,9 (w = 0,1). 


> [!QUESTION] ¿Por qué se mantiene este alelo mutante en poblaciones humanas con una selección tan fuerte en su contra? ¿Se debe al equilibrio entre mutación y selección?


La atrofia muscular espinal

| q    | s    |
| ---- | ---- |
| 0'01 | -0'9 |
$$
\begin{align}
\mu= \lvert s \lvert q^{2} \\
\mu=0'9*10^{-4}
\end{align}
$$


Wirth et al. también determinaron la tasa de mutación a partir de la proporción de nuevos alelos mutantes generados por la mutación, ya que 7 de 340 individuos afectados nacieron de padres sanos:

$$
\begin{align}
\mu=\frac{rq}{2-2r} \\
\mu=\frac{7/340()0'01}{2-2\left( \frac{7}{340}=1'1*10^{-4} \right)}
\end{align}
$$


> [!SUCCESS] EMA 
> La persistencia de la AME en humanos puede explicarse como resultado de un equilibrio entre mutación y selección.


## Frecuencias alélicas en el equilibrio mutación-selección

Para deducir las fórmulas hay que imaginarnos un locus con 2 alelos, *A1* y *A2*, con frecuencias *p* y *q*. *A1* es el tipo silvestre y *A2* es el deletéreo. Sea *mu* la tasa a la que las copias de *A1* se convierten en *A2* por mutación. Supongamos que la tasa de mutación retrógada es despreciable.
La selección eliminará continuamente copias de *A2* de la población, mientras que la mutación dará lugar continuamente a nuevas copias. Deseamos calcular la frecuencia de *A2* cuando  estos 2 procesos se compensan mutuamente. Desarrollaremos una ecuación en función de *p* que describa el equilibrio mutación-selección para el alelo *A1.* Luego resolveremos la ecuación para *q* a fin de obtener la frecuencia en el equilibrio de *A2*. Esta aproximación puede parecer contradictoria, pero simplifica enormemente el cálculo.

**Equilibrio mutación-selección para un alelo recesivo deletéreo**

Imagina que *A2* es un alelo recesivo deletéreo, de tal manera que la eficacia de los genotipos viene dada por


| *w11* | *w12* | *w22* |
| ----- | ----- | ----- |
| 1     | 1     | 1-s   |
en donde el coeficiente de selección *s* indica la fuerza de la selección contra *A2*.
En primer lugar escribiremos la ecuación p*, la frecuenica del  alelo *A1* después de haber actuado la selección, pero antes de que ocurra la mutación. 

$$
p*= p^{2}w_{11}+\frac{pqw_{12}}{p^{2}w_{11}+2pq_{12}+q^{2}w_{22}}
$$
Sustituyendo la eficacia en la table anterior y *q* por (1-p) y simplificando, obtendremos,

$$
p*= \frac{p}{1-s(1-p)^{2}}
$$
A continuación escribiremos una ecuación para p', la frecuencia del alelo *A1*, después de que ocurra la mutación. La mutación convierte una fracción *mu* de las copias de *A1* en copias *A2*, dejando una fracción (1-mu). Así,

$$
p'=1(1-\mu)p*=\frac{(1-\mu)p}{1-s(1-p)^{2}}
$$
Finalmente, cuando la mutación y la selección están en equilibrio, p' es igual a *p*, la frecuencia del alelo *A1* que iniciamos con:

$$
\frac{(1-\mu)p}{1-s(1-p)^{2}}=p
$$
Esto se puede simplificar a 

$$
(1-p)^{2}=\frac{\mu}{s}
$$
Sustituyendo (1-p) por q y despejando q obtendremos una ecuación para q^, la frecuencia en el equilibrio del alelo *A2* en el equilibrio mutación-selección.

$$
\hat{q}=\sqrt{ \frac{\mu}{s} }
$$
Si *A2* es un letal recesivo, entonces s=1, y la frecuencia en el equilibrio de *A2* es igual a la raíz cuadrada de la tasa de mutación.

**Equilibrio mutación-selección para un alelo letal dominante.

Imaginemos que *A2* es un alelo letal dominante, de tal manera que la eficacia de los genotipos viene dada por


| *w11* | *w12* | *w22* |
| ----- | ----- | ----- |
| 1     | 0     | 0     |
La expresión para p* se simplifica hasta 
$$
p*=1
$$
lo que tiene sentido porque, por definición, la selección elimina a todas las copias del alelo letal dominante *A2* de la población. Ahora la expresión p' es

$$
p'=1-\mu
$$
y la condición de equilibrio es
$$
1-\mu=p
$$
Sustituyendo *p* por (1-q) y simplificando, tendremos:
$$
\hat{q}=\mu
$$
En otras palabras, la frecuencia en el equilibrio de *A2* es igual a la tasa de mutación.

## Fórmulas del mutación-selección

Selección en contra del dominante, alelo mutante deletéreo

| w(AA) | w(Aa)  | w(aa)  |
| ----- | ------ | ------ |
| 1     | 1+(-s) | 1+(-s) |

$$
\begin{align}
q=\frac{\mu}{\lvert s \lvert}
\end{align}
$$

Selección en contra parcialmente dominante, alelo mutante deletéreo
w(AA)=1  w(Aa)=1+(-hs)  w(aa)=1+(-s)
$$
q=\frac{\mu}{h\lvert s \lvert}
$$

Selección en contra de alelo mutante deletéreo en haploides.
w(A)=1 w(a)=1+(-s)
$$
q=\frac{\mu}{\lvert s \lvert}
$$
---
# Equilibrio mutación-selección y carga genética

El papel de la deriva queda claro cuando subimos en el modelo hasta el nivel poblacional. El modelo de deriva más famoso es el de trinquete de **Muller**; arguye que las poblaciones asexuales están condenadas a acumular mutaciones deletéreas. H.J. Muller imaginó una población asexual finita en la que los individuos sufren, ocasionalmente, mutaciones deletéreas. Debido a que  las mutaciones imaginadas por Muller son deletéreas, la selección actuará contra ellas. La frecuencia de cada alelo mutante de la población reflejará la tasa de mutación, la fuerza de la selección y la deriva genética.

En cualquier momento, la población de Muller puede incluir individuos, que no lleven una mutación, 2 mutaciones y así sucesivamente. Debido a que la población es asexual, podemos pensar en estos grupos como en subpoblaciones distintas, y representar el número relativo de individuos de cada subpoblación en un histograma. El número de individuos dentro de cada grupo puede ser muy pequeño, dependiendo del tamaño de la población en conjunto y del equilibrio entre la mutación y la selección. El grupo con 0 mutaciones es el único cuyos miembros, como promedio, gozan de la eficacia más elevada; pero si este grupo es evitar la reproducción de todos los individuos del  grupo. Si esto sucede una sola vez, entonces se perderá la subpoblación con  0 mutaciones y los miembros del grupo con una mutación ahora serán los individuos con la mayor eficacia. El único modo para  que reaparezca el grupo con 0 mutaciones es si un miembro del grupo con una mutación sufre una mutación retrógada  que le convierte en uno de con 0 mutaciones.


> [!NOTE] Mutación retrógada/reversa
> Es una mutación que revierte los efectos de una mutación anterior. 

Con la desaparición del grupo con 0 mutaciones, los miembros de la subpoblación con una mutación gozarán de la máxima eficacia media. Pero este grupo puede ser también muy pequeño y puede perderse por  azar en cualquier generación dada. De nuevo, la pérdida por deriva del grupo es mucho más fácil que su recreación por mutación reversa. A medida que el trinquete avanza y la población pierde grupo tras grupo con máxima eficacia, la eficacia promedio de la población disminuye con el tiempo. La carga impuesta por las mutaciones que se acumulan, se conoce como carga genética. Finalmente la carga genética soportada por la población asexual será tan elevada que la población se extinguirá.


> [!NOTE] Lastre genética
> Es la reducción de la eficacia promedio de una población debido a procesos genéticos poblaciones
> Cuantifica el impacto negativo acumulado de alelos deletéreos en una población. 

$$
L=1-\bar{w}
$$
Se distingue diversos tipos de carga genética:
- Lastre mutacional: 
	- Debido a la aparición continua de mutaciones deletéreas (equilibrio mutación-selección).
- Lastre sustitutiva:
	- Debido a la aparición de mutaciones beneficiosas. Cuando estas mutaciones surgen, las variantes previas tienen una aptitud relativa < 1 y generan carga.
- Lastre segregativa: 
	- Surge cuando la reproducción sexual rompe las asociaciones alélicas beneficiosas. Por ejemplo, en el caso de la heterosis (sobredominancia), el genotipo más apto es Aa, pero necesariamente genera aa y AA.
- Lastre recombinante: 
	- Debido a la ruptura de las asociaciones alélicas beneficiosas entre loci (haplotipos).

## Principio Haldane-Muller

La carga de mutación solo depende de la tasa de mutación y no de los efectos de las mutaciones en la eficacia.

Alelos recesivos deletéreo
![[Pasted image 20260108103122.png]]
Alelo dominante deletéreo
![[Pasted image 20260108103132.png]]
Alelos deletéreos en haploides
![[Pasted image 20260108103141.png]]


> [!SUCCESS] Principio de Haldane-Muller
> La población puede soportar solo un número limitado de mutaciones deletéreas por generación sin que disminuya significativamente su viabilidad.


> [!SUCCESS] Equilibrio mutación-selección y lastre genética
> La mutación es un proceso físico-químico que puede producir diferentes tipos de cambios genéticos.
La mutación es la última fuente de variación genética.
Las tasas de mutación se pueden medir mediante la prueba de fluctuación de Luria-Delbrück u otros métodos, y son diferentes de las frecuencias de mutación.
Las tasas de mutación varían ampliamente entre los organismos.
Se puede alcanzar un equilibrio entre mutación y selección, el cual dependerá de la tasa de mutación, el coeficiente de selección y el modo de herencia.
La lastre mutacional es independiente del coeficiente de selección (principio de Haldane-Müller).

---
# Efectos de la migración o flujo génico

La migración es el movimiento de alelos entre poblaciones. Puede estar causada por cualquiera cosa que desplace alelos lo bastante lejos como para ir de una población a otra.
Hay diferentes modelos :
- Modelo continente-isla
	- La población se divide en continente e isla. 
		- El continente es grande, estable y su frecuencia alélica se considera cte.
		- La isla pequeña, sujeta a deriva genética y mutaciones, pero recibe inmigrantes del continente. 
	- La frecuencia de alelos en la isla cambian según el flujo de migración: la isla tiende a parecerse al continente cuanto mayor sea la migración. Si la migración es baja, la isla puede evolucionar independientemente. El modelo se usa para estudiar aislamiento, deriva genética y selección en poblaciones pequeñas.
- Modelo isla infinito
	- La población se divide en un número infinito de islas, cada una pequeña y sujeta a deriva genética y mutaciones. 
	- La migración ocurre entre islas de manera aleatoria. Debido al gran número de islas, la deriva promedio entre todas se reduce, pero cada isla puede diferir genéticamente de las demás. Se usa para estudiar genética, equilibrio entre deriva y migración, y cómo se mantiene la variabilidad en poblaciones fragmentadas.
- Modelo en una dimensión→Separación por la distancia
	- La población se organiza en una línea de subpoblaciones (islas) conectadas por migración. 
	- Cada subpoblación es pequeña y está sujeta a deriva genética y mutaciones.
	- La migración ocurre entre vecinas adyacentes.
	- Cuando más cerca más similar será geneticamente.
	- Se usa para estudiar aislamiento por distancia y la propagación de alelos a lo largo de un eje lineal.
- Modelo en dos dimensiones→ "Stepping-stone"
	- La migración ocurre solo entre subpoblaciones vecinas.
	- La distancia afecta la similitud genética: subpoblaciones cercanas tienden a ser más parecidas, las lejanas más divergentes.
	- Se usa para estudiar estructura espacial, aislamiento por distancia y cómo la migración local influye en la diversidad genética.

> [!Success] Modelo continente-Isla
> La migración consiste en el movimiento de alelos de una población a otra. En una población dada, la migración puede dar lugar a cambios en las frecuencias alélicas de una generación a la siguiente. En poblaciones pequeñas, reciben inmigrantes de poblaciones grandes, la migración puede ser un potente mecanismos evolutivo. A lo largo de grupos de poblaciones, el flujo génico tiende a homogeneizar las frecuencias alélicas. Por eso, la migración tiende a evitar la divergencia evolutiva de las poblaciones.

> [!NOTE] Stepping-Stone
> Es un modelo estructura poblaciona en el que las subpoblaciones están organizadas en una secuencia lineal o en un plano bidimensional y la migración solo ocurre entre vecinas inmediatas.

## Demostración de la migración como fuerza evolutiva(Continente isla)

Sea la *p1* la frecuencia del alelo *A1* en una población de una isla. Y *pc* la frecuencia del alelo *A1* en la población continental. Imagine que en cada generación un grupo de individuos se desplaza de la población continental a la isla, en donde constituyen la fracción *m* de la población de la isla. Queremos conocer cómo consecuencia de la migración, y si hay una frecuencia de equilibrio para *A1* que no cambie más incluso si continúa la migración.
En primer lugar, habrá que obtener la expresión para *pI'*, la frecuencia de *A1* en la isla en la generación siguiente. Una fracción *(1-m)* de los individuos de la generación siguiente ya está en la isla. En estos individuos de la generación siguiente viene del continente. En ellos la frecuencia de *A1* es *pC*. Así, la nueva frecuencia de *A1* en la población de la isla es el promedio ponderado de la frecuencia entre los residentes y la de los inmigrantes.
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

 Tenemos dos poblaciones, una en un continente y otra en una pequeña isla costera. Debido  a que la población de la isla es relativamente pequeña en relación con la población continental, cualquier suceso migratorio desde la isla al continente no tendrá consecuencias en las frecuencias alélicas y genotípicas del continente. Por ello, la migración y el flujo génico correspondiente, será efectivo sólo en una dirección, del continente a la isla. Pero, ¿puede la migración del continente  a la isla desplazar las frecuencias alélicas y genotípicas de la isla lejos del equilibrio de HWE?

 Para ello, debemos la frecuencia antes de la migración de *A1* es de 0'1(o sea, esta fijado en la población).
 Cuando los gametos de un conjunto de genes en donde está fijado *A1* se combina al azar para formar zigotos, las frecuencias genotípicas serán los siguientes:

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

##  Aplicación del modelo continente-isla II

**Investigación experimental sobre la migración como mecanismos evolutivo**

La serpiente de agua *Nerodia sipedon* proporcionan un ejemplo de migración desde una población continental a una isla. Estas serpientes viven en los alrededores del lago Erie y en las islas del lago. El patrón de color viene determinado por un solo locus con dos alelos, siendo el alelo para bandas dominantes sobre el alelo sin bandas.
En el continente casi todas son bandeadas, mientras que en las islas muchos carecen de bandas. La diferencia en la composición de las poblaciones del continente respecto de las de las islas que es consecuencia de la selección natural promovida por los predadores. 

Si la selección favorece a las serpientes sin bandas en las islas, entonces se esperaría las poblaciones isleñas estuvieran formadas sólo por serpientes sin bandas. Cosa que no sucede, debido que en cada generación varias serpientes con bandas se desplazan del continente a las islas. Los migrantes traen consigo alelos para el patrón a bandas. Cuando las serpientes migrantes se cruzan con las serpientes de la isla contribuyen con copias del alelo para bandas al conjunto de genes de la isla.
Este caso sería un ejemplo de la migración actúa como fuerza evolutiva en oposición a la selección natural, evitando que en las poblaciones de las islas quede fijado el alelo sin bandas.
![[Pasted image 20251104112141.png]]

## La migración como fuerza evolutiva homogeneizadora entre las poblaciones

 Éste es el efecto general de la migración: tiende a homogeneizar las frecuencias alélicas a lo largo de las poblaciones. En las serpientes de agua, a esta homogeneización se opone la selección natural.

> [!question] ¿Hasta dónde iría la homogeneización si no se opusiera la selección? 
>


El modelo anterior demuestra el flujo génico desde un continente a una isla, llevará finalmente las frecuencia alélicas de la isla a un valor exactamente igual al que hay en el continente. Es decir, si se permite que prosiga la migración sin oposición de cualquiera otra fuerza evolutiva, finalmente homogeneizará totalmente las frecuencias alélicas en las poblaciones.

## Estructura población

La migración tiene un efecto homogeneizador sobre las diferencias genéticas entre poblaciones.

Sin embargo, cuando actúan mecanismos evolutivos diferentes y el flujo genético
se reduce o desaparece, cada población se vuelve genéticamente diferente, una situación denominada: Estructura poblacional.

Como se observa, la deriva genética aleatoria conduce a una disminución de la heterocigosidad:

## Efecto Wahlund

Es una reducción en la heterocigosidad observada en una población que ha sido subdividida en subpoblaciones con diferentes frecuencias alélicas.

En la gráfica se observa como la heterozigosidad esperada bajo el HWE es la mitad(0'3) pero debido a la migración ese valor de heterozigosidad este ser verá incrementado o reducido.


En palabras, el efecto de Wahlund provoca una disminución de la frecuencia de homocigotas recesivos luego de la mezcla de poblaciones y apareamiento bajo panmixia igual a la varianza de frecuencias alélicas (del alelo recesivo) entre poblaciones.

> [!SUCCESS] Conclusión de los efectos de la migración
> La migración es un proceso que puede cambiar las frecuencias alélicas y genotípicas muy rápidamente.
Existen varios modelos de migración; el modelo continente-isla es uno de los más básicos.
En el modelo continente-isla se puede obtener un modelo de migración-selección polimórfico.
En ausencia de migración, la estructura poblacional se construye bajo la acción d la deriva genética.
El efecto Wahlund es la pérdida de heterocigosidad debido a la estructura poblacional y es importante en biología de la conservación.
Los efectos fundadores son un caso extremo de estructura poblacional debido a la migración/aislamiento.

---
# Desequilibrio de ligamiento: falta de independencia

Si nos fijamos en un par de loci situados en el mismo cromosoma, es decir, si consideramos 2 locis físicamente ligados. Imaginaremos que el locus *A* tiene 2 alelos, *A*  y *a*, y que el  locus *B* tiene dos alelos *B* y *b*.

En el HW para un solo locus, estuvimos interesados principalmente las frecuencias alélicas. En la versión para 2 loci, nos intereserá seguir tanto las frecuencias alélicas como cromosómicas. Hay que tener en cuenta que las suposiciones hechas anteriormente, nos permiten 4 genotipos cromosómicos diferentes; *AB, Ab, aB y ab*. A veces se denomina genotipo multilocus de un cromosoma como su haplotipo.

Habrá que determinar si la selección sobre el locus *A* interferirá en nuestra capacidad para utilizar los modelos de capítulos anteriores, y hacer predicciones acera de la evolución del locus B. 

## Ejemplo numérico

Tenemos 2 poblaciones hipotética, cada una con un conjunto cromosómico de cromosomas. Al estudiar la estructura genética de estas poblaciones, habrá que calcular las frecuencias alélicas. En la población de arriba,por ejemplo, 15 de los 25 cromosomas llevan el alelo A en el locus A. Por ello la frecuencia del alelo es 15/25 = 0,6. Lo mismo es cierto para la población de abajo. De hecho las frecuencias alélicas en los dos loci son idénticas en las dos poblaciones. Si sólo estuviéramos estudiando el locus A, o sólo el locus B, concluiríamos que las dos poblaciones son idénticas

Pero las dos poblaciones no son idénticas. Esto lo descubrimos cuando calculamos las
frecuencias cromosómicas. Por ejemplo, en la población de arriba 12 de los 25 cromosomas lleva el haplotipo AB, con una frecuencia de 0,48. Por otro lado, en la población de abajo la frecuencia de los cromosomas AB es 11 de 25, o el 0,44.

> [!SUCCESS] Primera lección de HW para 2 loci
> Un par de poblaciones pueden tener frecuencias alélicas idénticas pero frecuencias cromosómicas diferentes.


Otra forma de ver las diferencias entre las dos poblaciones de la Figura 7.2 es calculando la frecuencia del alelo B en cromosomas que llevan el alelo A respecto de los que llevan el alelo a. En la población de arriba hay 15 cromosomas que llevan el alelo A, 12 de los cuales llevan el alelo *B*. La frecuencia de *B* en cromosomas A es así 12/15 = 0,8. En la misma población hay 10 cromosomas que llevan el alelo a, 8 de las cuales llevan el alelo *B*. La frecuencia de *B* en cromosomas a es 8/10 = 0,8. Por ello, en la población de arriba, la frecuencia del alelo B es la misma en cromosomas que llevan A que en los que llevan a. No ocurre lo mismo en la población de abajo. Allí la frecuencia de B es 0,73 en cromosomas *A*, pero 0,9 en cromosomas *a*.

Los gráficos de barras de la Figura 7.2 proporcionan una representación visual de la
diferencia entre las dos poblaciones. La anchura de las dos barras en cada gráfico representa la frecuencia de los cromosomas que llevan *A* respecto de los cromosomas que llevan *a*. Advierta que la anchura combinada de las dos barras debe de ser igual a 1, por lo que si una barra se hace más ancha la otra debe hacerse más estrecha. La parte sombreada respecto de la no sombreada de cada barra representa la frecuencia del alelo *B* respecto del alelo *b* en los cromosomas en cuestión. El gráfico de barras nos permite ver a simple vista lo que descubrimos mediante el cálculo en los párrafos anteriores. En la población de arriba la frecuencia de *B* es la misma en cromosomas *A* y en cromosomas a; en las dos barras está sombreada la misma fracción. En la población de abajo la frecuencia de *B* es menor en cromosomas *A* que en cromosomas *a*.

![[Pasted image 20260109165907.png]]

> [!NOTE] Desequilibrio de ligamiento
> Falta de independencia entre alelos en diferentes loci.

## Definición del desequilibrio de ligamiento

En la población de arriba de la Figura 7.2, los loci A y B se encuentran en equilibrio
de ligamiento. En la población de abajo, los loci se encuentran en desequilibrio de liga-
miento. En una población, dos loci se encuentran en equilibrio de ligamiento cuan-
do el genotipo de un cromosoma en un locus es independiente de su genotipo en el
otro locus. Esto significa que, conociendo el genotipo del cromosoma para un locus
no nos dice nada sobre cuál es el genotipo en el otro locus. Dos loci se encuentran en
desequilibrio de ligamiento cuando no hay una asociación aleatoria entre el geno-
tipo de un cromosoma para un locus y su genotipo en el otro locus. Si conocemos el
genotipo de un cromosoma en un locus, esto nos da una clave acerca del genotipo en
el otro.

Condiciones son ciertas para un par de loci y sólo lo son si están en equilibrio de ligamiento:
1. La frecuencia de B en los cromosomas que lleven el alelo *A* es la misma que la frecuencia de *B* en los cromosomas que lleven el alelo *a*.
2. La frecuencia de cualquier haplotipo cromosómico se puede calcular multiplicando las frecuencias de los alelos constituyentes. Por ejemplo, se puede calcular la frecuencia de los cromosomas AB multiplicando la frecuencia del alelo A por la del alelo B.
3. La cantidad D, conocida como el coeficiente del desequilibrio de ligamiento, es igual a 0. *D* se calcula como
$$
\delta _{AB}\delta_{ab}-\delta_{Ab}\delta_{aB}
$$
donde delta son las frecuencias de los cromosomas.

## ¿Cómo se produce el desequilibrio de ligamiento en una población?

3 mecanismos pueden dar origen al desequilibrio de ligamiento en una población con apareamiento al azar:
- La selección sobre genotipos multilocus.
- Deriva genética.
- Mezcla de poblaciones.

**Selección**

Para ver cómo la selección sobre genotipos multilocus puede dar lugar a desequilibrio
de ligamiento, comencemos con una población cuyo conjunto de genes se muestra en la Figura 7.2a. Los locus A y B se encuentran en equilibrio de ligamiento. Imagine que los gametos en este conjunto de genes se combinan al azar para producir los zigotos. En la parrilla de la Figura 7.3a aparecen los 10 tipos de zigotos producidos y sus respectivas frecuencias esperadas. Por ejemplo, ya que el 32% de los óvulos y el 32% de los espermatozoides son aB, predecimos que la frecuencia de los zigotos aB/aB será 0,32  0,32  0,1024. Dejemos ahora que los zigotos se desarrollen hasta adultos y asignemos fenotipos como sigue: los individuos con genotipo ab/ab tienen un tamaño de 10. En los otros genotipos, cada alelo A o B añade una unidad al tamaño del individuo. Por ejemplo, los individuos aB/aB tienen un tamaño de 12 y los individuos AB/Ab un tamaño de 13. Imagine, finalmente, que los predadores capturan y se comen a todos los individuos cuyo tamaño es menor que 13. Los supervivientes, que representan el 65,28% de la población original, aparecen en la parrilla de la Figura 7.3b.

En el conjunto de los supervivientes, los loci A y B están en desequilibrio de ligamiento. Quizá la manera más fácil de verlo es calculando la frecuencia del alelo a y del b. Un modo de calcular la frecuencia de a es la siguiente: los individuos que llevan el alelo a constituyen una fracción (0,1536 + 0,1536)/0,6528 ⬇ 0,47 de los supervivientes. Así pues llevan el 47% de los alelos del locus A. La mitad de estos alelos serán a. Por consiguiente, la frecuencia de a entre los supervivientes es 0,5  0,47 ⬇ 0,24. La frecuencia de b es, aproximadamente, 0,09. Si nuestros dos loci estuvieran en equilibrio de ligamiento, entonces, de acuerdo con el criterio 2 de nuestra lista, la frecuencia de los cromosomas ab sería 0,24  0,09 ⬇ 0,02. De hecho, la frecuencia de los cromosomas ab es 0. Nuestros dos loci se encuentran en desequilibrio de ligamiento. Como ejercicio, el lector podría demostrar que los loci también se encuentran en desequilibrio de ligamiento de acuerdo con los criterios 1 y 3.

![[Pasted image 20260108115206.png]]

**Deriva genética**

Cuando los sucesos clave parece que son la mutación y la selección. La razón es que el escenario, tal como lo describimos, sólo podría darse en una población finita. En una población infinita, la mutación que convierte al alelo A en el a se produciría no una sola vez, sino muchas veces en cada generación, tanto sobre los cromosomas AB como Ab. En ningún momento habría ausencia de cromosomas aB. La selección que favorece a a sobre A aumentaría simultáneamente la frecuencia de los cromosomas ab y aB. Los locus A y B nunca estarían en desequilibrio de ligamiento. Debido a que en nuestro escenario sólo se puede generar desequilibrio de ligamiento en una población finita, el mecanismo evolutivo decisivo que actúa es la deriva genética. Fue a causa de un error de muestreo lo que ocasionó que la mutación que dio lugar al alelo a, sucediera una sola vez y en un cromosoma Ab.

![[Pasted image 20260108115108.png]]

**Mezcla de poblaciones**

imagine dos conjuntos de genes (Figura 7.5). En uno hay 60 cromosomas *AB, 20 Ab, 15 aB y 5 ab.* En el otro hay 10 cromosomas *AB, 40 Ab, 10 aB y 40 ab*. Los locus A y B se encuentran en equilibrio de ligamiento en cada conjunto génico, como se demuestra por los dos gráficos de barras superiores de la Figura 7.5. Ahora combine los dos conjuntos de genes. Esto da lugar a un nuevo conjunto de genes donde hay 70 cromosomas *AB, 60 Ab, 25 aB y 45 ab.* En este nuevo conjunto de genes los loci A y B se encuentran en desequilibrio de ligamiento.

La selección sobre genotipos multilocus, la deriva genética y la mezcla de poblaciones
pueden dar lugar a desequilibrio de ligamiento debido a que pueden dar lugar a pobla-
ciones en las que algunos haplotipos cromosómicos estén poco representados y otros
demasiado representados, cuando se compara con lo que deberían ser sus frecuencias en equilibrio de ligamiento. Por ejemplo, en nuestro esquema de selección multilocus, la selección actuaba con más fuerza contra ab que contra cualquier otro haplotipo, ya que no sobrevivía ningún individuo que tuviera un cromosoma ab. En nuestro escenario de deriva, un suceso aleatorio dio lugar a un cromosoma ab, pero no a un cromosoma aB.

En nuestro ejemplo de mezcla poblacional, una simple combinación de poblaciones con frecuencias alélicas y cromosómicas diferentes dio lugar a una nueva población con un exceso de cromosomas AB y ab.
![[Pasted image 20260108115145.png]]
## ¿Qué elimina el desequilibrio de ligamiento de una población?

El desequilibrio de ligamiento en una población puede generarse por selección, deriva o mezcla de poblaciones, pero la reproducción sexual lo reduce inevitablemente. La meiosis con entrecruzamiento y la fecundación cruzada reúnen cromosomas con haplotipos diferentes, y cuando los zigotos se reproducen, el entrecruzamiento rompe las viejas combinaciones de alelos y crea nuevas combinaciones, lo que se llama recombinación genética. 
La recombinación tiende a aleatorizar los genotipos de un locus respecto a otro, reduciendo la frecuencia de haplotipos sobrerrepresentados y aumentando la de los subrepresentados, disminuyendo así el desequilibrio de ligamiento. Bajo condiciones de Hardy-Weinberg, la tasa de disminución del desequilibrio entre un par de loci es proporcional a la frecuencia de recombinación entre ellos. Clegg y sus colegas documentaron esto en poblaciones de moscas de la fruta con dos alelos en dos loci del cromosoma 3, fundando poblaciones con cromosomas AB y ab o Ab y aB en completa disequilibrio. Tras 48 a 50 generaciones con apareamiento al azar y tamaños de unas 1000 moscas, midieron los haplotipos y observaron que el desequilibrio de ligamiento disminuyó como se esperaba, incluso algo más rápido de lo pronosticado, probablemente debido a la superioridad del heterozigoto, que aumentó la frecuencia de individuos heterozigotos y facilitó más entrecruzamiento, rompiendo las asociaciones no aleatorias entre alelos de los loci.
## Barrido selectivo y arrastre genético

Bajo el LD, la selección que favorece un alelo en un locus también afecta las frecuencias alélicas en otros loci.

![[Pasted image 20260108114115.png]]

> [!NOTE] Barrido selectivo
> Es un fenómeno que ocurre cuando un alelo beneficioso aumenta rápidamente de frecuencia en una población debido a selección positiva, y esto afecta a los alelos cercanos en el mismo cromosoma.
> Un alelo beneficioso aumenta rápidamente de frecuencia debido a selección positiva, y como consecuencia arrastra a los alelos vecinos en el cromosoma, reduciendo la diversidad genética en esa región.


> [!NOTE] Arrastre génico
> En el que un alelo neutro o incluso ligeramente perjudicial aumenta en frecuencia en una población porque está fisicamente ligado a un alelo beneficioso que está siendo favorecido por selección neutral.


Si el locus de interés está de hecho en desequilibrio de ligamiento con otro,
entonces los modelos de genética de poblaciones para un locus pueden dar lugar a predicciones incorrectas. Sin embargo, en poblaciones con apareamiento al azar, puede esperarse que muchas de las parejas de loci se encuentren en equilibrio de ligamiento.
En general, podemos esperar que los modelos para un solo locus funcionarán bien la
mayor parte de las veces.
## Utilizar el LD(Ligamiento selectivo) como evidencia de selección reciente

El alelo CCR5-Δ32 en los Capítulos 4 y 5. Este alelo es una mutación de pérdida de función del locus CCR5. Protege a los homozigotos contra la transmisión sexual de cepas del VIH-1. Entre las cuestiones no resueltas de la discusión anterior se encuentran éstas: ¿de dónde viene el alelo Δ32? y, ¿por qué es frecuente sólo en Europa?
J. Claiborne Stephens y sus colegas (1998) abordaron estas preguntas midiendo el desequilibrio de ligamiento entre el locus CCR5 y dos loci localizados cerca en el mismo cromosoma. Los loci cercanos son lugares con cortas repeticiones en tándem llamadas GAAT y AFMB. GAAT tiene tres alelos y AFMB cuatro. GAAT y AFMB no codifican nada y sus alelos parece que no tienen efecto sobre la eficacia. Stephens y sus colegas determinaron los haplotipos de 192 cromosomas de una muestra de europeos. Como muestra la Figura 7.9a, GAAT y AFMB están próximos a encontrarse en equilibrio de ligamiento. Las frecuencias de los distintos alelos del locus AFMB son casi las mismas en los cromosomas que llevan cualquiera de los alelos del locus GAAT que entre los cromosomas que llevan los otros alelos GAAT. Sin embargo, como muestran las Figuras 7.9b y 7.9c, el locus CCR5 se encuentra en fuerte desequilibrio de ligamiento tanto con el locus GAAT como con el locus AFMB. Casi todos los cromosomas que llevan el alelo Δ32 en CCR5 también llevan el alelo 197 en GAAT (Figura 7.9b) y el alelo 215 en AFMB (Figura 7.9c).

**¿Cómo surgió el desequilibrio de ligamiento entre CCR5 y sus vecinos? Lo más probable que sea la selección sobre genotipos multilocus.**

Tanto GAAT y AFMB  son loci que no codifican nada y sus alelos parecer ser selectivamente neutros. La mezcla poblacional es también un candidato improbable ya que requeriría una población en la que la frecuencia del alelo Δ32 fuera mucho más elevada que en Europa, y tal población no existe. Esto nos lleva a la deriva genética. La mezcla poblacional es también un candidato improbable ya que requeriría una población en la que la frecuencia del alelo Δ32 fuera mucho más elevada que en Europa, y tal población no existe. Esto nos lleva a la deriva genética.
Stephens y sus colegas creen que el desequilibrio de ligamiento entre CCR5 y sus vecinos surgió en un escenario similar al mostrado en la Figura 7.4. En un momento dado en el pasado, la población europea tenía sólo un alelo en CCR5, el CCR5-+. Luego, en un cromosoma con el haplotipo CCR5-GAAT-AFMB, +-197-215, se produjo una mutación que dio lugar al alelo Δ32. Por consiguiente, el antecesor de todos los alelos Δ32 fue un cromosoma con el haplotipo Δ32-197-215. Finalmente, el nuevo alelo Δ32 fue favorecido por selección natural. Se incrementó hasta frecuencias elevadas, arrastrando consigo a los alelos vecinos 197 y 215.

La asociación entre el alelo Δ32 de CCR5, el alelo 197 de GAAT y el alelo 215 de
AFMB no es perfecta.Ya que el alelo Δ32 apareció primero, la recombinación o muta-
ciones adicionales han situado al Δ32 en otros haplotipos, como el Δ32-197-217. En otras palabras, el desequilibrio de ligamiento entre el locus CCR5 y sus vecinos se está rompiendo. Stephens y sus colegas utilizaron estimas de frecuencias de entrecruzamiento y mutación para calcular lo rápidamente que se rompería el desequilibrio de ligamiento.
Luego utilizaron estos cálculos para estimar cuánto tiempo hacía que había aparecido por primera vez el alelo Δ32. Los investigadores concluyeron que el alelo Δ32 apareció hace entre 275 y 1.875 años, con la mejor estima en unos 700 años (véase el Cuadro 7.4).
La respuesta a nuestra pregunta acerca del origen del alelo Δ32 parece que es ésta: el
alelo se originó por una única mutación que se produjo en Europa en los últimos siglos.
El alelo no se dio fuera de Europa bien porque la mutación que lo originó nunca se ha
dado en una población no europea, o porque cuando la mutación se dio fuera de Euro-
pa, no fue favorecida por selección.

Esta respuesta plantea, desde luego, nuevas preguntas. Por ejemplo, la selección que favoreció al alelo Δ32 en Europa debe de haber sido fuerte. Sabemos esto porque sólo la selección fuerte pudo haber llevado al alelo de una frecuencia prácticamente de cero a una frecuencia del 10 al 20% en sólo unos 700 años

> [!question] ¿Cuál fue el agente selectivo responsable?
> La sospecha más obvia sería una enfermedad epidémica como sería la peste bubónica.

Una intrigante posibilidad es la peste bubónica, responsable de la peste negra que asoló a Europa durante el siglo XIV, matando de la cuarta parte a la mitad de la población. La peste bubónica la provoca la bacteria *Yersinia pestis*. Quizá el alelo Δ32 protegió también contra la *Yersinia pestis*. Desde este trabajo, la hipótesis de la peste bubónica está siendo comprobada por los investigadores en el laboratorio de Stanley Falkow de la Universidad de Stanford. No se tienen todavía resultados definitivos. 

Recientemente,Alshad Lalani y sus colegas (1999) comunicaron que el mixoma, un virus de los conejos de la familia de los poxvirus, puede, al igual que el VIH-1, utilizar CCR5 para introducirse en las células huésped. Lalani y sus colegas especularon que la enfermedad responsable de la elevada frecuencia del alelo Δ32 en Europa podría haber sido la viruela.

Si resulta que el agente selectivo que favoreció al alelo Δ32 en Europa fue la peste
bubónica o la viruela, entonces cabría esperar que las mutaciones de pérdida de función en el gen CCR5 habrían sido favorecidas en otras partes del mundo que también hubieran padecido epidemias de estas enfermedades. De hecho, los investigadores han encontrado diversas mutaciones en CCR5. Entre éstas hay una mutación de pérdida de función con una frecuencia del 3 al 4% en poblaciones chinas y japonesas. No se ha determinado el origen y significado selectivo de este alelo.

> [!SUCCESS] Desequilibrio del ligamiento 
> El desequilibrio de ligamiento es una herramienta poderosa para reconstruir la historia del alelo.

![[Pasted image 20260108112908.png]]

Existe una fuerte LD, con el alelo ∆32 asociado a los alelos GAAT 197 y AFMB 215:
• Esto no puede explicarse por la mezcla poblacional, ya que ∆32 es muy poco común en otras regiones.
• Es muy improbable que se deba a la selección en GAAT o AFMB, ya que se trata de regiones no codificantes.
• Por lo tanto, es probable que se trate de un caso de autostop debido a la selección en ∆32 en poblaciones finitas.


> [!success] Conclusiones del desequilibrio de ligamiento
> El desequilibrio de ligamiento es la falta de independencia entre alelos de
diferentes loci y tiene importantes consecuencias evolutivas.
Las frecuencias de haplotipos (gametos) en apareamientos aleatorios no se mantienen constantes, sino que varían según el desequilibrio de ligamiento y la tasa de recombinación genética.
La recombinación disipa el desequilibrio de ligamiento.
La selección multilocus, la mezcla poblacional o la selección de un alelo ventajoso en poblaciones finitas pueden generar desequilibrio de ligamiento.
En presencia de desequilibrio de ligamiento, la selección que actúa sobre un locus afecta las frecuencias alélicas en loci ligados (arrastre genético) y produce una pérdida local de variabilidad (barrido selectivo).
El desequilibrio de ligamiento se utiliza como indicador de episodios recientes de selección de nuevos alelos ventajosos.
