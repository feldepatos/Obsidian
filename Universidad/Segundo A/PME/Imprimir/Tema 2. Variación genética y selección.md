
## Cuantificación de la variación genética

- La forma más sencilla de **analizar las estructuras genéticas de poblaciones es mediante la estimación de las frecuencias de los alelos presentes en los individuos de una población.**
- Para ello, necesitamos determinar el genotipo de los individuos de la población (o al menos de una muestra representativa de individuos) en diferentes loci.
- A partir de estas frecuencias genotípicas, podemos estimar las frecuencias alélicas (también llamadas frecuencias genéticas).
- En el caso de individuos haploides, las frecuencias alélicas son iguales a las frecuencias genotípicas, que a su vez son iguales a las frecuencias fenotípicas.
- En el caso de individuos diploides, las frecuencias alélicas pueden estimarse a partir de las frecuencias genotípicas mediante:
$$
f(A_{i})=f(A_{i}A_{j})+\frac{1}{2}ª\sum_{j=1}^nf(A_{i}A_{j})
$$
Para un locus con 2 alelos:
$$
\begin{align}
f(A)=f(AA)+\frac{1}{2}f(Aa) \\
f(a)=f(aa)+\frac{1}{2}f(Aa)
\end{align}
$$
- Como se observa, en los **haploides, las frecuencias alélicas se estiman directamente a partir de las frecuencias fenotípicas.**
- Sin embargo, en el caso de los **diploides, las frecuencias genotípicas no siempre pueden estimarse directamente a partir de las frecuencias fenotípicas** (depende del tipo de herencia).
- Si la herencia no es dominante (intermedia, codominancia, dominancia parcial, etc.), donde cada genotipo muestra un fenotipo diferente, las frecuencias genotípicas pueden estimarse a partir de las frecuencias fenotípicas.
- Sin embargo, cuando la herencia es dominante, no es posible:
$$
\begin{align}
f(fenotipo\ dominante)=f(AA)+f(Aa) \\
f(fenotipo\ recesivo)=f(aa)
\end{align}
$$

- Para determinar si un individuo con fenotipo dominante es homocigoto o heterocigoto, debemos analizar si su descendencia es homogénea o heterogénea en un cruce con un individuo homocigoto recesivo (denominado cruce de prueba), pero esto resulta engorroso o imposible en muchos casos (por ejemplo, en humanos).
- Otra posibilidad es determinar si se cumplen ciertas condiciones (el llamado equilibrio de Hardy-Weinberg) que facilitarán la estimación de las frecuencias alélicas, como se explica en la siguiente sección.

Existen técnicas moleculares paras cuantificar como el análisis de las aloenzimas, análisis restrictivo del ADN, y la secuenciación del ADN.


| Análisis de las aloenzimas                                                                                            | Análisis restrictivo del ADN                                                | Secuenciación del ADN                                   |
| --------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------- | ------------------------------------------------------- |
| Diferencias en la movilidad electroforética de variantes alélicas de enzimas, detectadas por su actividad enzimática. | detección de sustituciones de nucleótidos ubicadas en sitios de restricción | Diferencias de nucleótidos en las secuencias del genoma |

La heterocigosidad se suele emplear en genética de poblaciones como medida de variabilidad, pero no es el único parámetro que se puede calcular (número promedio de alelos por locus, frecuencia de loci polimórficos, etc.). Una ventaja importante de este parámetro es que la heterocigosidad esperada según Hardy-Weinberg coincide con la diversidad genética, una medida de variabilidad genética frecuentemente utilizada que no se limita a los organismos diploides.
$$
h=\sum_{i\neq j}2p_{i}p_{j}=1-\sum_{i}p^{2}=D\ \ \ 0<D_{1}-\left( \frac{1}{K} \right)
$$
$$
D'=\frac{D}{D_{max}} donde \ D_{max}=1-\frac{1}{k}\text{K es el número de alelos}
$$
Heterocigosidad media
$$
H_{e}=\frac{1}{n}\sum_{i=1}^{n}h_{i}
$$
donde h_i, es la heterozigosidad esperada para el locus i, y n es el número de loci.

---

# Poblaciones genéticas

## El origen de la genética de población

El origen de la genética de poblaciones es una disciplina científica que surgió entre finales del siglo XIX y principios del siglo XX. En ese periodo existían dos teorías fundamentales en biología. La primera era una teoría que proponía que los organismos heredan rasgos de sus progenitores mediante unidades discretas que se transmiten de generación en generación. Esta teoría explicaba cómo se mantiene la información genética y cómo pueden reaparecer características en descendientes aunque no se expresen en los padres. La segunda era la teoría de la evolución por selección natural, que planteaba que en la naturaleza existen variaciones entre los individuos y que aquellos con características más favorables para sobrevivir tienden a dejar más descendencia, provocando cambios graduales en las poblaciones a lo largo del tiempo.

Inicialmente, estas dos teorías parecían incompatibles. Algunos pensaban que la herencia era demasiado rígida para permitir cambios evolutivos importantes, mientras que otros creían que la evolución ocurría de forma continua sin necesidad de comprender la genética. Sin embargo, durante las primeras décadas del siglo XX, varios científicos demostraron que la herencia y la evolución no solo eran compatibles, sino que juntas podían explicar de manera precisa cómo y por qué cambian las poblaciones biológicas. Esta unión de ideas dio lugar a lo que se conoce como la síntesis moderna. La síntesis moderna integró la teoría de la herencia genética con la teoría de la selección natural, creando un marco científico que explica la evolución mediante cambios en las frecuencias de genes dentro de una población.

A partir de esta integración nació la genética de poblaciones, una disciplina que analiza de forma matemática y estadística cómo evolucionan las poblaciones a lo largo del tiempo. La genética de poblaciones se centra en estudiar los genes, que son unidades de información hereditaria, y observar cómo cambian en distintas generaciones. Este campo investiga las fuerzas evolutivas principales: la selección natural, que favorece ciertos genes por su ventaja adaptativa; la mutación, que introduce variaciones nuevas; la migración, que permite el intercambio de genes entre poblaciones; y la deriva genética, que explica cómo el azar puede alterar la composición genética, especialmente en poblaciones pequeñas.

En la parte inferior de la imagen aparecen tres figuras históricas importantes para el desarrollo de esta disciplina. Estas personas no se identifican individualmente por nombre, sino por su rol como fundadores del campo. Aportaron teorías y modelos matemáticos que permitieron demostrar que la evolución puede estudiarse de manera cuantificable y predecible. Entre sus contribuciones destacan la forma en que se mantiene el equilibrio genético en una población, la influencia del azar en la evolución y la importancia de la interacción entre el ambiente y los genes. Gracias a sus trabajos, la evolución dejó de ser un concepto puramente descriptivo para convertirse en una ciencia basada en datos, ecuaciones y predicciones.

En resumen, **la genética de poblaciones nació de la unión entre el estudio de la herencia biológica y la teoría de la evolución**. Esta combinación dio origen a una disciplina científica moderna que explica cómo cambian los organismos a lo largo del tiempo mediante procesos genéticos observables y medibles. La genética de poblaciones es hoy uno de los pilares de la biología evolutiva y nos permite entender temas como la adaptación, la biodiversidad y el origen de las especies desde una perspectiva genética y matemática.

- Objeto de estudio: La genética de poblaciones estudia la estructura de las características genéticas de las poblaciones de organismos, así como los procesos responsables de su cambio de generación en generación (evolución).
- Población: comunidad reproductiva de individuos que comparten un conjunto común de genes (acervo genético).
- Fuerzas evolutivas: mecanismos que promueven el cambio genético en las poblaciones de generación en generación.

Las fuerzas evolutivas son:
- Mutación: mecanismo implicado en la generación de variabilidad genética.
- Selección: transmisión diferencial de variantes genéticas de generación en generación debido a diferencias en la aptitud de los portadores.
- Flujo génico (migración): cambios en las frecuencias génicas debido al movimiento de individuos o gametos entre poblaciones.
- Deriva genética: transmisión diferencial de variantes genéticas de generación en generación debido a eventos aleatorios.

---
# Equilibrio Hardy-Weinberg
## Perspectiva histórica

El primer biológo que abordó un ejemplo numérico, siguiendo las frecuencias de los alelos mendelianos de una generación a la siguiente en una población ideal, fue G.Ydny Yule en 1902. Comenzó con un conjunto de genes en el que las frecuencias de los dos alelos eran 0'5 y 0'5 y demostró que en el conjunto de genes de la siguiente generación las frecuencias alélicas eran todavia 0'5 y 0'5.

Como nosotros, Yule concluyó que las frecuencias de los alelos en su población ideal estaban en equilibrio. La conclusión de Yule tan novedosa como correcta, pero la tomó de una forma demasiado literal. Había desarrollado un único ejemplo, y creyó que las frecuencias alélicas de 0'5 y 0'5, representaban el único estado de equilibrio posible para un sistema de dos alelos. Por ejemplo, Yule creía que si aparecía un alelo A por mutación en una población cuyo conjunto de genes era sólo de *a*, entonces la frecuencia del alelo A aumentaría automáticamente hasta construir la mitad del conjunto de genes. Yule arguyó esta idea durante la discusión que siguió a una charla dada por R.C. Punnet. Punnet creía que Yule no tenía razón, pero no supo cómo probarlo.

