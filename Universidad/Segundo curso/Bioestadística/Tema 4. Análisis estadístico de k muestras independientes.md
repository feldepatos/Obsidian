# Diseño de experimentos con *k* muestras independientes
Condiciones sobre el diseño del experimento
- Las muestras de cada grupo pueden considerarse muestras aleatorias de sus correspondientes poblacionales.
- Las muestras deben ser todas independientes entre sí.


---
# Comparación de medias: Análisis de la varianza (ANOVA)

¿Son  los datos  compatibles con la hipótesis  de que las medias de las *k* poblacionales son iguales?
$$
\text{Contraste de hipótesis para} \ H_{0}: \mu_{1}=\mu_{2}=\mu_{3}=\dots=\mu_{k}.
$$
**Definición**
Procedimiento correcto:  Análisis de la varianza(ANOVA)
$$
\begin{align}
H_{0}: \mu_{1}=\mu_{2}=\mu_{3}\dots \mu_{k} \\
H_{A}: \text{No se cumple} \ H_{0}
\end{align}
$$
Procedimiento incorrecto: comparar   las medias poblacionales de los  grupos dos a dos con un test t:  *mui=muj, i=!j*. SI la hipótesis nula  H0:mu1=mu2=mu3...=muk es cierta, la probabilidad de rechazarla  es más alta de lo  que  debería  ser.

##  Procedimiento ANOVA
Condiciones sobre el diseño del experimento
- Las *k* distribuciones poblacionales de la variable Y deben ser:
	- Normales (o las muestras deben ser suficientemente grandes).
	- Asumir para todas ellas la misma varianza, sigma².
- Si las distribuciones poblacionales son normales, pero no se cumple la condición de igualdad de las varianzas, utilizaremos el ==test de Welch==.
- Si las distribuciones poblacionales no son normales(y las muestras son pequeñas), emplearemos un método no paramétrico para comparar las *k* poblaciones, ==el test de Kruskal-Wallis==.

### Análisis de la  varianza (Tabla ANOVA)
La información que proporcionan todas las muestras suele expresarse en forma de tabla, tabla ANOVA, siendo *n* el número total de observaciones y *k* el número de grupos.

![[Pasted image 20250601204354.png]]
Pasos a seguir
1. Seleccionar el nivel de significatividad alpha.
2. Calculamos el valor estadístico de contraste_ *Fs*=CM(Entre)/CM(Intra).
3. Calcular el p-valor del contraste: área a la derecha del estadístico *Fs* según la distribución *F* con grados de libertad *k-1* (numerador) y *n-k* (denominador).
4. Si p-valor < alpha, rechazamos *H0*.


--- 
# Comparación de medias con varianzas distintas: Test de Welch



---
# Alternativas no paramétricas: Test de Kruskal-Wallis



---