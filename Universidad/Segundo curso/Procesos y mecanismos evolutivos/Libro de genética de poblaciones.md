# Tema 3. Los genes en las poblaciones
# Tema  4. La deriva genética en poblaciones finitas
# Tema 5. Selección: bases generales
## Conceptos claves

| Concepto                     | Definición                                                                                                                                                                                                                 |
| ---------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Selección                    | Mecanismo poblacional que produce cambios en las frecuencias alélicas debido a la reproducción diferencial adaptativa de los genotipos                                                                                     |
| Viabilidad                   | medida relativa del número de individuos supervivientes de una clase fenotípica o genotípica determinada                                                                                                                   |
| Fertilidad                   | Hace referencia a la descendencia viable de un individuo o población. También se utiliza como el número de descendientes viables de una hembra durante su período reproductivo                                             |
| Aptitud                      | Dícese de la capacidad reproductiva de un genotipo relativa a los demás genotípicos de la población. Depende de muchos factores del ciclo vital tales como la viabilidad, la fertilidad, la capacidad de apareamiento, ect |
| Aptitud marginal de un alelo | Es la aptitud media de todos los genotipos que contienen ese alelo                                                                                                                                                         |
| Coeficiente de selección     | Exceso(defecto) relativo de aptitud de un genotipo respecto al genotipo de menos (más actitud) aptitud cuando la aptitud de éste se iguala a 1. Se aplica a los términos s, t                                              |
| Equilibrio poblacional       | Estado en el que se encuentra la población donde las frecuencias alélicas de un locus determinado no cambian en sucesivas generaciones                                                                                     |
| Polimorfismo protegido       | Polimorfismo que se mantienen debido a que existe un equilibrio interno localmente estable en la población                                                                                                                 |
| Superdominancia              | Polimorfismo que se mantiene protegido debido a la superior aptitud del heterocigoto respecto a los homocigotos                                                                                                            |
| Lastre genético              | Diferencia relativa entre la aptitud media de una población dada y la de una población formada exclusivamente por el geontipo más apto.                                                                                    |
## 5.1 Introducción
Aunque conceptualmente sencilla, la selección natural-el éxito reproductivo diferencial de los organismos es un agente evolutivo con múltiples modos de actuación y consecuencias sobre la dinámica de las poblaciones. La selección natural puede entenderse en el contexto de la teoría de la genética de poblaciones y, de forma más amplia, en el de la evolución. Bajo el primero, la selección es uno de los parámetros que alteran el equilibrio Hardy-Weingerg. Desde el segundo la selección natural es un agente fundamental de la evolución adaptativa. Cuatro puntualizaciones nos pueden servir de ayuda para poder apreciar la profunda significación que tiene la selección como agente de evolución:
1. Selección natutal no es lo mismo que la evolución
	1. La evolución es un proceso en dos pasos:
		1. El primero está relacionado con el origen de la variación genética
		2. El segundo está relacionado con el cambio en el patrón de la variación fundamentalmente con el reemplazamiento de unos genotipos por otros.
	2. La selección natural puede ser una de las causas del cambio del patrón de variación (recordemos que la deriva genética, factores históricos, ect son otras posibles causas), pero no del origen de la variación. De ahí que no exista una correspondencia biunívoca formal entre evolución y selección natural.
2. No todo tipo de selección natural provoca evolución, ni todo tipo de evolución es producto de la selección natural.
		1. Solo hemos de imaginar una situación en la que dándose diferencias en viabilidad o fertilidad de los genotipos no se produzcan cambios en el patrón o distribución de los mismos en generaciones consecutivas para advertir entonces que, aún actuando la selección natural, no hay evolución. Del mismo modo se puede presentar la situación de observar cambios en la distribución de los genotipos con las generaciones sin existir diferencias entre ellos en sus viabilidades o fertilidades. Al respecto cabe recordar que ya se vio en el capítulo 4 y se verá en el 7 cómo la deriva genética puede promover evolución.
3. Es importante tener presente que la selección natural sólo tiene relevancia para evolución si las diferencias en éxito reproductivo que tienen los fenotipos de una población se traducen en diferencias genotípicas. De lo contrario tales diferencias son irrelevantes.
4. La selección natural es la variación en el éxito reproductivo medio de los diferentes fenotipos de una población,
	1. Dicho de otro modo: un carácter puede evolucionar por selección natural si supone, de alguna forma, un incremento en el éxito reproductivo del organismos portador.
Una teoría de la evolución debería estar integrada por 3 subteorías, una relacionada con los procesos ecológicos (que contemple para los ambientes posibles la correspondiente dinámica de los fenotipos en función de su aptitudes biológicas), otra relacionada con los procesos de desarrollo (que determinan el efecto del genotipo sobre el fenotipo), y una tercera sobre la genética de poblaciones (que da cuenta de los cambios en la composición genética de una población cuando son conocidas la aptitudes de los genotipos). Como señala Lewontin, la genética de poblaciones constitute una explicación necesario, pero probablemente no suficiente, de la evolución, porque las leyes que controlan los procesos los cambios en la composición genética de las poblaciones. De ser la teoría de la genética de poblaciones necesaria y suficiente estaríamos frente a una teoría explicativa completa de la evolución.
Mas que desarrollar con detalla todos aquellos casos formales donde se pueden presentar la selección, lo que se pretende es introducir un estilo de razonamiento. Para ello se formulará un modelo general de cómo opera la selección, empezando por organismos con reproducción asexual, que servirá para derivar la expresión del cambio de las frecuencias de los alelos con el tiempo, así como para estudiar bajo qué situaciones se puede dar un mantenimiento estable del polimorfismo.
## 5.2 Selección en organismos asexuales
Considérese una población de organismos asexuales haploides en la que un locus determinado presenta dos tipos de alelos A y a. El número de individuos de cada tipo en la generación t es NA(t) y Na(t). Interesa determinar el número de individuos en generaciones futuras. Para ello se necesita conocer el número de descendientes de cada genotipo. Si los individuos con el alelo A tienen una probabilidad vA de viabilidad o supervivencia hasta adulto y una descendencia media o fertilidad de fA, el número esperado de descendientes de un individuo de tipo será vAfA*. A esta cantidad compuesta de viabilidad y fertilidad fA se le denomina aptitud absoluta o aptitud darwinista del genotipo A o wA(fitness). Por analogía, la aptitud de los individuos portadores del alelo a vendrá dada por wA. A lo largo del capítulo y otros donde se hable de selección y no se haga mención en contra, se supone que los números de individuos NA(t) Na(t) son suficientemente grandes como para ignorar las fluctuaciones que podrían aparecer como consecuencias de la aleatoriedad de los nacimientos o las muertes. En otras palabras, la aproximación matemática a utilizar será determinista, en la cual NA(t) individuos del genotipo A tendrán NA(t) WA descendientes. En la siguiente generación, el número de individuos de genotipos A y a vendrá dado, respectivamente, por
#T51
$$
N_{A}(t+1)=N_{A}(t)w_{A}
$$
$$
N_{a}(t+1)= N_{a}(t+1)*w_{a}
$$
Por ello, las frecuencias de los genotipos A y a en la generación t serán respectivamente:
#T52
$$
p_{i}=\frac{N_{A}(t)}{N_{A}(t)+N_{a}(t)}
$$
$$
qi= \frac{N_{a}(t)}{N_{A}(t)+N_{a}(t)}
$$
Análogamente, la frecuencia de los individuos de genotipo A en la generación t+1 teniendo en cuenta las igualdades que aparecen en #T51 vendrá dada por:
#T53
$$
p_{t+1}=\frac{N_{A}(t+1)}{N_{A}(t+1)+N_{a}(t+1)}= \frac {N_{A}(t)*w_{A}}{N_{A}(t)w_{A}+N_{a}(t)w_{a}}
$$
Diviendiendo por N(t)= NA(t)+ Na(t) cada uno de los N de la fracción de la derecha de #T53 sustituyendo #T52 se tiene que:
#T55
$$
p_{t+1}= \frac{p_{i}w_{A}}{p_{i}w_{A}+q_{j}w_{a}}
$$
El denominador de las dos fracciones que aparecen en la #T54 y #T55 es una media aritmética ponderada, a la que se le denomina aptitud media relativa w, y que puede ser reformulada como sigue:
#T56
$$
 \bar{w}=\frac{N_{A}(t)w_{A}+N_{a}(t)w_{a}}{N_{A}(t)+N_{a}(t)}=\frac{N_{t+1}}{N_{t}}