Desde luego, ya hemos demostrado que Punnet estaba en lo cierto al rechazar la idea de Yule. Nuestros cálculos demuestran que una población con frecuencias alélicas de 0'6 y 0'4, también está en equilibrio. Sin embargo, lo que Punnet deseaba era una prueba generalizada. Esta prueba demostraría que cualesquiera frecuencias alélicas, siempre que sumaran 1, permanecerán sin cambio de una generación a la siguiente.
Punnet planteó el problema a su amigo matemático G.H.Hardy, que obtuvo la prueba en corto tiempo. Hardy simplemente repitió los cálculo que Yule había realizado, pero utilizando variables en lugar de frecuencias alélicas específicas tal como Yule había hecho. Los cálculos de Hardy para un caso general demostraron realmente que cualesquiera frecuencias alélicas estarán en equilibrio.

Se descubrió que, el médico alemán Wilhelm Weinberg defendió una tesis doctoral en la que llegó a las mismas conclusiones, pero incluyendo numerosos ejemplos.

A partir de entonces, esta demostración se conoció como el equilibrio de Hardy-Weinberg (EH).

Los estadounidenses adoptaron el nombre de Hardy-Weinberg-Castle, ya que en 1903 el genetista estadounidense William E. Castle publicó un artículo que planteaba una conclusión similar utilizando ejemplos numéricos.
## Hardy-Weinberg

El equilibrio de Hardy-Weinberg (EH), también conocido como ley de Hardy-Weinberg, solo se cumple en poblaciones ideales (irreales), ideales en el mismo sentido que las leyes de la física, por lo que es imperativo comprender sus limitaciones.

Consideraremos una población ideal para comprender el EH:
- Una población de organismos diploides con reproducción sexual, en la que se cumplen las leyes de la herencia de Mendel.
- Los individuos sexualmente maduros de cualquier generación (t) producen gametos en una cantidad suficientemente grande (no limitante).
- El apareamiento de los individuos de la población es aleatorio, independientemente de sus fenotipos y genotipos (PANMIXIA, POBLACIÓN PANMÍTICA).
- La conjugación aleatoria de gametos (PANGAMIA) en la generación t genera cigotos de la generación t+1.
## Modelo general

En un locus con 2 alelos A1 y A2. Denominaremos a la frecuencia A1 en el conjunto de genes *p* y a la frecuencia de A2 *q*. Hay sólo 2 alelos en la población, por lo que
$$
p+q=1
$$
El primer paso es permitir que los gametos del conjunto de genes se combinen para producir zigotos. Los zigotos que se producen y el cálculo que especifica la probabilidad de cada caso. Por ejemplo, si cogemos un óvulo al azar, la probabilidad de que sea de genotipo A1 es *p*. Cuando un espermatozoide fertiliza un óvulo, la probabilidad de que sea de genotipo A1 es *p*. Por consiguiente, la probabilidad de que presenciemos la producción de un zigoto A1A1 es
$$
p*p=p^{2}
$$
La siguiente imagen muestra que el apareamiento al azar en nuestro conjunto de genes a zigotos en las siguientes proporciones:
![[Pasted image 20251026164022.png]]
Esto confirma que hemos tenido en cuenta a todos los zigotos. El mismo resultado se puede demostrar algebraicamente sustituyendo *q* por(1-p) en la expresión 
$$
p^{2}+2pq+q^{2}
$$
y simplificando.

Hemos ido de las frecuencias alélicas en el conjunto de genes a las frecuencias genotípicas de los zigotos. Ahora dejaremos que los zigotos lleguen a adultos y que los adultos produzcan gametos para formar el conjunto de genes de la siguiente generación.
Podemos calcular la frecuencia del alelo A1 en el nuevo conjunto de genes como siguie. Ya que los adultos de genotipo A1A1 constituyen una proporción p² de la población, producirán p² gametos. Todos estos gametos llevarán el alelo A1. De igual manera, los adultos de genotipo A1A2 constituyen una proporción 2*pq* de la población, y producirán 2*pq* gametos. La mitad de estos gametos llevarán el alelo A1. Por ello, la fracción total de gametos del conjunto de genes que llevarán el alelo A1 es
$$
p^{2}+ (\frac{1}{2})2pq=p^{2}+pq
$$
Podemos simplificar esta expresión sustituyendo *q* por (1-*p*)  en la parte derecha. Esto da
$$
\begin{align}
p^{2}+pq=p^{2}+p(1-q) \\
=p^{2}+p-p^{2} \\
=p
\end{align}
$$
![[Pasted image 20251026164923.png]]
En la figura 5.8 se presenta gráficamente este cálculo. La figura también muestran un cálculo que establece que la fracción de gametos del conjunto de genes que llevan el alelo A2 es *q*. Asumimos por principios que *q* y *p* suman 1, por lo que sabemos que hemos tenido en cuenta todos los gametos.

Comenzamos con frecuencias alélicas *p* y *q* en nuestro conjunto de genes de la población. Seguimos a los alelos a través de los zigotos y los adultos y hasta el conjunto de genes de la siguiente generación. Las frecuencias alélicas en el nuevo conjunto de genes sigue siendo *p* y *q*. Las frecuencias alélicas *p* y *q* pueden presentar cualquier valor entre 0 y 1, siempre y cuando sumen. En otras palabras, *cualesquiera* frecuencias alélicas se mantendrán en equilibrio, no sólo *p=q* =0,5 como creía Yule.

Si los ratones se aparean aleatoriamente y todos los individuos tienen la misma probabilidad de reproducirse, las frecuencias genotípicas en la siguiente generación serán las descritas en la siguiente tabla:
![[Pasted image 20251026170007.png]]

Éste es un resultado importante. Al comienzo del capítulo definimos la evolución como el cambio de las frecuencias alélicas en las poblaciones. Los cálculos que acabamos de realizar demuestran, que dados supuestos simples, en poblaciones que siguen las reglas de la genética mendeliana, las frecuencias alélicas no cambian.
Hemos presentado este resultado como el trabajo de Hardy-Weinberg donde se obtuvo 2 conclusiones:
1. Las frecuencias alélicas de una población se mantendrán constantes generación tras generación.
2. Si las frecuencias alélicas de una población son *p* y *q*, las frecuencias genotípicas serán *p²*, *2pq* y *q²*.

Por lo tanto, una población alcanzará un HWE cuando:
- Los individuos se aparean aleatoriamente.
- No existe ningún mecanismo evolutivo (selección, mutación, deriva genética o flujo génico) que altere las frecuencias alélicas.

El HWE es una situación ideal que puede utilizarse como hipótesis nula para determinar la acción de los mecanismos evolutivos o la presencia de apareamiento no aleatorio en poblaciones naturales.

Características del equilibrio HWE
1. Organismos diploides.
2. Población con reproducción sexual.
3. Generaciones no superpuestas.
4. Apareamiento aleatorio.
5. Población muy grande (infinita).
6. Ausencia de migración.
7. Se puede asumir que la mutación es irrelevante.
8. La selección natural no actúa sobre el gen considerado.

Por tanto, las frecuencias de alelos y genotipos en generaciones consecutivas están relacionadas según las expresiones:
$$
P=p^{2}; Q=q^{2};H=2pq
$$
y permanecerán constantes después de la generación hasta que cambien las condiciones.
### Ejemplo numérico

Hay que considera que en el proceso de apareamiento al azar ocurre de la siguiente manera: tomamos todos los óvulos y esperma que producen todos los adultos de la población y los mezclamos en un "barril", al cual llamaremos *gene pool* (conjunto de genes). Cada espermatozoide se desplaza hasta colisionar al azar con un óvulo para producir un zigoto.
En nuestro ejemplo los organismos son diploides, por lo que cada uno tiene en el locus A dos alelos. Pero los adultos producen sus óvulos y esperma por meiosis.
Siguiendo la ley de la segregación de Mendel, cada gameto recibe exactamente un alelo del locus A. Imagina que le 60% de los óvulos y del esperma reciben el alelo A y que el 40% recibe el alelo *a*. En otras palabras, la frecuencia del alelo A en el conjunto de genes es de 0'6, y la del alelo *a* de 0'4.
¿Qué sucede cuando un espermatozoide encuentra a un óvulo? Por ejemplo, ¿qué fracción de zigotos se producirán con el genotipo AA? En la figura 5.2 se muestran los cuatro combinaciones posibles de óvulos y esperma, los zigotos que se producen y un cálculo especificando la probabilidad de cada uno de ellos. Por ejemplo, si tomamos un óvulo al azar, hay una probabilidad del 60% de que tenga el genotipo *A* . Cuando un espermatozoide va fertilizar a un óvulo, hay un 60% de probabilidad de que el esperma tenga el genotipo *A*. La probabilidad de que presenciemos la producción de un zigoto *AA* será por consiguiente,
$$
0'6*0'6=0'36
$$
Si observamos la formación de todos los zigotos, el 36% tendrá el genotipo *AA*. Los cálculos de la figura 5.2 muestran que el aparemiento al azar en el conjunto de genes dará lugar a las siguientes proporciones de zigoto:

