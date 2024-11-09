Aquí desarrollamos ecuaciones que predicen frecuencias alélicas en la próxima generación, dadas las frecuencias alélicas en esta generación y las aptitudes para los genotipos. Comenzamos con un acervo genético en el que el alelo *A1* está en la frecuencia *p* y el alelo *A2* está en la frecuencia *q*. Permitimos que los gametos se apareen al azar para formar cigotos de genotipos *A1 A1 , A1 A2* y *A2 A2* en las frecuencias *p2, 2pq y q2*, respectivamente. Incorporamos la selección imaginando que los cigotos *A1 A1* sobreviven hasta la edad adulta a una tasa *w11* , los cigotos *A1 A2* sobreviven a una tasa *w12* y los cigotos *A2 A2* sobreviven a una tasa *w22* .
Todos los sobrevivientes producen el mismo número de descendientes.
Por lo tanto, la tasa de supervivencia de un genotipo es proporcional al éxito reproductivo de por vida del genotipo, o aptitud.
Por lo tanto, nos referimos a las tasas de supervivencia como aptitudes. La aptitud promedio para toda la población, *w*, está dada por
$$
w=p^{2}ww_{11}+2pq_{w_{1}2}+q^{2}w_{22}
$$

Para ver esto, note que podemos calcular el promedio de los números 1, 2, 2 y 3 como 11 + 2 +4 2 + 32 o como 114 * 12 + 112 * 22 + 114 * 32. Nuestra expresión para la aptitud promedio es de la segunda forma: Multiplicamos la aptitud de cada genotipo por su frecuencia en la población y sumamos los resultados.]
Ahora calculamos las frecuencias genotípicas entre los adultos sobrevivientes (justo antes de que produzcan gametos).
Las nuevas frecuencias de los genotipos son:
$$
\begin{align}
A_{1}A_{1}\ A_{1}A_{2}\  A_{2A_{2}} \\
\frac{p^{2}w_{11}}w{} \frac{2pqw_{12}}w{} \frac{q^{2}w_{22}}w{}
\end{align}
$$
(Tenemos que dividir por la aptitud promedio en cada caso para asegurar que las nuevas frecuencias sigan sumando 1.)

Finalmente, dejamos que los adultos se reproduzcan y calculamos las frecuencias alélicas en el nuevo acervo genético:

Para el alelo *A1*: los individuos *A1 A1* contribuyen
$$
\frac{p^{2}w_{11}}w{}
$$
de los gametos, todos ellos *A1* , y los individuos *A1 A2* de los gametos, la mitad de ellos A1 .
La nueva frecuencia de A1 es, por lo tanto,
$$
\frac{p^{2}w_{11}+pqw_{12}}w{}
$$

Para el alelo *A2*: A1 A2 los individuos contribuyen
$$
\frac{2pq_{12}}w{}
$$

de los gametos, la mitad de ellos *A2* ; los individuos *A2 A2* individuos contribuyen
$$
\frac{q^{2}w_{22}}w{}
$$
de los gametos, todos ellos A2 . Entonces la nueva frecuencia de *A2* es
$$
\frac{pqw_{12}+q^{2}w_{22}}w{}
$$
El lector debe confirmar que las nuevas frecuencias de *A1 y A2* suman 1.
Resulta instructivo calcular el cambio en la frecuencia del alelo A1 de una generación a la siguiente.
Este valor, Δp, es la nueva frecuencia de A1 menos la antigua frecuencia de A1:
$$
\begin{align}
\Delta p=\frac{p^{2}w_{11}+pqw_{12}}w{-p} \\
=\frac{p^{2}w_{11}+pqw_{12}}w{-\frac{pw}{w}} \\
=\frac{p^{2}w_{11}+pqw_{12}-pw}w{} \\
=\frac{p}w{(pw_{11}+qw_{12}-w)}
\end{align}
$$

La expresión final es útil, porque muestra que el cambio en la frecuencia del alelo A1 es proporcional a
$$
(pw_{11}+qw_{12}-w)
$$
La cantidad
$$
(pw_{11}+qw_{12}-w)
$$
a veces se denomina exceso promedio del alelo *A1*. Es igual a la aptitud promedio del alelo A1 cuando se lo empareja al azar con otros alelos
$$
(pw_{11}+qw_{12})
$$
menos la aptitud promedio de la población *w*. Cuando el exceso promedio del alelo *A1* es positivo, la frecuencia de *A1* aumentará. En otras palabras, si el individuo portador promedio de *A1* tiene una aptitud mayor que el promedio, entonces la frecuencia del alelo *A1* aumentará.
El cambio en la frecuencia del alelo A2 de una generación a la siguiente es
$$
\begin{align}
\Delta q=\frac{pqw_{12}+q^{2}w_{22}}w{-q} \\
=\frac{q}w{(pw_{12}+wq_{22}-w)}
\end{align}
$$