$$
Por lo tanto, la aptitud media nos mide el factor de incremento absoluto del número de individuos de la generación t+1, respecto de la generación t. Las igualidades #T54 y #T55 se puede reescribir de la forma siguiente:
#T57
$$
p_{t+1}=\frac{p_{i}w_{A}}{\bar{w}}
$$
$$
q_{t+1}=\frac{q_{j}w_{a}}{\bar{w}}
$$
### 5.2.1 Aptitud y densidad poblacional
Si se considera la razón entre las dos ecuaciones dadas en #T57 se apreciará que la composición genética de la población en la generación t+1 depende de la razón de aptitudes y no de sus valores absolutos. En efecto, tal razón puede expresarse del siguiente modo
#T58
$$
\begin{align}
p_{t+1}=w_{A}p_{i} \\
q_{t+1}=w_{a+q_{i}}
\end{align}
$$
El recuardo #t51 muestra un ejemplo que ayudará a entender mejor la expresión #T58. No es trivial la relevancia biológica de las aptitudes relativas, debido a que una fuente extra de mortalidad o fertilidad puede cambiar las aptitudes absolutos, pero puede dejar intactas las aptitudes relativas si afecta de igual forma a todos los genotipos. Habrá, pues, un efecto sobre el tamaño de la población, aunque no sobre su composición genética. Esta circunstancia es importante cuando la población tiene regulación por su tamaño(recuardo #t52)
### 5.2.2 Coeficiente de selección
Si w_A>w_a las aptitudes relativas se pueden representar, en lugar de w_A : w_a como (1+s):1, donde s es el coeficiente de selección que favorece. Obviamente, cuando no hay selección s=0. Con la nueva nomenclatura al aptitud media, w, se puede reformular como:
#T59
$$
\bar{w}=(1+s)p_{i}+q_{j}
$$
y sí se tiene en cuenta que q=1-p, entonces
#T510
$$
\begin{align}
\bar{w}=(1+s)p_{i}+(1-p_{i}) \\
\bar{w}=p_{1}+sp_{i}+1-p_{i} \\
\bar{w}=1+sp_{i}
\end{align}
$$
por lo que la primera de las dos ecuacións de #T57 se transforma en:
#T511
$$
p_{t+1}=\frac{p_{i}(1+s)}{1+sp_{i}}
$$
### 5.2.3 Cambio en las frecuencias alélicas y genotípicas
El cambio de la frecuencia alélica en dos generaciones consecutivas y, por tanto, de la genotípica al tratarse de organismo halpoides, viene dado por:
#T512
$$
\begin{align}
\vartriangle p=p_{t+1}-p_{i}=\frac{p_{i}w_{A}}{p_{i}w_{A}+(1-p_{i})w_{a}}-\frac {p_{i}}{p_{i}+(1-p)} \\
\vartriangle p\frac{(p_{i}w_{A}*p_{i}+(1-p_{i}))-(p_{i}*p_{i}w_{A}+(1-p)w_{a})}{p_{i}w_{a}+(1-p_{i})w_{a}*p_{i}+(1-p_{i})} \\
\vartriangle p= \frac {p_{i}w_{A}*p_{i}-p_{i}^{2}-(p_{i}*p_{i}w_{a}+w_{a}-p_{i}w_{a})}{(p_{i}w_{A}+(1-p_{i}w_{a})(p_{i}+(1-p_{i}))} \\
\vartriangle p=\frac{}{}
\end{align}
$$
Eliminando los subíndices en las igualdades anteriores, pues se hace referencia a la frecuencia alélica de la generación de partida, y teniendo en cuenta el valor de la aptitud media w=pwA+(1-p)wa se puede reformular el cambio de la frecuencia alélica como:
#T513 
$$
\vartriangle p=\frac{p(w_{A}-pw_{A})}{\bar{w}}=\frac{p(1-p)w_{A}-w_{a}}{\bar{w}}
$$
Si se sustituye w_A por 1+s, w_a por 1, y se mantienen la aptitud media tal como quedó definidida en #T510 entonces el cambio de la frecuencia del alelo A queda, también como:
#T514
$$
\vartriangle p=\frac{p(1-p)((1+s)-1)}{1+sp}=\frac{sp(1-p)}{1+sp}
$$
Hasta aquí se ha tratado el caso de organismos con reproducción asexual. Los resultados no son diferentes si se consideran haploides sexuales. Así, si la selección precede a la meiosis cambiarán las proporciones de los genotipos(y de los genes), desde p, y q, p(t+1) y q(t+1) en la misma forma que los asexuales, tal y como se desprende de las ecuaciones #T54 y #T55.La fertilización subsecuente, seguida por la meoisis y si no existen violaciones de las leyes mendelianas. En tal caso un haploide sexual se comporta como un asexual. Sólo cuando se considera más de un locus se puede demostrar que asexuales y haploides se comportan de forma diferente.
## 5.3 Selección en organismos diploides
Los modelos asexuales son simples debido a que la descendencia tienen siempre el mismo genotipo(ignorando la mutación,claro). En una población diploide las cosas son diferentes. Un progenitor de tipo AA puede tener descendientes AA o Aa, e incluso, en los modelos más sencillos, los números relativos estos dos tipos de descendientes dependen de la composición del resto de población. No obstante, la complejidad introducidas por la diploidía son manejables.
Considérese una población en equilibrio Hardey-Weinberg en la generación t con un número N de cigotos donde, por tanto, Np² son los individuos de genotipo AA, 2NP, q son los de  genotipo Aa y Np² son los genotipo aa. Si la viabilidad de los individuos de genotipo tipo AA es v_AA y su fertilidad f_AA, entonces la contribución de los individuos AA al conjunto de gametos que constituyen la siguiente generación t+1 será Np²*v_AA*f_AA. Se supone que N es suficientemente grande como para descartar efectos aleatorios sobre las frecuencias alélicas y poder desarrollar el modelo desde un punto de vista determinista. Teniendo en cuenta la distribución al conjunto de gametos de los genotipos AA y suponiendo, además, apareamiento al azar, el número de cigotos descendientes de dos progenitores AA será proporcional a (Np²v_AA*f_AA*)².
A esta expresión se puede llegar de otra forma. En este efecto, ya que hay Np²v_AA adultos de genotipo AA, y éstos aparean al azar, el número de apareamientos AAxAA será proporcionales a ((Np_i)²v_AA)((Npi)²v_AA. Además, cada uno de tales apareamientos tendrá una descendencia proporcional a f_AAxf_AA, el número de gametos procedentes de progenitores AA, Aa y aa vendrá dado por (Np_i)²w_Aa y (Nq_i)²w_aa respectivamente. Los gametos A serán todos aquellos procedentes de los progenitores AA más la mitad de los progenitores AA más la mitad de los progenitores Aa. Por lo tanto, la frecuencia de A entre los gametos que forman la generación t+1 vendrá dada por:
#T515 Aptitudes absolutas
$$
P_{t+1}=\frac{Np_{i}^{2}w_{AA}+Np_{i}q_{j}w_{Aa}}{Np_{i}^{2}w_{AA}+2Np_{i}q_{j}w_{aa}}
$$
La expresión #T515, que relaciona aptitudes absolutas, se puede transformar en relación de aptitudes relativas tan sólo dividiendo numerador y denominador N. En ese caso #T515 se transforma en:
#T516
$$
p_{t+1}=\frac{p_{i}^{2}w_{AA}+p_{i}q_{i}w_{Aa}}{p_{i}^{2}w_{Aa}+2p_{i}q_{i}w_{Aa}+q_{i}^{2}w_{aa}}
$$
El denominador constituye la aptitud media relativa de un individuo tomado al azar o la aptitud media de la población, a la que denominamos w. Una observación interesante es que, ya que los gametos así formados se unen al azar, los cigotos que formen con las nuevas frecuencias estarán en equilibrio de Hardey-Weinberg y se habrá dado, posiblemente, un cambio en la frecuencia de los genes de una generación a la siguiente.
Existe una serie de formas alternativas a la ecuación #T516 y que pueden tener interés para el estudio de los efectos poblacionales de la selección. La primera es una ecuación similar a la #T58 con organismos con reproducción asexual
#T517
$$
\begin{align}
p_{t+1}=p_{i}(p_{i}w_{AA}+q_{j}w_{Aa}) \\
q_{t+1}=q_{j}(p_{j}w_{Aa}+q_{j}w_{aa})
\end{align}
$$
Esta expresión se puede derivar de #T516 . Otra forma de calcular p_t+1 viene dada por:
#T518
$$
p_{t+1}=\frac{p_{i}(p_{i}w-AA)+q_{j}w_{Aa}}{\bar{w}}=\frac{p_{i}\bar{w}_{A}}{\bar{w}}
$$
donde w es la aptitud media relativa (aptitud marginal) de aquellos  individuos que son portadores del alelo A.
La tercera forma expresa el cambio en la frecuencia alélica variación de p como una función de p. Restando p_i en ambos lados de la expresión #T516, y eliminando el subíndice de generación se obtiene:
#T519
$$
\begin{align}
\vartriangle p=p_{t+1}-p_{i}=\frac{p^{2}w_{AA}+pqw_{Aa}-p(p^{2}w_{AA}+2pqw_{Aa}+q^{2}w_{aa})}{p^{2}w_{AA}+2pqw_{Aa}+q^{2}w_{aa}} \\
=\frac{p(1-p)[p(w_{AA}-w_{Aa})+(1-p)x(w_{Aa}-w_{aa})]}{\bar{w}} \\
=\frac{pq(\bar{w}_{A}-\bar{w}_{a})}{\bar{w}}
\end{align}
$$
Conviene observar la equivalencia formal del incremento en la frecuencia de un alelo entre haploides #T513 y diploides #T519. En haploides se tiene la diferencia entre las aptitudes de los dos genotipos, mientras que en diploides, por el hecho de que un alelo está presente en homocigosis y  heterocigosis, es la diferencia entre las aptitudes marginales de los mismos. La expresión #T519, de forma alternativa, se puede formular también como:
#T5120 
$$
\begin{align}
\vartriangle p=p_{t+1}-p_{t}=\frac{p^{2}w_{AA}+pqw_{Aa}-p\bar{w}}{\bar{w}} \\
= \frac{p(pq_{AA}+pq_{Aa}-p\bar{w})}{\bar{w}}\\=
\frac{p(\bar{w}_{A}-\bar{w})}{\bar{w}}
\end{align}
$$
En efecto, el incremento de un alelo en dos generaciones consecutivas es proporcional a la frecuencia del alelo en la población y al de la diferencia entre la aptitud marginal del mismo y la aptitud media. Un valor positivo de esa diferencia, es decir una mayor aptitud marginal que la aptitud media, implica incremento de la frecuencia del alelo en la población.
## 5.4 Algunos modelos selectivos de aptitud de especial importancia
En el presente apartado vamos a estudiar, con cierto nivel de detalle, algunos modelos que son importantes por un doble motivo. En primer lugar porque se trata de modelos elementales que nos pueden permitir entender la formilización de la acción de la selección natural sobre las frecuencias alélicas y servir de base para poder acceder a otros modelos más complejos. Y en, segundo lugar, porque existen ejemplos, de poblaciones naturales y experimentales, bien documentados donde se aplican tales modelos. Como nota aclaratoria indicar que, si bien en los apartados 5.2 y 5.3, para evitar la proliferación de subindices hemos hecho referencia a modelos de selección en un focus con dos alelos A y a, ahora tales alelos serán denominados A1 y A2. También pretendemos con ello indicar lo que, por otro lado, es natural en buena parte de los loci: sus múltiples estados alélicos y el uso de la notación A1,A2,A3....Ai
### 5.4.1 Alelos recesivos
Supóngase que por lo que hace a la aptitud biológica el alelo A1 es recesivo respecto del A2. Es conveniente recordar que el locus en cuestión puede mostrar, respecto de otro carácter en el que está implicado, unas relaciones de dominancia diferentes a las que muestra respecto del carácter aptitud biológica. Con respecto a está el heterocigoto A1A1 y el homocigoto A2A2 tienen el mismo comportamiento fenotípico, confiriendo la misma aptitud de los genotipos portadores. Sean 1+s,+1 y 1 las aptitudes de los genotipos A1A1, A1A2 y A2A2, respectivamente. En tal caso las aptitudes de los alelos A1 y A2 son, respectivamente:
#T521 
$$
\begin{align}
\bar{w_{A_{1}}}=pw_{A_{1}A_{1}}+qw_{A_{2}A_{2}}+q=p(1+s)+(1-p)=1+sp \\
\bar{wA_{1}}=pw_{A_{1}A_{1}}+qw_{A_{2}A_{2}}=p+q=1
\end{align}
$$
y la aptitud media de la población es
#T522
$$
\begin{align}
\bar{w}=p^{2}w_{A_{1}A_{1}}+2pqw_{A_{1}A_{2}}+q^{2}w_{A_{2}A_{2}}=p^{2}(1+s)+2pq+q^{2} \\
p^{2}(1+s)+2p(1-p)+1(1-p)^{2}=p^{3}+p^{2}s+2p^{2}+2p+1-2p+p^{2}=1-sp^{2}
\end{align}
$$
Por otro lado, las expresiones para el cambio de la frecuencia alélicas y el incremento entre dos generaciones consecutivas vienen dadas según #T518 y #T520, respectivamente,
#T523
$$
p_{t+1}=\frac{p_{i}(1+sp_{t})}{1+sp_{i}^{2}}
$$
#T524
$$
\vartriangle p=\frac{sp^{2}(1-p)}{1+sp^{2}}
$$
Las figuras 5.2, 5.3, 5.4 muestran el cambio del alelo A con el tiempo el de variación p y el de w en funcón de p, respectivamente, para el coeficiente de selección determinado. Hay que hacer notas que en 5.23 no aparece la variable tiempo propiamente, sino que se trata de una ecuación de recurrencia, de forma que la frecuencia en una generación se calcula a partir del valor de la frecuencia de la generación anterior y el coeficiente de selección. Lo que aparece en la figura 5.2 es la representación de los valores de p para un número determinado de generaciones. Podrá observarse que p sube rápidamente al principio y tiende luego asintóticamente hacia 1. En la figura 5.3 se observa cómo variación p no es una función lineal de p, presentando un máximo a frecuencia intermedias. Por último (figura 5.4), y como era de esperar, la aptitud media se incrementa con el aumento de p, aunque no lo hace de una forma lineal.
### 5.4.2 Alelos dominantes
### 5.4.3 Aptitudes multiplicativas y aditiva
### 5.4.4 Ventaja y desventaja del heterocigoto: análisis de la estabilidad
Los casos que hemos visto hasta el momento resultan, normalmente, en la eliminación de un alelo por otro. Otros casos interesante son aquellos en los que el heterocigoto tiene mayor o menor ventaja que los homocigotos. Son interesantes porque no sólo permiten, como es el caso de la mayor ventaja del heterocigoto, alcanzar una situación de estabilidad poblacional, sino también, como ocurre cuando los heterocigotos son menos ventajosos que los homocigotos, porque el resultado de la seleción dependerá de las condiciones iniciales de la población. Una parametrización adecuada para esta situación puede ser la de asignar valores de aptitud 1-s, 1, y 1-t a los genotipos A1A1, A1A2 y A2A2, respectivamente. Así, para el caso de ventaja del heterocigoto los valores de s y t son positivos y negativos cuando el heterocigoto es desventajoso. Los valores que toman las aptitudes medias de los alelos y de la población vienen dados por la siguiente expresiones:
#T540 
$$
\begin{align}
\bar{w}_{A_{1}}=1-sp \\
\bar{w}_{A_{2}}=1-t(1-p) \\
\bar{w}=1-sp^{2}-t(1-p)^{2}
\end{align}
$$
y los valores de cambio en la frecuencia del alelo A1 vienen dados por
#T541
$$
\begin{align}
p_{t+1}=\frac{p_{t}(1-sp_{t})}{1-sp_{t}^{2}-t(1-p_{t})^{2}} \\
\vartriangle p= \frac{p(1-p)[t-(s+t)p]}{1-sp^{2}-t(1-p)^{2}}
\end{align}
$$
Una cuestión inmediata que se puede formular concierne a las situaciones en que variación p tome el valor 0, es decir que no exista cambio en la frecuencia del alelo y, por consiguiente, nos encontramos en un equilibrio alélico. Estas son las siguientes:
1. Que el denominador sea infiniro, lo que es posible porque s y t no lo son.
2. Que p →1-p sean 0. Es una opción trivial, porque implica que no existe uno de los dos alelos, y por lo tanto la selección no puede actuar para reintroducir lo que ya se ha perdido.
3. Que t-(s+t)p sea 0. Esta situación es más interesante y ampara la posibilidad biológica de un equilibrio estable. En efecto, haciendo cero la expresión se obtienen el punto de equilibrio p:
#T542
$$
p=\frac{t}{s+t}
$$
Interesan tanto las situaciones para las que ambos coeficientes de selección son positivos como negativos. La expresión variación p en 5.41 tendrá el signo de t-(s+t)p, ya que p(1-p) es positivo así como el denominador. Pero el signo de t-(s+t) es el mismo que el signo de t/(s+t)-p=pt-p. Por lo tanto si p< pt, entonces variación de será positivo, y cuando p> pt, entonces variación p será negativo. Esto implica que las frecuencias alélicas siempre cambian hacia el punto de equilibrio. En ese caso, el punto de equilibrio es estable. Esta presentación del equilibrio es correcta para pequeñas desviaciones del mismo.
No podemos determinar si frente a una gran perturbación que desplaza la frecuencia muy lejos del punto de equilibrio, éste volverá a alcanzarse. Tal equilibrio en el que independencia de la magnitud de la perturbación se vuelve a él se denomina equilibrio globalmente estable. Es muy difícil investigar si la naturaleza de un equilibrio es globlamente estable, puesto que aun no siendo globalmente estable (cuando provocamos, por ejemplo, una perturbación del 30%), sí puede serlo localmente, respondiendo favorablemente a una perturbación pequeña.
La naturaleza de la estabilidad local se puede estudiar considerando el carácter continuo de las funciones en p. En efecto, si variación de p es una línea recta de pendiente ax en la vecindad de pt en un momento dado la distancia entre p y qt es un valor x(es decir x=p-pt). Así una generación después, el valor que tomará la nueva distancia 
Es decir, el valor que toma la nueva distancia depende del valor que tuviera x en la generación anterior y de a la pendiente en el punto de equilibrio. De hecho, si repetimos el proceso compraberemos que la distancia al punto de equilibrio al cabo de t generaciones es(1+a)^t .

El análisis formal del cambio de la frecuencia alélica bajo desventaja del heterocigoto es esencialmente similar al de ventaja del heterocigoto, pero las consecuencias biológicas son bien distintas y de relevancia. Del mismo modo se puede ver que existen un punto de equilibrio en p=t/s+t. El signo de variación p es el mismo que el de t-(t+s)p, que es a su vez el mismo que el de p-pt, puesto que ahora s y t son negativos. Por lo tanto, para valores de p mayores que p_e, variación p es positivo, y negativo para valores de p menores que pe. Tenemos un caso claro de equilibrio inestable. Por el contrario, los puntos extremos p=0 y p=1 constituyen casos de equilibrio estable(se puede seguir el razonamineto dado para los valores de las pendientes en os citados puntos y de la variable x de distancia entre los citados puntos y los valores próximos de perturbación).
### 5.4.5 Polimorfismos protegidos
Una forma alternativa de análisis de la estabilidad bajo ventaja o desventaja del heterocigoto resulta del estudio de la dinámica del alelo raro. Bajo ventaja del heterocigoto se puede suponer que el alelo raro se encuentra, normalmente en heterocigosis. Supongamos por ejemplo, que A1 es raro. Ello implica que los genotipos A1A1, son inexistentes, los A1A2 son poco frecuentes pero más aptos A2A2, lo más abundantes. Es obvio que se incrementará la frecuencia de heterocigotos y, por lo tanto, la del alelos A1. En ese caso nos alejaremos de p=0 y, por lo tanto, p=0 es un equilibrio inestable. El razonamiento para cuando A1 es frecuente es análogo pues, en ese caso, no existen genotipos A2A2, y los genotipos A1A2 son los más aptos que los A1A1. Luego dinámica será disminuir la frecuencia de los alelos A1 en favor de una mayor presencia de alelos A2.Es decir, el punto p=1 es inestable.Como variación de p es una función contínua de p, es evidente que si es positiva para valores de próximos a 0 y negativa para valores de p próximos a 1, en alguna frecuencia de p entre 0 y 1 variación debe valer 0.En otras palabras, debe existir algún punto de equilibrio interno que es estable o en el que el polimorfismo está protegido.Dejemos como ejercicio el estudio de la dinámica del alelo raro para cuando hay desventaja del heterocigoto, pudiendo razonarse cualitativamente que, en este caso, el polimorfismo no estaría protegido.
### 5.4.6 Genes liagos al sexo o en organismos haploidiploides
El efecto de la selección natural sobre el cambio de las frecuencias alélicas en genes ligados al sexo en especies diploides, donde el macho normalmente es el sexo heterogamético, y el de genes de especies haplo-diploides, donde el macho, generalmente, es el sexo haploide pueden ser modelizados de la misma forma. El modelo general aparece en el cuadro 5.3, donde aparecen las aptitudes para cada genotipo según sexo, así como las frecuencias genotípicas por genotipo y sexo antes y después de la selección.

|                         | Hembras          |                 |          | Machos |      |
| ----------------------- | ---------------- | --------------- | -------- | ------ | ---- |
|                         | A1A1             | A1A2            | A2A2     | A1     | A2   |
| Aptitud                 | w11              | w12             | w22      | w1     | w2   |
| Antes de la selección   | p_f x p_m        | p_f q_m+p_m q_f | q_m xq_f |        |      |
| Después de la selección | (p_f p_m w11)AWf |                 |          |        | (qf) |
Cada genotipo tiene una nueva frecuencia después de la selección, tras recalcular las frecuencias multiplicando por los coeficientes de selección y dividiendo por la aptitud media de cada sexo. Por lo tanto, la frecuencia del alelo A2 después de actuar la selección sobre los genotipos hembras y machos vendrá dada respectivamente por:
#T546 y #T547
$$
\begin{align}
q_{f}^{'}=\frac{{(1/2)(p_{f}q_{m}+p_{m}q_{f})w_{12}+w_{f}q_{m}w_{22}}}{\bar{w}_{f}} \\
q_{m}^{'}=\frac{q_{f}w_{2}}{\bar{w}_{m}}
\end{align}
$$
donde las aptitudes  medias por sexo son:
#T548 y #T549
Para ver el alcance de este modelo de selección podemos estudiar un caso, por ejemplo el de selección contra el homocigoto recesivo de la hembre A2A2, con valor w22-1-sf y contra los machos haploides A2 con valor w2-1-sm. En ese caso las expresiones y se transforman en
#T550 y #T551
Como puede observarse, para el caso extremo de que los genotipo en cuestión sean letales (sf=sm=1) se obtiene que q'm=0 y q'f=1/2pf. Es decir, las frecuencias alélicas difieren según sexo, incluso partiendo de valores iniciales similares. El cambio en las frecuencias según sexo viene dado por
#T552 y #T553

Puede demostrarse que si los valores de los coeficientes de selección son positivos, los incremnentos de la frecuencia del alelo A2 son negativo, de forma tal que, aunque con trayectorias distintas, las frecuencias del alelo van disminuyendo en ambos sexos. Queda por discutir, no obstanten, si existe posibilidad de un mantenimiento estable de los alelos ligados al sexo. Hedrick da las desigualdades generales necesarias para esta situación:
#T554
Utilizando la nomeclatura de Haldane y Jayakar, en la que la aptitud del alelo A1 en los machos es 1+s la del alelo A2 1-sm y, por otra parte, las aptitudes de las hembras homocigóticas A1A1 y A2A2A son 1-s1 y 1-s2 y la 1 la de la hembra heterocigota A1A2, la expresión se transforma en
#T555
#T556 
#T557
Resulta, como observación interesante, que si los coeficientes s1,s2,s3 son suficientemente pequeños, las frecuencias de equilibrio para ambos sexos son aproximadamente similares, tomando el valor
#T558

## 5.5 Relación entre selección y aptitud media poblacional
¿Incrementa la selección natural la aptitud media de una población? Existen diferentes formas de interpretar esta cuestión. En el ámbito de la ecología evolutiva, por ejemplo, diríamos que si una población incrementa su tamaño con el tiempo, es decirm aumenta su densidad como consecuencia de la selección natural, aumenta también su aptitud media. En el ámbito de la genética de poblaciones, otra forma de entender el incremento de aptitud es determinando si hay cambios en la composición genética de la población según las aptitudes relativas y evaluando la aptitud media. Vamos a concentrarnos, por el momento, en este segundo caso tanto para especies haploides como diploides.
## 5.6 Lastre genético
La noción de lastre genético representa una importante aproximación al estudio de las posibles limitaciones al crecimiento en aptitud media de las poblaciones. El lastre es precisamente **la diferencia entre la aptitud media de una población y la que tendrá esta población si sólo existieran individuos con el genotipo más apto**. NO existe un solo tipo de lastres, sino varios, dependiendo de qué factores estén actuando en el cambio de la composición genética de las poblaciones. En general, bajo un punto de vista teórico toda población variable tiene un lastre, aunque esto no significa que la variabilidad genética poblacional será negativa para la población, dadas la connotaciones negativas que se atribuye al lastre. Veremos a continuación algunos tipos de lastre y su significado.
## 5.6.1 Lastre segregacional
Mientras que una población de organismos asexuales conlleva, bajo el modelo de selección natural, la fijación del genotipo más apto, consiguiéndose así la máxima aptitud media, en el caso de una población diploide con reproducción sexual, el sistema genético mendeliano impone ciertas restricciones al logro de tal aptitud máxima. Así, debido a la segregación mendeliana de organismos diploides con reproducción sexual y en el caso de la ventaja del heterocigoto aparece un tipo de lastre denominado segregacional. Para entender esta afirmación se parte de la expresión de la aptitud media,w, de la población que aparece en #T540 y, por otro lago, del valor del equilibrio bajo ventaja del heterocigoto, pt=t/(s+t). Sustituyendo apropiaamente este valor en #T540 se obtiene:
#T570
$$
\bar{w}=1-sp_{t}^{2}-t(1-p_{t}^{2})=1-\frac{st^{2}}{(s+t)^{2}}-\frac{ts^{2}}{(s+t)^{2}}=1-\frac{st}{s+t}
$$
Como podrá apreciarse, la aptitud media de la población en equilibrio es menor que la mayor de las aptitudes, la que corresponde al heterocigoto(w_A1A2=1). Pero no hay que interpretar este resultado como que la población pierde aptitud. La siguiente argumentación sirve de justificación a tal afirmación. Supongamos que la población está formada inicialmente por genotipos A_2A_2. En ese caso la aptitud media es 1-r. Si se introduce en ella un alelo A1, por mutación o migración, entonces éste empieza a crecer en frecuencia y se llegará, bajo el modelo de ventaja del heterocigoto, a una aptitud media que vendrá dada por:
#T571
$$
\bar{w}=1-\frac{st}{s+t}\geq1-t
$$
ya que es fácil demostrar que:
$$
\frac{st}{s+t}\leq t
$$
Es decir, se ha dado un incremento en la aptitud, pasando de 1-t a 1-[st/(s+t)]. Por lo tanto no hay, ciertamente, una idea de pérdida de aptitud, sino simplemente una potencial pérdida en función del genotipo de referencia. En efecto, en una población donde todos los genotipos son A2A2 no parece tener sentido hablar de lastre, si comparamos con la máxima aptitud posible representada por el único genotipo existente. Si aparece un genotipo A1A2 en ella, entonces es éste el genotipo de referencia, el más apto ahora, por lo que el incremento en el lastre segregacional aparece por haber cambiado de genotipos de referencia. NO obstante, no hay una disminución efectiva de la aptitud media, sino sólo un valor positivo de lastre cuando se compara con la aptitud relativa del heterocigoto que es, por definición,1. El recuadro #t57 ayudará con un ejemplo.
### 5.6.2 El lastre mutacional en el equilibrio mutación-selección
En el apartado 5.4.1 se estudió el caso de un alelo recesivo cuyo homocigoto tenía una aptitud de 1+s, superior a la de los otros dos genotipos de la población. Ahora se examinará una situación en la que el alelo recesivo, por ejemplo A1, es deletéreo, y el genotipo A2A2 tiene una aptitud 1-s, mientras que los otros dos genotipos(A1A1 y A1A2) tienen aptitud 1. De forma paralela a como se vio en ese apartado(obsérvese que allí el alelo recesivo era el A2), se puede demostrar que el cambio por selección, variaciónq_j(véase[5.20]), en la frecuencia del alelo deletéreo recesivo es:
#T572
$$
\vartriangle q_{s}=\frac{s q^{2}p}{1-s q^{2}}
$$
donde el denominador es la aptitud media, puesto que p²+2pq+q²(1-s) =1-sq², y el numerador, algo más complicado de deducir, viene de restar al nuevo número de alelos A1 después de la selección, es decir pq+q²(1-s), el producto de la frecuenica del alelo q, por la aptitud media osea q(1-sp²). Es fácil intuir que el valor del incremento es negativo. En otras palabras, la frecuencia del alelo deletéreo por efecto de la selección va disminuyendo de generación en generación.
Simultáneamente se puede suponer que la mutación incrementa la frecuencia del alelo deletéreo. Como se examinará en el capítulo 9, la mayor parte de las mutaciones que ocurren en las poblaciones son de tipo deletéreos que éstos a estados de normalidad " funcional ". Por lo tanto, si el alelo A1, con frecuencia p, es un alelo normal, y u la probabilidad de mutación al alelo A2 deletéreo, entonces, exclusivamente por mutación se puede dar un incremento de la frecuencia del citado alelo. Es decir:
#T573
$$
\vartriangle q_{m}=up
$$
Como quiera que [5.72]y[5.73] son de digno opuestos, y suponiendo que la selección y la mutación actúan al mismo tiempo, puede darse un equilibrio entre selección contra un alelo deletéreo y mutación a favor del mismos. Es decir:
#T574
$$
\vartriangle q_{j}+ \vartriangle q_{m}=0
$$
O lo que es igual :
#T575
$$
up=\frac{s q^{2}p}{1-s q^{2}}
$$
Si consideramos que el denominador de [5.75] es =1, dado que en el equilibrio la frecuencia de un alelo deletéreo A2 es muy baja, entonces la frecuencia aproximadamente de equilibrio del alelo recesivo viene dada por:
#T576
$$
q=\sqrt{ \frac{u}{s} }
$$
Como puede observarse, la frecuencia de equilibrio del alelo deletéreo crece con la tasa de mutación y decrece con mayores valores de coeficientes de selección.
En el caso de que el alelo deletéreo fuera dominante, el valor del incremento por selección variaciónq_t cambia respecto del examinado en 5.72. En efecto:
#T577
$$
\vartriangle p=-\frac{sp^{2}q}{1-s(1-p^{2})}
$$
donde el denominador es la aptitud medai y ahora es p²+2pq(1-s)=1-s(1-p²), puesto que el heterocigoto A1A2 tiene la misma aptitud que el homocigoto dominante A2A2. Por otro lado, el numerador se obtiene de restar al nuevo número de alelos A2, pq(1-s)+q²(1-s), el producto del alelo A2, q, por la aptitud media, 1-s(1-p²). Razonando de forma singular al caso del alelo deletéreo recesivo, el equilibeio mutación-selección aparece cuando:
#T578
$$
up=\frac{sp^{2}q}{1-s(1-p^{2})}
$$
Si dividimos ambas partes de la desigualdad por p, sustituimos p y p² por 1-q y (1-q²) respectivamente y aproximamos a cero los términos cuadráticos que aparecen, la expresión 5.78 se transforma en:
#T579
$$
u=\frac{s q}{1-2s q}
$$
de donde,
#T580
$$
u-2s qu=s q
$$
Suponiendo  que el producto 2squ se aproxima a cero porque q y un son muy pequeños, el punto de equilibrio sería
#T581
$$
q_{t}=\frac{u}{s}
$$
De forma parecida a como ocurría con el alelo recesivo la frecuencia de equilibrio crece con la tasa de mutación y decrece con el coeficiente de selección.
Tanto a partir 5.76 como de 5.81 podemos llegar a sendas estimas de la tasa de mutación con tal de conocer el coeficiente de selección en contra del alelo letal, ya sea recesivo o dominante, y la frecuencia del alelo en cuestión en la población examinada. Para el caso en que, además el alelo en cuestión es parcialmente dominante véase el ejemplo que aparece en el recuadro 5.8.
En el apartado 5.6.1. se ha examinado el lastre segregacional de una población, que aparece como la diferencia entre la aptitud de una población con el genotipo óptimo (es decir 1), y la aptitud de media de la población en equilibrio bajo un determinado modelo de selección. ¿Qué lastre aparece en poblaciones con equilibrio mutación-selección? Para el caso de una mutación deletérea recesiva la medida del lastre(L) sería:
#T583
$$
L=1-(1-s q^{2})=s q^{2}
$$
En equilibrio véase 5.76
$$
q^{2}_{e}=\frac{u}{s}
$$
por lo que el lastre equivale a u, la tasa de mutación. De forma análoga, el laste para el caso de una mutación deletérea dominante será:
#T584
$$
1-[1-s(1-p^{2})]
$$
Si sustituimos p² por (1-q)² y aproximamos a cero el término sq², puesto que en el equilibrio  q es pequeño la expresión 5.84 se transforma en 2qs.
Como la frecuencia de equilibrio es q=u/s,  el lastre vale 2u. En consecuencia, el lastre genética introducido por una mutación deletérea varía entre u y 2u. Lo más sorprendente de este resultado es que el efecto de la mutación en la reducción de la aptitud media de la población es independiente del grado de severidad o letalidad de la misma, y sólo es directamente proporcional a la tasa de mutación. Esto se conoce como principio de Haldane-Muller del efecto de la mutación recurrente.
## 5.7 Conclusiones
1. La selección natural, parámetro fundamental de la evolución adaptativa, puede cambiar la frecuencia de los genes en las poblaciones.
2. La aptitud media de una población en una generación dada mide el incremento del número de individuos de la misma respecto de la generación anterior.
3. Dos poblaciones con crecimientos distintos, aunque puedan diferir en sus tamaños absolutos, no diferirán en su composición genética si las aptitudes relativas de sus genotipos son las mismas.
4. Un alelo incrementa su frecuencia de un alelo total recesivo no es lineal, sino más efectiva es la selección en reducir su frecuencia.
5. La disminución con el tiempo de la frecuencia de un alelo letal recesivo no es lineal, sino más bien asintótica, de forma que cuanto menos frecuente es el alelo en la población menos efectiva es la selección en reducir su frecuencia.
6. Los cambios y los incrementos de frecuencia que experimentan organismo haploides son similares a los de organismos diploides con aptitud multiplicativa.
7. Cuando los coeficientes de selección no son elevados (menos de 0,1), los cambio que experimenta la frecuencia de un alelo no son muy diferente bajo los modelos multiplicativo o aditivo de la aptitud biológica. Las diferencias son apreciables, en cambio, cuando los coeficientes de selección son mayores.
8. En ciertos casos existe un punto de equilibrio internos que es estable y polimorfismo se denomina protegido. Esto sucede, por ejemplo, cuando la aptitud del heterocigoto es superior a ambos homocigotos en un locus con dos alelos. Por el contrario, cuando el heterocigoyo es inferior en aptitud a los dos homocigotos, el equilibrio internos es inestable y el polimorfismo no puede mantenerse.
9. Se puede evaluar la naturaleza del equilibrio cuando la población sufre pequeñas perturbaciones que lo alejan del mismo. La estabilidad depende de la relación existente entre los coeficientes de selección de los genotipos. NO podemos determinar, en cambio frente a una gran perturbación que desplaza la frecuencia muy lejos del punto de equilibrio, si éste volverá a alcanzarse. A un equilibrio en el que, con independencia de la magnitud de la perturbación, se vuelve a él se le denomina equilibrio globalmente estable. Es muy difícil investigar si la naturaleza de un equilibrio es globalmente estable, puesto que aun no siendo globalmente estable(cuando se trata, por ejemplo, de una perturbación del 30%), sí puede serlo localmente, respondiendo favorablemente a una perturbación pequeña.
10. Si las frecuencias alélicas en un gen seleccionado en contra y ligado al sexo difieren en machos y hembras durante el proceso selectivo sus frecuencias oscilar alrededor de la frecuencia alélica promedio y tienden a converger.
11. En el caso de genes ligados al sexo se puede establecer un polimorfismo estable si hay ventajas de las hembras heterocigóticas y los machos no están sometidos a fuertes presiones de selección o, como parece lógico, con fuerzas de selección actuando en direcciones opuestas en ambos sexos.
12. Mientras exista varianza de la aptitud en la población, la población incrementará su aptitud media. A esto se le conoce como teorema fundamental de Fisher de la selección natural. La aptitud con las generaciones porque la varianza no puede ser negativa.
13. Toda población con variabilidad genética tiene una aptitud inferior a la de una población formada por individuos del genotipo con más aptitud. Esta diferencia se denomina lastre. Sin embargo, esto no implica que la aparición de un alelo de aptitud superior genere una disminución de la aptitud marginal, sino todo lo contrario, como demuestra el teorema fundamental.
14. El efecto de una mutación deletérea en reducir la aptitud media en una población en equilibrio es independiente de su coeficiente de selección, y directamente proporcional a la tasa de mutación, oscilando entre 1 y 2 veces dicha tasa. A esto se le conoce como el principio de Haldane-Muller.

#  Tema 9. La genética de poblaciones molecular
## Conceptos clave
Mutación y aptitud: en un intervalo de variación continua las mutaciones se pueden clasificar por su efecto sobre la aptitud en letales, deletéreas, ligeramente deletéreas, neutras, ligeramente desventajosas y ventajosas.
Teoría neutra de la evolución molecular: Teoría que sostiene que la mayor de los cambios evolutivos a escala molecular de las especies no son el producto de la selección positiva de los alelos ventajosos o de la selección estabilizadora, sino de la deriva genética de mutantes que son selectivamente neutros o casi neutros.
Tasa de sustitución/fijación: es una medida de la frecuencia con la que un alelo puede llegar a fijarse en una población.
Modelo de infinitos alelos: aquel en que cada mutación genera un alelo nuevo distinto de los ya presentes en la población.
Número eficaz de alelos: número de alelos de igual frecuencia en una población ideal que se requiere para producir la misma homocigosis que la que se observa en una población real.
Tiempo de fijación: tiempo medio necesario para que una mutación neutra, ventajosa o desventajosa se fije en una población o especie, condicionado a que se haya producido dicha fijación.
Mutación neutra: mutación cuya tasa de sustitución depende exclusivamente de la tasa de mutación.
Mutación casi neutra: mutación cuya tasa de sustitución depende exclusivamente del tamaño eficaz (Ne) de población, o lo que es loa mismo de la acción de la deriva genética. Aproximadamente, Ne debe ser mucho menor que 1/2s para que una mutación con coeficiente de selección s tenga una probabildiad de fijación significativa.
Diversidad nucleotídica: número medio de diferencias nucleotídicas por sitio nucleotídico.
## 9.1 Introducción: La controversia seleccionismo-neutralismo
Kimura en su libro sobre la teoría de la evolución molecular afirma que la gran mayoría de los cambios evolutivos a nivel molecular son causados no por la selección darqiniana positiva, sino por deriva genética de alelos neutros o casi neutros. La teoría ha tenido un gran impacto sobre la teoría de la genética de poblaciones y la evolución, especialmente en la última década, en buena medida por la posibilidad brindada por las técnicas procedentes de la biología molecular de constrastar experimental sus predicciones. Pero su mayor interés ha radicado en su oposición conceptual a la teoría seleccionista. La selección natural es el concepto clase de la teoría evolutiva, además, es historicamnete el primero en aglutinar y dar foma casual y, por tanto científica, a las diferentes disciplinas biológicas que se dedicaban al estudio de las transformaciones evolutivas. Que su operatividad explicativa le convirtió en el núcleo de la teoría evolutiva parece incuestionable. Aunque sólo sea por la cantidad de argumentaciones en torno a su papel determinante en la explicación del cambio orgánico, no cabe duda de su centralidad. La selección natural es esencial para comprender el cambio adaptativo, de tal suerte que los argumentos hiperseleccionista han sido fuerte criticado por aquellos que ven que hay otras formas de explicación del cambio o de la invariancia en evolución. La selección natural como  forma de explicación evolutiva ha supuesto  un punto de referencia para el desarrollo de explicaciones alternativas. Lo mismo puede decirse de la teoría neutra de la evolución molecular. Dos son a nuestro juicio las clases de su éxito. La primera radica en que se ha construido a la manera de las teorías físicas, es decir, razonando deductivamente sobre las consecuencias de determinados modelos para luego encontrar adecuadas verificaciones experimentales que han venido a ser cada vez más amplias. La segunda radica en la generalidad de sus conclusiones. Su razonamiento analítico, le ha dado potencia, más todavía cuando se ha verificado que, generalmente, sus predicciones eran buenas. La evolución molecular se ha encontrado con una teoría que ha suplantado la selección positiva como elemento central del cambio evolutivo.
Desde que fuera formulada, la teoría neutra se ha presentado como referencia para aquellos que pretendían encontrar explicaciones alternativas basadas en modelos selectivos más o menos sofisticados. Ella misma, pues, ha pasado ocupar, a escala molecular, el papel de la selección natural venía teniendo como punto de referencia de la teoría general de la evolución. Tal situación ha sido de enorme importancia conceptual para la propia teoría general de la evolución, dado que deja de utilizarse la selección natural como concepto panexplicativo. Por supuesto que el neodarwinismo se ha resistido a la inclusión de nuevas teorías, como era de esperar desde la óptica de la dinámica de la ciencia en la gestación de nuevas teorías científicas. Es el caso, por ejemplo, en otros niveles de la jerarquía biológica, de las explicaciones de los patrones del cambio morfológico alternativas a la selección natural, lo que nos lleva en la actualidad a un fascinante impasse de explicaciones encontradas. La teoría neutra, que también ha recibido el ataque científico del neodarwinismo, ha resistido con éxito y, de hecho, se ha convertido en una explición efectiva de la variación genética a escala molecular. En otras palabras, la teoría neutra es una hipótesis nula alternativa a la teoría seleccionista. La teoría se encuadraría dentro del conjunto de modelos explicativos en ciencia que tienen al azar como punto de referencia. Son los llamados modelos neutros, que tanta importancia parecen tener en aquellas ciencias donde el nivel de complejidad del fenómeno a estudiar o, por qué no, la propia madurez teórica de la disciplina posibilita la incorporación del tipo de aproximaciones. En cualquier caso el efecto de la teoría neutra ha sido sinérgico, porque ha vigorizado la propia teoría general de la evolución al dar con formas de explicaciones de la evolución alternativas a la selección natural, pero también ha promovido y acelarado un nuevo campo de investigación e incitado a los neodarwinistas a lograr explicaciones seleccionistas efectivos de la variabilidad genética a escala molecular.
Llegados a este punto, cuando a escala molecular se hbala de eevolución enutra y no neutra, podemos preguntarnos ¿qué son exactamente?

Aunque sea una posición anticipatoria por nuestra parte nos decantamos por la segunda acepción. Como tendremos oportunidad de mostrar a lo largo de este capítulo, la esencia del debate entre neutralista y seleccionistas radica en la forma de la distribución de aptitudes de los alelos mutantes. Ambos consideran que una gran mayoría de las mutaciones en proteínas son deletéreas, y que ésas son eliminadas por selección purificadora, no contribuyendo al proceso de sustitución ni al polimorfismo de las poblaciones. Pero divergen en cuanto a la cantidad de mutaciones no deletéreas que son de tipo neutro, puesto que los seleccionistas mantienen que son pocas las mutaciones neutras no deletéreas y los neutralistas que la mayor parte de ellas son efectivamente neutras.
Lo cierto es que la genética de poblaciones es una disciplina que en la actualidad tiene incorporadas esas dos teorías, maxime cunado no se puede afirmar que sólo la aproximación neutra o la seleccionista es suficiente para explicar la evolución a escala molecular, pero al mismo tiempo incorporar también situaciones donde participa la selección de forma total o parcial en combinación con la deriva genética y la mutación. Así, se estudiarán, por un lado, modelos sencillos donde la mutación es el único factor que altera el equilibrio genética poblacional, para luego abordar los cambios genéticos que experimentan las poblaciones bajo el supuesto de la acción combinada de diferentes parámetros como la mutación, la deriva genética y la selección.

## 9.2 La dinámica de la mutación
La mutación es la fuente primera del cambio evolutivo y, por tanto, su comprensión es fundamental para apreciar su relevancia para el cambio de la estructura genética de las poblaciones y, en última instancia para la evolución. Curiosamente, a pesar del carácter aleatorio de la mutación, su efecto sobre el cambio de la frecuencia alélica es determinista, pues suponemos que la tasa o probabilidad de mutación toma un valor constante por generación.
Las mutaciones tienen contribuciones bien distintas a la aptitud de los individuos portadores de las mismas. La figura muestra una distribución hipotética de las mutaciones según sus efectos sobre la aptitud. Como puede observarse la distribución es binomial, de forma que, por un lado, se tiene una amplia gama de mutaciones deletéreas, estrictamente letales o casi letales, que forman, el primer pico de la distribución, para luego, después de pasar por un intervalo de mutaciones desventajosas, llegan a un segundo pico que contienen las llamadas mutaciones neutras que incorporan las estrictamente neutras y las casi neutras. Estas últimas agrupan, a izquierda y derecha de las neutras, las que son ligeramente desventajosas y ligeramente ventajosas, respectivamente. Por último, en la zona descendente del segundo piso, se tienen las mutaciones ventajosas.
### Equilibrio poblacional bajo mutación
El modelo más sencillo consiste en suponer que el alelo A1 de frecuencia p, tiene una probabilidad u de mutar a otro alelo A2(de frecuencia q) y que éste puede volver a mutar con una % v al alelo A1(retromutación). En ese caso, el cambio en la frecuencia del alelo A2 bajo mutación exclusivamente viene dado por:
#T91
$$
\vartriangle q= up-vq=u-q(u+v)
$$
Como puede observarse el valor del incremento viene del posible aumento de la frecuencia del alelo A2 por mutación del alelo A1(es decir up) y de la disminución de la citada frecuencia por mutación del alelo A1(vq). Aq es una función lineal de q. El valor máximo del incremento del alelo A2 aparece cuando q=0, en cuyo caso el valor del incremento es la tasa de mutación, , y su valor máximo de decrecimiento aparece cuando q=1, en cuyo caso el valor del incremento es -v. Como quiera que las tasas de mutación suelen ser muy pequeñas, los cambios que experimentan de generación en generación las frecuencias de los alelos debido a la acción exclusiva de la mutación son pequeños. La mayor parte de las mutaciones suelen ser deletéreas, de forma tal que es más probable, suponiendo que el alelo A1, no es deletéreo, que pase a serlo, que la probabilidad de que aparezca A2 a partir de un alelo deletéreo. Sin otros parámetros en acción sobre el cambio de las frecuencias alélicas debería incrementarse en la población la frecuencia de alelos deletéreos, pero este cambio, como vamos a ver, es lento bajo la acción exclusiva de la mutación. En efecto, supongamos una situación extrema, donde v=0. En ese caso la frecuencia del alelo A1 es:
#T92
$$
p_{1}=p_{0}-up_{0}=(1-u)p_{0}
$$
Resulta fácil, por iteración a partir de #T92, obtener el valor de la frecuencia del alelo A1 al cabo de generaciones. En efecto:
#T93
$$
p_{t}=(1-u)^{t}p_{0}
$$
Como ocurre con otros parámetros también la mutación puede llevar a un equilibrio poblacional de las frecuencias alélicas, situaciones que aparece cuando Aq=0. En ese caso sustituyendo en #T91 se obtiene:
#T94
$$
q=\frac{u}{v+u}
$$
## 9.3 La teoría neutra de la evolución molecular