| *AA* | *Aa* | *aa* |
| ---- | ---- | ---- |
| 0'36 | 0'48 | 0'16 |
(La categoría *Aa* a los heterozigotos producidos por la combinación bien de un óvulo *A* y un espermatozoide *a*, o de un óvulo *a* con un espermatozoide *A*). Advierte que,
$$
0'36+0'48+0'16=1
$$
Esto confirma que hemos tenido en cuenta a todos los zigotos. La figura 5.3 muestra una representación geométrica de los mismos cálculos.
![[Pasted image 20251026183423.png]]
Dejemos ahora que los zigotos se desarrollen hasta adultos y que los adultos produzcan gametos para obtener el conjunto de genes de la siguiente generación.
## Cálculo de frecuencias alélicas a partir de frecuencias genotípicas

En el nuevo conjunto de genes, podemos calcular la frecuencia del alelo *A* de la siguiente manera. Ya que los adultos de genotipo *AA* constituyen el 36% de la población, producirán el 36% de los gametos. Todos estos gametos llevarán el alelo *A*. Así mismo, los adultos de genotipo *Aa* constituyen el 48% de la población, y producirán el 48% de los gametos. La mitad de estos gametos llevarán el alelo *A*. Por ello, la fracción de gametos del conjunto de genes que lleva el alelo *A* es
$$
0'36+(\frac{1}{2})0'48=0'6
$$

En la figura 5.4 se presenta este cálculo gráficamente. La figura también muestra un cálculo que establece que la fracción de gametos del conjunto de genes que llevan el alelo *a* es 0'4. Advierta que:
$$
0'6+0'4=1
$$
![[Pasted image 20251026183346.png]]
Esto confirma que hemos tenido en cuenta a todos los gametos. En la figura 5.5. se muestra una representación geométrica de los mismos cálculos.
![[Pasted image 20251026183317.png]]
Hemos cerrado el círculo y hemos llegado exactamente a donde comenzamos. Comenzamos con frecuencias alélicas del 60% para A y del 40% para a en el conjunto de genes de la población. Seguimos a los alelos a través de los zigotos y de los adultos y en el conjunto de genes de la siguiente generación. Las frecuencias alélicas en el nuevo conjunto de genes es también el 60% y el 40%. Por ello, las frecuencias alélicas de A y de a se encuentran en equilibrio en nuestra población: no cambian de una generación a la siguiente. La población no evoluciona.

Con mucha frecuencia, se desconocen las frecuencias genotípicas. Cuando carecemos de información para derivar algunas frecuencias genotípicas debido a la dominancia, es decir, A > a, p(A) = p, p(a) = q, es posible invocar el equilibrio de Hardy-Weinberg si existen razones para que esto se cumpla; como la codominancia, herencia intermedia que alteran los fenotipos.

$$
q=\sqrt{Q}; p=1-p; P=p^{2}; H=2pq
$$
## Comprobación del equilibrio HWE

La comprobación se realiza mediante la prueba del x².
$$
x^{2}=\sum_{i} \frac{(o_{i}-e_{i})^{2}}{e_{i}}
$$
Por lo tanto, los grados de libertad a utilizar en la prueba son: «número de clases» – «número de parámetros libres en el modelo». Es el número de sumandos del estadísiticos menos uno, menos el total de parámetros independientemente a partir  de la muestra.


> [!DANGER] Grados de libertad
> Debemos comparar este valor con un χ2 con 1 gl, ya que hemos utilizado 2 parámetros de la muestra (N y p) para calcular los valores esperados.


## Equilibrio de Hardy-Weinberg con >2 alelos o poliploides

Imagina un locus con varios alelos. Podemos denominar a los alelos *Ai, Aj, Ak*, y así sucesivamente y podemos representar sus frecuencias en el conjunto de genes con las variables *pi,pj,pk* y así sucesivamente. La formación de un zigoto con genotipo *Ai,Aj* precisa de la unión de un óvulo *Ai* y un espermatozoide *Aj*. Así, la frecuencia de cualquier genotipo homozigoto *AiAi* será pi².
La formación de un zigoto con genotipo *AiAj* requiere bien la unión de un óvulo *Ai* con un esperma *Aj*, o de un óvulo *Aj* con un esperma. Así, la frecuencia de cualquiera genotipo heterozigoto *AiAj* es 2*pipj*.
Por ejemplo, si hay 3 alelos con frecuencias *p1,p2 y p3*, de tal manera que
$$
p_{1}+p_{2}+p_{3}=1
$$
entonces, las frecuencias genotípicas serán
$$
(p_{1}+p_{2}+p_{3})^{2}=p^{2}+p^{2}_{2}+p^{2}_{3}+2p_{1}p_{2}+2p_{1}p_{3}+2p_{2}p_{3}
$$
y las frecuencias alélicas no cambiaran de generación en generación.

Un locus con n alelos de frecuencias Ai. Las frecuencias genotípicas se derivan del polinomio y, en consecuencia, las frecuencias genotípicas son:

$$
\begin{align}
\left( \sum ^{n}_{i=1} \right)f(A_{i})^{2} \\
f(A_{i}A_{i})=f(A_{i})^{2} \ y \ f(A_{i}A_{j})=2f(A_{i})f(A_{j})
\end{align}
$$

K-ploidía con n alelos de frecuencias Ai. Las frecuencias del genotipo se derivan del polinomio:

$$
\begin{align}
\ \left( \sum ^{n}_{i=1} \right)f(A_{i})^{k}
\end{align}
$$


> [!SUCCESS] HW en poliploides
>  El HWE no puede aplicarse a más de un locus porque el equiibrio en cada locus individual no implica el equilibrio de las frecuencias genotípicas. 
>  Los distintos loci no recombinan libremente si están ligados en el mismo cromosomas y su independencia depende de la recombinación (que a su vez depende de la distancia física citogenética).


## Equilibrio HWE y heterozigosidad

La heterozigosidad es máxima cuando p=q=0.5
En cualquier caso, dados p y q, el equilibrio H-W es igual a la heterocigosidad esperada.
Cabe destacar que la heterocigosidad se utiliza frecuentemente para medir la variabilidad genética.
La diversidad genética, Π, es la heterocigosidad esperada H en el equilibrio de Hardy-Weinberg.
$$
\pi=\sum_{i\neq j}2p_{i}p_{j}=1-\sum_{i}p^{2}=E(H)
$$

![[Pasted image 20260109122257.png]]
## Caso especial de genes ligados al sexo

Consideremos un gen en el cromosoma X con dos alelos A y a, con frecuencias p y q respectivamente.
En equilibrio, las frecuencias del genotipo femenino son:
$$
\begin{align}
f(X^{A}X^{A})=p^{2} \\
f(X^{a}X^{a})=q^{2} \\
f(X^{A}X^{a})=2pq
\end{align}
$$
Y las frecuencias del genotipo masculino son:
$$
\begin{align}
f(X^{A}Y)=p \\
f(X^{a}Y)=q
\end{align}
$$
, ya que solo hay un alelo.
Una diferencia importante con los genes autosómicos es que el equilibrio no se alcanza en una sola generación.
Cambio en las frecuencias de alelos y genotipos en hombres y mujeres.

En este caso el equilibrio no se obtiene en la primera generación, sino que el sistema asciende asintóticamente  a dicho equilibrio. Para ello debemos  partir desde individuos heterozigotos 
### Ejemplo numérico
![[Pasted image 20251026202721.png]]
Aunque el equilibrio no se alcanza inmediatamente, sólo se necesitan unas pocas generaciones (8-10).



> [!SUCCESS] Conclusiones de HW 
> La genética de poblaciones es el resultado de la fusión del mendelismo y el darwinismo a principios del siglo XX.
El equilibrio de Hardy-Weinberg es una hipótesis nula sobre las frecuencias genotípicas y puede comprobarse estadísticamente.
Las frecuencias alélicas pueden calcularse cuando se conocen las frecuencias genotípicas.
Las frecuencias genotípicas solo pueden deducirse a partir de las frecuencias alélicas si se asume el equilibrio de Hardy-Weinberg.
El equilibrio de Hardy-Weinberg puede extenderse a más de dos alelos y a organismos con cualquier valor de ploidía.
Para los genes autosómicos, el equilibrio se alcanza en una sola generación.
Para los genes ligados al sexo, la función es asintótica, pero rápida.


---
# Selección natural: Modelo solo un locus
## Introducción

### Aptitud biológica o darwiniana

- La aptitud biológica (eficacia biológica) describe el éxito reproductivo individual y equivale a la contribución promedio al acervo genético de la siguiente generación que realizan los individuos con un genotipo o fenotipo determinado.
- La aptitud de un genotipo se manifiesta a través de su fenotipo, que también se ve afectado por el entorno de desarrollo. La aptitud de un fenotipo determinado también puede variar en distintos entornos selectivos.
- La aptitud es una propiedad, no de un individuo, sino de una clase de individuos. Por lo tanto, el «número esperado de descendientes» se refiere al número promedio, no al número producido por un solo individuo.
- La aptitud absoluta (W) de un genotipo se define como el cambio proporcional en la abundancia de ese genotipo a lo largo de una generación, atribuible a la selección.
- La aptitud relativa (w o ω) de un genotipo indica el cambio en la frecuencia de un genotipo en relación con otro. Se elige un genotipo como referencia y su aptitud relativa se establece en 1, y las aptitudes de los genotipos restantes se miden en relación con esta referencia.

> [!NOTE] Eficacia 
> Es la medida del **éxito reproductivo de un individuo o genotipo**, es decir, su capacidad para **sobrevivir y dejar descendencia viable** que contribuya a la siguiente generación en comparación con otros individuos de la población.

### Coeficiente de selección
- El coeficiente de selección (s, t…) mide hasta qué punto la selección natural actúa para reducir la contribución relativa de un genotipo dado a la siguiente generación con respecto al genotipo de referencia (con aptitud 1). Por consiguiente, la aptitud de este genotipo dado es w = 1 + s.
- Por ejemplo, una población con tres genotipos AA, Aa y aa con aptitudes relativas wAA, wAa y waa, respectivamente. El genotipo AA es la referencia, wAA = 1; por lo tanto, wAa = 1 + s y waa = 1 + t, donde s, t… miden la ventaja de aptitud (s, t… > 0) o desventaja (s, t… < 0) de Aa y aa con respecto a AA.

> [!NOTE] Coeficiente de selección
> Es una medida que indica **cuánto se reduce la eficacia biológica de un genotipo en comparación con el genotipo más apto** de la población.

## Selección: modelos de locus dialélico único
### Caso general

En una población tiene un conjunto de genes en el que alelo *A1* tiene una frecuencia *p* y el alelo *A2* una frecuencia *q*. Permitimos que los gametos se unan al azar para formar los zigotos, con genotipos *A1A1,A1A2 y A2A2*, y en las frecuencias *p²,2pq y q²* respectivamente.
Incorporamos la selección imaginando que los zigotos *A1A1* sobreviven hasta la madurez con una tasa *w11*, los zigotos *A1A2* sobreviven con una tasa *w12* y los zigotos *A2A2* sobreviven con una tasa *w22* . Todos los individuos que sobreviven dan lugar al mismo número de descendientes. Por consiguiente, la tasa de supervivencia de un genotipo es proporcional al éxito reproductivo durante la vida del genotipo, o eficacia. Por ello, nos referimos a la tasa de supervivencia como de eficacia. La eficacia media para el conjunto de la población, que se obtiene por la expresión:
$$
\bar{w}=p^{2}w_{11}+2pqw_{12}+q^{2}w_{22}
$$
La expresión para la eficacia promedio es del segundo tipo: multiplicamos la eficacia de cada genotipo por su frecuencia en la población y luego sumamos los resultados.
Calculemos ahora las frecuencias genotípicas de los adultos que sobreviven(justo antes de que sus gametos vayan al conjunto de genes). Las nuevas frecuencias genotípicas serán:
$$
\begin{align}
A_{1}A_{1}=\frac{p^{2}w_{11}}{\bar{w}} \\
A_{1}A_{2}=\frac{2pqw_{12}}{\bar{w}} \\
A_{2}A_{2}=\frac{q^{2}w_{22}}{\bar{w}}
\end{align}
$$
(En cada caso hemos dividido por la eficacia media para asegurarnos que las nuevas frecuencias todavía sumen 1.)

Finalmente, dejamos que los adultos se crucen y calculamos las frecuencias alélicas en el conjunto de genes:
Para el alelo *A1*: los individuos *A1A1* contribuyen con 
$$
\frac{p^{2}w_{11}}{\bar{w}}
$$
, los cuales son todos *A1*; si los individuos *A1A2* contribuyen con

$$
\frac{2pqw_{12}}{\bar{w}}
$$
gametos, de los cuales la mitad son *A1*. 
Así, la nueva frecuencia de *A1* es
$$
p^{2}w_{11}+\frac{pqw_{12}}{\bar{w}}
$$
Para el alelo *A2*: los individuos *A2A2* contribuyen con 

$$
\frac{2pqw_{12}}{\bar{w}}
$$
gametos, todos los cuales son *A2*; los individuos *A1A2* contribuyen con 

$$
\frac{q^{2}w_{22}}{\bar{w}}
$$
gametos, la mitad de los cuales son *A2*. Por ello, la nueva frecuencia de *A2* es

$$
pqw_{12}+\frac{q^{2}w_{22}}{\bar{w}}
$$

De esta forma confirmamos que las nuevas frecuencias de *A1* y *A2* suman 1.
Es instructivo calcular el cambio en la frecuencia del alelo *A1* de una generación a la siguiente. 

$$
\text{Este valor,}\vartriangle p,\text{es igual a la nueva generación del alelo A1, menos su frecuencia anterior}.
$$
$$
\begin{align}
\vartriangle p=p^{2}w_{11}+\frac{pqw_{12}}{\bar{w}}-p \\
=p^{2}w_{11}+\frac{pqw_{12}}{\bar{w}}-\frac{p\bar{w}}{\bar{w}} \\
=p^{2}w_{11}+\frac{pqw_{12}-p\bar{w}}{\bar{w}} \\
p=\frac{p}{\bar{w}}(pw_{11}+qw_{12}-\bar{w})
\end{align}
$$
La expresión final es útil porque muestra que el cambio en la frecuencia del alelo *A1* es proporcional a *(pw11+qw12-w(total)).*

La expresión*(*pw11+qw12-w*)* es igual a la eficacia media del alelo *A1* cuando se une al azar con otros alelos *(pw11+qw22)* menos la eficacia media de la población(w). En otras palabras, si los individuos que llevan *A1* tienen una eficacia superior a la media, entonces el alelo *A1* aumentara en frecuencia.

El cambio en la frecuencia del alelo *A2* de una generación a la siguiente es:

$$
\begin{align}
\vartriangle q=\frac{pqw_{12}+q^{2}w_{22}}{\bar{w}}-p \\
=\frac{p}{\bar{w}}(pw_{12}+qw_{22}-\bar{w})
\end{align}
$$
Por tanto las características serán:
- Un locus = A
- Dos alelos = A1 y A2
- El alelo antiguo es A1, el nuevo es A2
- Tres genotipos posibles = A1A1, A1A2 y A2A2
- Cada genotipo tiene una aptitud relativa diferente (w11, w12, w22)
- Nos interesa el destino del nuevo alelo A2
- La aptitud del genotipo antiguo (A1A1) se establece en 1.
- La aptitud relativa de los dos nuevos genotipos posibles (A1A2 y A2A2) se define comparativamente como 1 + s o 1 + t, donde s y t son los coeficientes de selección.
- En comparación con el alelo antiguo (A1), el nuevo (A2) puede ser perjudicial, neutral o ventajoso, dependiendo del efecto sobre la aptitud del portador.
![[Pasted image 20251027085030.png]]
![[Pasted image 20251027085043.png]]
$$
\begin{align}
\vartriangle p=p'-p=\frac{p^{2}(w_{11}+pqw_{12})}{\bar{w}}-p=\frac{p^{2}w_{11}+pqw_{12}-p\bar{w}}{\bar{w}} \\
\vartriangle p\bar{w}=p^{2}w_{11}+pqw_{12}-p^{3}w_{11}-2p^{2}qw_{12}-pq^{2}w_{22} \\
\vartriangle p\bar{w}=w_{11}(p^{2}-p^{3})+w_{12}(pq-2p^{2}q)-pq^{2}w_{22} \text{como p²-p³=p²q} \\
\vartriangle p\bar{w}=p^{2}w_{11}+pqw_{12}-p^{3}w_{11}-2p^{2}qw_{12}-pq^{2}w_{22} \\
\vartriangle p\bar{w}=pq[pw_{11}+w_{12}(1-2p)qw_{22}]\text{y como 1-2p=q-p} \\
\vartriangle p\bar{w}= pq(pw_{11}+qw_{12}-pw_{12}-qw_{22}) \\
\vartriangle p\bar{w}= pq[w_{11}-w_{12}+q(w_{12}-w_{22})]
\end{align}
$$

$$
\begin{align}
\vartriangle q\bar{w}=q'-q=\frac{q^{2}w_{22}+pqw_{12}}{\bar{w}}-q=\frac{q^{2}w_{22}+pqw_{12}-q\bar{w}}{\bar{w}} \\
\vartriangle q\bar{w}= q^{2}w_{22}+pqw_{12}-q(p^{2}w_{11}+2pqw_{12}+q^{2}w_{22})\\
\vartriangle q\bar{w}=q^{2}w_{22}+pqw_{12}-p^{2}qw_{11}-2pq^{2}w_{12}-q^{3}w_{22} \\
\vartriangle q\bar{w}=(q^{2}-q^{3}w_{22})+(pq-2pq^{2}w_{12})-p^{2}qw_{11} \text{como q²-q³=pq²} \\
\vartriangle q\bar{w}= pq[qw_{22}+(1-2p)w_{12}-pw_{11}]\text{como 1-2q=p-q}\\
\vartriangle q\bar{w}=pq(qw_{22}+pw_{12}-qw_{12}-pw_{11})\\
=-pq[p(w_{11}-w_{12}+q(w_{12}-w_{22}))] \\
\vartriangle q\bar{w}=pq[p(w_{11}-w_{12})+q(w_{12}-w_{22})]
\end{align}
$$


### Añadiendo la selección al análisis de HW: Cambios en las frecuencias alélicas

Todo esto implica cambios en las frecuencias alélicas debido a la selección. Partimos que la población tiene individuos tienen locus *B* que afecta a la probabilidad de supervivencia. Supongamos, como que la frecuencia *B1* en el conjunto de genes es de 0'6, y la frecuencia del alelo B2 es 0'4. Después del apareamiento al azar, obtenemos unas frecuencias genotípicas para *B1B1, B1B2 y B2B2* de 0'36,0'48 y 0'16. El resto de nuestros cálculos serán más simples si damos a la población de zigotos un tamaño definido, por lo que imaginemos que hay 1000 zigotos: 

| B1B1 | B1B2 | B2B2 |
| ---- | ---- | ---- |
| 360  | 480  | 160  |
Estos zigotos están representados por un gráfico de barras en la figura. Seguiremos a los individuos que se desarrollan a partir de estos zigotos hasta que lleguen adultos. Aquéllos que sobrevivan se cruzarán para producir el conjunto de genes de la generación siguiente.

![[Pasted image 20251027020951.png]]
Incorporamos la selección estipulando que los genotipos difieren en sus tasas de supervivencia. Todos los individuos *B1B1* sobreviven, y también lo hacen el 75% de los individuos *B1B2* y el 50% de los *B2B2*. Como se muestra en la siguiente imagen, en la población hay ahora 800 adultos:

| *B1B1* | *B1B2* | *B2B2* |
| ------ | ------ | ------ |
| 360    | 360    | 80     |
En los adultos, las frecuencias de los 3 genotipos serán:

| *B1B1*       | *B1B2*       | *B2B2*     |
| ------------ | ------------ | ---------- |
| 360/800=0'45 | 360/800=0'45 | 80/800=0'1 |
Cuando estos adultos produzcan gametos, la frecuencia del alelo *B1* en el nuevo conjunto de genes será igual a la frecuencia de *B1B1* entre los adultos que sobrevivem más la mitad de la frecuencia de *B1B2*. Este cálculo y el de la frecuencia para el alelo *B2* son como sigue:

$$
\begin{align}
B_{1}→0'45+\left( \frac{1}{2} \right)0'45=0'675 \\
B_{2}→\left( \frac{1}{2} \right)0'45+0'1=0'325
\end{align}
$$
La frecuencia del alelo *B1* ha aumentado en un porcentaje del 7'5. La frecuencia del alelo *B2* ha disminuido en  la misma cantidad.

**La selección ha dado lugar a que no se cumpla la conclusión 1 del análisis de HWE. La población ha evolucionado en respuesta a la selección.**

Utilizamos una selección fuerte para insistir en nuestro ejemplo numérico. En la naturaleza, las diferencias en supervivencia raramente son tan elevadas como para ocasionar cambios importantes en las frecuencias alélicas en una sola generación. Sin embargo, si la selección continúa actuando durante muchas generaciones, incluso pequeños cambios en las frecuencias de un largo período. En la figura 5.10 se presentan cambios acumulativos en frecuencias alélicas que se pueden obtener por selección. 

La figura se basa en un modelo poblacional similar al utilizado en los ejemplos numéricos procedentes, excepto en que las frecuencias alélicas iniciales son 0'01 para *B1* y 0'99 para *B2*. La línea amarilla presenta el cambio en frecuencias alélicas cuando las tasas de supervivencia son del 100% para *B1B1*, del 90% para *B1B2* y del 80% para *B2B2*. La frecuencia del alelo *B1* pasa en menos de 100 generaciones de 0'01 a 0'99. Con esquemas de selección más débiles, la frecuencia de *B1* varía más lentamente, pero de manera inevitable.

### Investigaciones experimentales sobre el cambio de las frecuencias alélicas por selección

Douglas Cavener y Michael Clegg (1981) documentaron el cambio acumulativo en fre-
cuencias alélicas a lo largo de muchas generaciones en un experimento de selección natural en el laboratorio con la mosca de la fruta *(Drosophila melanogaster)*. La mosca de la fruta, como muchos otros animales, sintetiza una enzima que degrada el etanol, el ingrediente activo venenoso de la cerveza, del vino y de la fruta en putrefacción. Esta enzima se denomina alcohol deshidrogenasa, o ADH. Esta población tenía en el locus de la ADH tenían dos alelos Adh^f y el ADH^s.
Separaron las moscas en función del tipo de alimento que le daban: unas reciban alimento rociado con etanol y otras alimento normal. La elección de los padres fueron al azar para simular la selección natural. Además utilizaron ambientes diferentes.

Tras unas pocas generaciones apenas hubo algún cambio notable a largo plazo en la población de control, por otro lado, en  la  población  experimental se observó  un descenso de la frecuencia del ADHŝ.

La única diferencia entre los dos tipos de población es que las experimentales tienen etanol en su alimento. Esto sugiere que es la ausencia de selección la condición que no se cumple en las poblaciones experimentales. Las moscas con el alelo AdhF parece que tienen mayor éxito reproductivo (mayor eficacia) que las moscas con el alelo AdhS cuando hay etanol en el alimento. 

Cavener y Clegg advirtieron que este resultado está de acuerdo con el hecho de que extractos del alcohol deshidrogenasa de homozigotos AdhF degradan el etanol dos veces más rápido que los extractos del alcohol deshidrogenasa de homozigotos AdhS. No está claro si las moscas con el alelo AdhF tiene una mayor eficacia porque tiene una mayor tasa de supervivencia o porque dan lugar a más descendencia.
En conclusión, la eficiencia de la selección depende de las frecuencias iniciales y de los valores de aptitud relativos.

![[Pasted image 20251027021020.png]]


> [!SUCCESS] Frecuencias alélicas bajo el peso de la selección
> Cambios en la frecuencia del alelo ADHF del gen de la alcohol deshidrogenasa (el otro alelo es ADHS) en cuatro poblaciones experimentales de *Drosophila melanogaster.*
En las poblaciones cuya alimentación se complementó con etanol, la frecuencia del alelo F aumentó.
Por el contrario, en las poblaciones control (sin etanol añadido), la frecuencia del alelo F oscila alrededor del valor inicial, f (ADHF) = 0,35, f (ADHS) = 0,65.

### Cálculo de las frecuencias genotípicas

Los cálculos y el ejemplo que acabamos de discutir demuestran que la selección puede dar a lugar que las frecuencias alélicas cambien a lo largo de las generaciones. La selección invalida la  conclusión 1 del análisis de HW. Consideremos ahora de qué manera la selección afecta a la conclusión 2 del análisis de HW. En un población sometida a selección,¿podemos todavía calcular las frecuencias genotípicas multiplicando las frecuencias alélicas?
![[Pasted image 20251027124633.png]]

A menudo no podemos hacerlo. Como antes, que usamos una población con 2 alelos en un locus que afecta a la supervivencia: *B1 y B2*. Supongamos que las frecuencias iniciales de cada alelo en el conjunto es de 0'5. Después del apareamiento al azar, las frecuencias genotípicas de *B1B1, B1B2 y B2B2* son 0'25, 0'5 y 0'25, respectivamnete. El resto de nuestros cálculos serán más simples si damos  a la población de zigotos un tamaño dado, por lo que imaginemos que hay 100 zigotos.

| B1B1 | B1B2 | B2B2 |
| ---- | ---- | ---- |
| 250  | 500  | 250  |
Estos zigotos están representados en un gráfico de barras en la figura. Seguiremos a los individuos que se desarrollan de estos zigotos hasta el estado adulto. Aquellos que sobrevivan se cruzarán para producir el conjunto de genes de la siguiente generación.
Incorporamos la selección estipulando que los genotipos se diferencian en sus tasas de supervivencia. El 50% de los individuos *B1B1* sobrevive, todos los individuos *B1B2* sobreviven y el 50% de los *B2B2* sobrevive. Como se muestra en la siguiente imagen, ahora habrá 750 adultos en la población:

| B1B1 | B1B2 | B2B2 |
| ---- | ---- | ---- |
| 125  | 500  | 125  |
La frecuencia de los 3 genotipos será la siguiente:

| B1B1  | B1B2  | B2B2  |
| ----- | ----- | ----- |
| 0'167 | 0'667 | 0'167 |
Cuando estos adultos produzcan, las frecuencias de los 2 alelos en el nuevo conjunto de genes será:


| B1  | B2  |
| --- | --- |
| 0'5 | 0'5 |
![[Pasted image 20260109125222.png]]
A pesar de la fuerte selección en contra de los homozigotos, la frecuencia de los alelos no ha cambiado; **la población no ha evolucionado**

Sin embargo, advierta que la selección *ha dado lugar* a que no se cumpla la conclusión 2 del análisis de HW. **Ya no podemos calcular las frecuencias genotípicas de los adultos supervivientes multiplicando las frecuencias de alelos.**


> [!SUCCESS] Efectos de la selección a las frecuencias alélicas y genotípicas
>Bajo la selección una población la 2 conclusión de HW se rompe pero rara vez la selección provoca grande cambios en las frecuencias y en tal caso, en una generación de apareamiento al azar devolverá inmediatamente a los genotipos al equilibrio HW.

## Selección sobre alelos recesivos y dominantes

Los datos recogidos por Peter Dawson son un ejemplo de cómo la recesividad y la dominancia afectan al curso de la evolución. Dawson había estudiado una colonia de laboratorio del gorgojo del trigo(*Tribolium castaneaum*), y había identificado un gen,
que llamaremos locus 1. Este locus tenía dos alelos: *y l*. Los individuos con genotipos
/ y /l eran fenotípicamente normales, mientras que los individuos con genotipo l/l
no sobrevivían. En otras palabras, l es un alelo letal recesivo.

Dawson recogió heterozigotos de su colonia de gorgojos del trigo y los utilizó para
establecer dos nuevas poblaciones experimentales.Ya que todos los fundadores eran heterozigotos, la frecuencia inicial de los dos alelos era 0,5 en las dos poblaciones.Ya que los individuos l/l tienen una eficacia cero, Dawson esperaba que su población evolucionara hacia frecuencias cada vez más bajas del alelo l y más altas del alelo . Dawson utilizó las ecuaciones derivadas en el Cuadro 5.3 y el método descrito en el Cuadro 5.6 para hacer predicciones cuantitativas del curso de la evolución. Luego dejó que sus poblaciones evolucionaran durante unas doce generaciones, midiendo en cada generación las frecuencias de los dos alelos.
Los resultados aparecen en la Figura 5.14. Los datos de Dawson están muy de acuerdo con sus predicciones teóricas. Al principio, la frecuencia del alelo letal recesivo disminuye rápidamente (Figura 5.14a). En la segunda generación ya ha bajado del 0,5 a, aproximadamente, el 0,25. Sin embargo, a medida que la evolución progresaba, la reducción en frecuencia del alelo letal se hizo más lenta. Entre las generaciones 10 y 12 la frecuencia no disminuyó en absoluto. 

![[Pasted image 20260109123248.png]]
 
El equilibrio de Hardy-Weinberg explica el porqué. Imagine primero un alelo recesivo que es frecuente: su frecuencia es, por ejemplo, 0,95. Así, el alelo dominante tiene una frecuencia del 0,05. Multiplicando las frecuencias alélicas podremos calcular las frecuencias genotípicas:

| *AA*   | Aa    | aa     |
| ------ | ----- | ------ |
| 0'0025 | 0'095 | 0'9025 |
Casi un 10% de los individuos de la población tienen fenotipo dominante, mientras que
el 90% restante tienen fenotipo recesivo. Ambos fenotipos están razonablemente bien
representados y si se diferencian en eficacia, las frecuencias alélicas de la siguiente generación pueden ser sustancialmente distintas. Imaginemos ahora que el alelo recesivo es raro: su frecuencia es 0,05. Así, el alelo dominante tiene una frecuencia de 0,95. Las frecuencias genotípicas son

| *AA*   | Aa    | aa     |
| ------ | ----- | ------ |
| 0'9025 | 0'095 | 0'0025 |

Prácticamente el 100% de la población tiene el fenotipo dominante, mientras que el fenotipo recesivo está casi ausente.Aunque los fenotipos se diferencien mucho en eficacia, hay tan pocos de los fenotipos minoritarios que habrá muy poco cambio en frecuencias alélicas en la generación siguiente. En una población con apareamiento al azar, la mayoría de las copias del alelo recesivo raro se encuentran escondidas fenotípicamente en los individuos heterozigotos. Para un tratamiento algebraico de la selección sobre los alelos recesivos y dominantes véase el Cuadro 5.7(Tratamiento algebraico de la selección sobre alelos recesivos y dominantes)

![[Pasted image 20260109141837.png]]

> [!SUCCESS] Experimento de Dawson
> Demuestra que la teoría de la genética de poblaciones, a pesar de sus suposiciones simplificadas, nos permite predecir con mucha exactitud el curso de la evolución, al menos en las condiciones controladas del laboratorio.

### Selección sobre el alelo recesivo

> [!NOTE] Coeficiente de selección
> Indica la fuerza de la selección sobre los homozigotos o heterozigotos relativa a los otros genotipos


| *WAA* | *WAa* | *Waa* |
| ----- | ----- | ----- |
| 1     | 1     | 1+s   |
Los valores positivos de *s*  indican selección a favor del alelo recesivo; los  valores negativos de *s* indican selección en contra del alelo recesivo.
Es necesario la ecuación de la siguiente generación de la frecuencia *q*, es decir, *q'*.
$$
q'=\frac{pqw_{Aa}+q^{2}w_{aa}}{\bar{w}}=\frac{pqw_{Aa}+q^{2}w_{aa}}{p^{2}w_{AA}+2pqw_{Aa}+q^{2}w_{aa}}
$$
Sustituyendo los valores de eficacia y (1-p) por *p* y simplificando, obtendremos
$$
q'=\frac{q(1+sq)}{1+sq^{2}}
$$
Si *a* es un letal recesivo, entonces *s* es igual *a-1*. 
Sustituyendo este valor en la ecuación anterior tendremos
$$
q'=\frac{q(1-q)}{1-q^{2}}=\frac{q(1-q)}{(1-q)(1+q)}=\frac{q}{(1+q)}
$$

### Selección sobre el alelo dominante

| *WAA* | *WAa* | *Waa* |
| ----- | ----- | ----- |
| 1+s   | 1+s   | 1     |
En este caso la selección favorece al alelo *A*, por tanto, afecta tanto a los individuos en homozigosis *AA* así como los heterozigotos *Aa* respecto al homozigoto *aa*.
$$
p'=\frac{p^{2}w_{AA}+pqw_{Aa}}{\bar{w}}=p^{2}w_{AA}+\frac{pqw_{Aa}}{p^{2}w_{AA}+2pqw_{Aa}+q^{2}w_{aa}}
$$
Lo mismo que en el caso  anterior  se sustituye *q* por *(1-p)* y simplificando se obtiene:
$$
p'=\frac{p(1+s)}{1+2sp-sp^{2}}
$$
Si **A* es letal dominante**, *s* es igual a  -1. Sustituyendo  este  valor en la ecuación anterior se ve  que el letal dominante **se elimina de la población en una sola generación.**

### Selección sobre los alelos recesivos en comparación  con la selección sobre los alelos dominantes.

La selección sobre los alelos recesivos y la selección sobre los alelos dominantes son lados opuestos de la misma moneda. La selección en contra de un alelo recesivo es
selección a favor del alelo dominante y viceversa.

En la Figura 5.15a (izquierda) se muestran 100 generaciones de evolución en una población ideal sometida a **selección contra un alelo recesivo y a favor del alelo dominante.** Al principio, la frecuencia de los alelos cambia rápidamente. Sin embargo, a medida que **el alelo recesivo se hace más raro, la tasa de evolución disminuye** drásticamente. Cuando el alelo recesivo es raro, la mayoría de las copias se encuentran en los individuos heterozigotos de la población, en donde se encuentran realmente ocultos al efecto de la selección.

La figura también muestra (derecha) la eficacia media de la población (véase el Cuadro 5.3) en función de la frecuencia del alelo dominante. A medida que el alelo
dominante se va haciendo más frecuente, la eficacia media de la población aumenta. La eficacia media se maximiza cuando el alelo favorecido alcanza una frecuencia del
100%. Las gráficas de la eficacia media en función de la frecuencia alélica se denominan a menudo **paisajes adaptativos.**

La Figura 5.15b (izquierda) muestra 100 generaciones de evolución en una población ideal sometida a **selección a favor del alelo recesivo y en contra del alelo dominante.**
Al principio la frecuencia de los alelos cambia lentamente. El alelo recesivo es raro, la mayoría de las copias presentes se encuentran en los heterozigotos y la selección no
puede verlos. Sin embargo, a medida que los alelos recesivos se hacen lo bastante frecuentes como para que aparezca una fracción sustancial de homozigotos, la tasa de
evolución aumenta espectacularmente. Una vez se acelera el ritmo de la evolución, los alelos recesivos favorables alcanzan rápidamente una frecuencia del 100%. Es decir, el
alelo recesivo queda fijado en la población.

La figura también muestra (derecha) la eficacia media de la población (véase el Cuadro 5.3) en función de la frecuencia del alelo recesivo. A medida que el alelo recesivo se va haciendo más frecuente, la eficacia media de la población aumenta. La eficacia media se maximiza cuando el alelo favorecido alcanza una frecuencia del 100%.

> [!SUCCESS] Selección sobre los alelos recesivos  en comparación con la selección sobre los alelos
> El alelo no favorecido por la selección se esconde en los individuos heterozigotos. Pero tras 100  generaciones se observa un ligero cambio de frecuencias, como el aumento de la frecuencia de homozigotos no favorecidos. Una vez se acelera el ritmo de la evolución, los alelos favorecidos por la selección acabará fijandose en la población.


![[Pasted image 20251027133512.png]]
### Selección dominante: selección que actúa sobre el fenotipo dominante
![[Pasted image 20260109142535.png]]

##  Selección sobre homozigoto y heterozigoto

Cuando un alelo es recesivo y el otro es dominante, la eficacia de los heterozigotos es igual a la de uno de los dos homozigotos. Desde luego hay otras situaciones posibles. **A menudo la eficacia de los heterozigotos se encuentra entre la de los dos homozigotos**. Esto puede cambiar la tasa de evolución, pero no altera el resultado final. Al final, en la población queda fijado un alelo y el otro se pierde. En la Figura 5.10 se muestran varios ejemplos.

También es posible que la eficacia de los heterozigotos sea superior o inferior a la de
los dos homozigotos. La superioridad y la inferioridad de los heterozigotos dan lugar a
resultados completamente distintos.

Nuestro primer ejemplo viene de la investigación en poblaciones de laboratorio de la
mosca de la fruta (Drosophila melanogaster) realizada por Terumi Mukai y Allan Burdick
(1959). Al igual que Dawson, Mukai y Burdick estudiaron la evolución de un locus con
dos alelos. Los homozigotos para un alelo eran viables mientras que los homozigotos para el otro alelo no lo eran. Los investigadores utilizaron heterozigotos como fundadores para establecer dos poblaciones experimentales con frecuencias alélicas iniciales de 0,5. Permitieron que las poblaciones evolucionaran durante 15 generaciones, midiendo en cada generación la frecuencia del alelo viable.
Los resultados de Mukai y Burdick aparecen en la Figura 5.16, representados por los
símbolos rojos. Como se esperaba, la frecuencia del alelo viable aumentó rápidamente en las primeras generaciones. Sin embargo, la tasa de evolución disminuyó mucho antes de que el alelo viable se aproximara a la frecuencia de 1,0. Por el contrario, parecía que el alelo viable alcanzaba un equilibrio, o un estado sin cambios, a una frecuencia de 0,79.

Para profundizar más, Mukai y Burdick fundaron dos nuevas poblaciones experimentales, esta vez con una frecuencia inicial del alelo viable de 0,975. La evolución de estas poblaciones se representa en la Figura 5.16 por los símbolos azules. En lugar de aumentar hacia 1,0, la frecuencia del alelo viable bajo, alcanzando de nuevo un equilibrio cercano al 0,79.

![[Pasted image 20260109133941.png]]
Adviértase que una frecuencia de equilibrio de 0,79 para el alelo viable significa que
el alelo letal tiene una frecuencia de equilibrio de 0,21. ¿Cómo puede mantener la selección natural un alelo letal a tan elevada frecuencia en esta población? Mukai y Burdick arguyeron que la explicación más probable era la superioridad del heterozigoto, también conocida como **superdominancia.** 



> [!NOTE] Superdominancia 
> Es un tipo de selección natural en el que el **genotipo heterocigoto tiene mayor eficacia biológica que ambos genotipos homocigotos**. Como consecuencia, se mantiene la variación genética en la población, ya que ninguno de los alelos se elimina. Un ejemplo clásico es el caso de la anemia falciforme, donde los heterocigotos tienen ventaja frente a la malaria.


De acuerdo con esta hipótesis, los heterozigotos tienen mayor eficacia que cualquiera de los homozigotos. En el equilibrio, la ventaja selectiva que posee el alelo letal cuando está en heterozigosis se equilibra exactamente con la desventaja obvia que sufre cuando está en homozigosis. Las curvas roja y azul de la Figura 5.16 representan la evolución en una población ideal en la que la eficacia de los tres genotipos son las siguientes (V representa el alelo viable y L el alelo letal):


| *VV*  | *VL* | *LL* |
| ----- | ---- | ---- |
| 0'735 | 1'0  | 0    |
Las curvas teóricas se ajustan mucho a los datos. Manteniendo una población en un
equilibrio en el que ambos alelos se encuentren presentes, la superioridad del heterozi-
goto puede mantener diversidad genética. Para un tratamiento algebraico de la superioridad del heterozigoto, véase el Cuadro 5.8.

Nuestro segundo ejemplo, del trabajo de G. G. Foster y sus colegas (1972), demuestra
cómo evolucionan las poblaciones cuando los heterozigotos tienen menor eficacia que
cualquiera de los dos homozigotos. Foster y sus colegas utilizaron moscas de la fruta con cromosomas compuestos. Los cromosomas compuestos son cromosomas homólogos que han permutado brazos completos, de tal manera que un homólogo tiene dos copias de un brazo y el otro homólogo tiene las dos copias del otro brazo (Figura 5.17a,b). En la meiosis, los cromosomas compuestos pueden segregar o no. Por ello se producen cuatro tipos de gametos en igual número: gametos con ambos cromosomas homólogos, gametos con sólo uno de los brazos del par, gametos con sólo el otro brazo del par y gametos sin cromosomas del par (Figura 5.17c). Cuando se cruzan dos moscas con cromosomas compuestos, la cuarta parte de sus zigotos tiene cada uno de los brazos cromosómicos en la dosis correcta y son viables. Los otros tres cuartos tienen o demasiadas copias o demasiado pocas de uno o de los dos brazos cromosómicos y son inviables (Figura 5.17d). Cuando una mosca con cromosomas compuestos se cruza con una mosca con cromosomas normales, ninguno de los zigotos que se forma es viable (Figura 5.17e).
Foster y sus colegas establecieron poblaciones de laboratorio en las que algunos de los fundadores tenían cromosomas segundos compuestos [C(2)] y otros tenían cromosomas segundos normales [N(2)]. Para el análisis podemos tratar cada cromosoma como si fuera un único alelo. Así, los fundadores son homozigotos C(2)C(2) y homozigotos N(2)N(2).
Basándonos en la viabilidad de los homozigotos que acabamos de describir, las eficacias de los genotipos en la población mezcla son:

| C(2)C(2) | C(2)N(2) | N(2)N(2) |
| -------- | -------- | -------- |
| 0'25     | 0        | 1        |
![[Pasted image 20260109134407.png]]
En otras palabras, los genotipos presenta una fuerte desventaja del heterozigoto(**infradominancia**).

> [!NOTE] Infradominancia
> Es un tipo de selección natural en el que el **genotipo heterocigoto tiene menor eficacia biológica que ambos genotipos homocigotos**. Esto genera una selección en contra del heterocigoto y puede provocar que uno u otro alelo se fije en la población, dependiendo de sus frecuencias iniciales.

El análisis *Equilibrio estable con superioridad del heterozigoto y equilibrio inestable con inferioridad del heterozigoto* que será descrito a continuación, predice que una población mezclada estará en equilibrio, con los 2 alelos presentes, cuando la frecuenica de *C(2)* sea exactamente 0'8. Sin embargo, este equilibrio **es inestable**. Si la frecuencia de *C2* sube ligeramente por encima de 0'8, entonces aumentará rápidamente hasta 1'0. De igual manera, si la frecuencia de *C(2)* baja ligeramente de 0'8 rápidamente bajará hasta cero.

Intuitivamente, la razón de esta predicción es la siguiente. **Los heterozigotos son inviables, por lo que los adultos de la población serán todos homozigotos.**

Imaginemos primero que los individuos *C(2)C(2)* son corrientes y los *N(2)N(2)* raros. Si las moscas se cruzan al azar, casi todos los cruces se darán entre moscas *C(2)C(2)*, o entre moscas *C(2)C(2)* y *N(2)N(2)*. Sólo raramente se cruzarán moscas *N(2)N(2)* entre si. Por ello, la mayoría de las moscas *N(2)N(2)* tendrán un éxito reproductivo nulo, y la frecuencia de *C(2)* subirá hasta 1,0. Imaginemos ahora que hay bastantes moscas *N(2)N(2)* y que un número apreciable de ellas se cruza entre sí. Estos cruces producirán cuatro veces más descendientes que los cruces entre moscas C(2)C(2). Por ello la frecuencia de N(2) subirá hasta 1,0 y la frecuencia de C(2) caerá hasta cero.

Foster y sus colegas fundaron 13 poblaciones mezcladas, con frecuencias de C(2) entre 0,71 y 0,96, y luego siguieron su evolución durante cuatro generaciones. Los resultados aparecen en la Figura 5.17f. Cuantitativamente, el resultado está perfectamente de acuerdo con las predicciones teóricas. En las poblaciones con las frecuencias iniciales de C(2) más elevadas, aumenta rápidamente hasta la fijación, mientras que en poblaciones con frecuencias iniciales bajas, C(2) se pierde rápidamente. La situación exacta del punto de equilibrio inestable es, aproximadamente 0,9 en lugar de 0,8. Foster y sus colegas advierten que
sus moscas C(2)C(2) llevaban marcadores genéticos recesivos que los biólogos introducen para permitir una fácil identificación. Sugieren que estos marcadores reducen la eficacia relativa de las moscas C(2)C(2) por debajo del valor de 0,25, deducido exclusivamente en función de sus cromosomas compuestos. El experimento de Foster y colegas demuestra que la inferioridad de los heterozigotos da lugar a la perdida de diversidad genética en las poblaciones. Sin embargo, llevando a la fijación a alelos diferentes en poblaciones distintas, la inferioridad del heterozigoto puede ayudar a mantener la diversidad genética en el conjunto de las poblaciones.

### Equilibrio estable con superioridad del heterozigoto y equilibrio inestable con inferioridad del heterozigoto
$$
\begin{align}
\vartriangle p=\frac{p}{\bar{w}}(pw_{11}+qw_{12}-\bar{w}) \\
=\frac{p}{\bar{w}}(pw_{11}+qw_{12}-p^{2}w_{11}-2pqw_{12}-q^{2}w_{22})
\end{align}
$$
Sustituyendo *p* por (1-*q*) en los términos primero y tercero de la expresión entre paréntesis, tendremos,

$$
\vartriangle p=\frac{p}{\bar{w}}[(1-q)w_{11}+qw_{12}-(1-q)^{2}w_{11}-2pqw_{12}-q^{2}w_{22}]
$$
Después de simplificar y despejar *q*, tendremos,

$$
\vartriangle p=\frac{pq}{\bar{w}}(w_{12}+w_{11}-qw_{11}-2pqw_{12}-qw_{22})
$$

Por definición, la frecuencia del alelo A1,  estará en equilibrio  cuando
$$
\vartriangle p=0
$$
Para tener esta condición es necesario  que *p o q*=0. **Estos dos equilibrios son triviales**. Se dan cuando desaparece un alelo de la población. La ecuación también tiene una tercera situación de equilibrio, que es cuando,
$$
w_{12}+w_{11}-qw_{11}-2pw_{12}-qw_{22}=0
$$
Tenemos que sustituir  *q*  por *(1-p)* y despejando *p* tendremos,
$$
\hat{p}=w_{22}-\frac{w_{12}}{w_{11}-2w_{qw}+w_{22}}
$$
donde p^ es la frecuencia del alelo A1 en el equilibrio. Finalmente, sea la eficacia de los genotipos la siguiente:

| *A1A1* | *A1A2* | *A2A2* |
| ------ | ------ | ------ |
| 1+s    | 1      | 1+t    |
Si *s o t* tienen valores positivos significa que están en contra del heterozigoto mientras que los negativos estarían a favor.  
Al final al fórmula se queda :
$$
\begin{align}
 \hat{p}=\frac{t}{s+t} \\
 \hat{q}=\frac{s}{s+t} 
\end{align}

$$

> [!SUCCESS] Equilibrio polimorfico
> Se puede alcanzar un equilibrio polimórfico en ambos casos;  cuando la selección favorece al heterocigoto (w12 > w11 y w12 > w22, por lo tanto, s y t < 0), lo que se denomina sobredominancia, heterosis o selección balanceadora. Y cuando la selección actúa en contra del heterocigoto (w12 < w11 y w12 < w22, por lo tanto, s y t > 0), lo que se denomina subdominancia o selección disruptiva.

> [!QUESTION] ¿Por qué con sobredominancia conseguimos un equilibrio mientras que con infradominancia no?
> En sobredominancia, el heterozigoto tiene ↑ eficacia que ambos homozigotos, por lo que hace que la selección favorezca a los individuos con alelos distintos y mantiene la variabilidad en la población. Esta situación genera un equilibrio estable, porque is la frecuencia de uno  de los alelos ↓, la producción de heterozigotos sigue siendo ventajosa y la selección lo vuelve a aumentar; por eso  el sistema tiende  a regresar  al equilibrio→Selección estabilizadora.
> Por otro lado, en el  caso de infradominancia, el heterozigoto tiene menor ↓ eficacia, por tanto, la selección actúa en su contra. En este caso, el equilibrio en el que ambos alelos estén presentes es inestable, porque cualquier desviación en la frecuencia de un alelo reduce más la producción de heterozigotos y empuja a la población a la fijación de uno u otro alelo. Conduciendo a un  equilibrio inestable y no mantiene la variación genética.


Por ejemplo, cuando **s = –0,4 y t = –0,6, los heterozigotos tienen una mayor eficacia**, y la frecuencia en el equilibrio para el alelo A1 es 0,6. **Cuando s = 0,4 y t = 0,6, los
heterozigotos tienen una menor eficacia y la frecuencia en el equilibrio para el alelo A1 es también 0,6.**
Otro método útil para analizar el equilibrio es representar el Δp en función de p. En la Figura 5.18a se muestra tal representación para los dos ejemplos numéricos que
acabamos de calcular. En ambas representaciones se demuestra que el Δp = 0 cuando p = 0, p = 1 ó p = 0,6.

Las curvas de la Figura 5.18a también nos permiten determinar si un equilibrio es estable o inestable. Observemos la curva roja; se refiere a un locus con superioridad
del heterozigoto. Advierta que cuando **p es mayor de 0,6, el Δp es negativo**. Esto quiere decir que cuando la frecuencia del alelo A1 sea superior a su valor de equilibrio,
la población retrocederá hacia el equilibrio en la generación siguiente. De igual manera, cuando **p* sea menor que 0,6, el Δp será positivo**. Cuando la frecuencia del **alelo A1 se encuentra por debajo de su valor de equilibrio volverá hacia el equilibrio en la generación siguiente**. El equilibrio “interno” de un locus con superioridad del heterozigoto es estable.

La Figura 5.18b muestra un paisaje adaptativo para un locus con **superioridad del heterozigoto**. El gráfico representa la eficacia media poblacional en función de la frecuencia del alelo A1. La eficacia media es baja cuando no está A1 y relativamente baja cuando A1 se ha fijado. A medida que la frecuencia del alelo se desplaza desde ambos extremos hacia su equilibrio estable, la eficacia media poblacional aumenta hasta un máximo.
![[Pasted image 20260109141448.png]]

Miremos ahora a la curva azul de la Figura 5.18a. Se refiere a un locus con **inferioridad del heterozigoto. Si *p* aumenta, aunque sólo sea ligeramente, por enzima de 0,6**, seguirá aumentado hasta 1,0 en las generaciones siguientes; si *p* disminuye, aunque sólo sea ligeramente por debajo de 0,6, continuará disminuyendo hasta 0 en las generaciones siguientes. El equilibrio interno para un locus con inferioridad del heterozigoto es inestable.

![[Pasted image 20260109141442.png]]


> [!QUESTION] ¿Cómo diferenciar entre sobredominancia e infradominancia
>Sobredominancia → si el heterozigoto con ↑ eficacia+ s<0 + t<0
>Infradominancia→si el heterozigoto con ↓ eficacia +s >0 + t>0

![[Pasted image 20260109143801.png]]
> [!NOTE] Paisaje adaptativo
> Es una representación conceptual que muestra la relación entre los **genotipos o fenotipos** de una población y su **eficacia biológica**. Se imagina como una superficie con **picos y valles**, donde los picos representan combinaciones genéticas con alta eficacia biológica y los valles combinaciones con baja eficacia. La selección natural tiende a mover a las poblaciones hacia los picos adaptativos, mientras que la deriva genética, la mutación y la recombinación pueden permitir que una población cruce valles y alcance picos diferentes.

La Figura 5.18c muestra el paisaje adaptativo para un locus con **inferioridad del heterozigoto**. La eficacia media poblacional es mínima cuando la frecuencia del alelo A1 coincide con el equilibrio interno inestable. Cuando la frecuencia del alelo se aleja de este equilibrio en ambas direcciones, la eficacia media aumenta.
Una comparación del paisaje adaptativo de la Figura 5.18c con los de las Figuras 5.18b y 5.15 ofrece una conclusión importante. Cuando una población evoluciona
en respuesta a la selección, la eficacia media de los individuos de la población tiende a elevarse. Sin embargo, la selección no siempre maximiza la eficacia media en un
sentido global. Dependiendo de las frecuencias alélicas iniciales, la población representada en la Figura 5.18c puede evolucionar bien hacia la fijación, bien hacia la
pérdida del alelo A1. Si el alelo queda fijado, la población se situará en un equilibrio estable, pero la eficacia media de la población será sustancialmente menor que si el alelo se hubiera perdido.

![[Pasted image 20260109141429.png]]


> [!SUCCESS] Selección natural: Modelo de solo un locus
> Es posible derivar una expresión matemática sencilla para describir la acción de la selección natural en un locus con dos alelos.
Estas expresiones también pueden aplicarse a organismos haploides.
La acción de la selección depende de la ventaja selectiva, la frecuencia inicial del alelo seleccionado y el modo de herencia (recesivo/dominante/codominante).
Cuando la selección favorece al heterocigoto, este puede mantener un polimorfismo estable y puede asociarse a la selección estabilizadora.
La selección contra el heterocigoto conduce a un polimorfismo inestable y puede asociarse a la selección disruptiva.
Existen evidencias experimentales y observacionales que demuestran la validez de los modelos de selección estudiados (experimentos con insectos y datos de poblaciones humanas).
