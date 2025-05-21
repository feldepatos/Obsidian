# Una ojeada a los sistemas  de reparación

## Sistemas de prevención
Evitan los errores antes de que ocurran
Detoxificación: neutralizan los efectos de algunos agentes causantes de daños en el DNA
1. Sistemas SOD
	- Previene los efectos nocivos de los agentes oxidantes
		- Superóxido dismutasa
			- Radicale superódico→H2O2
		- Catalasa
			- H2O2→H2O
2. Gen mutL
	- Modifica para la 8-oxo-dGTP difosfatasa, que hidroliza el trifosfato de la 8-oxo-G a la forma monofosfato impediendo su incorporación al DNA.

## Sistemas de reparación

1. Prereplicativos
	1. Reversión directa al daño
		1. Fotorreactivación
			- ¿Qué es?
				- Es un sistema de reparación directa de los daños producidos por la luz UV.
			- Proceso
				- La luz produce dímeros de pirimidinas(T)
				- Reconocimiento de los dímeros de  T por la fotoliasa
					- Codificada por el gen **phr**
				- Eliminación de los dímeros  por  la exposición  a la luz.
		2. Alquiltransferasas
			- Eliminan grupos alquilo producidos por agentes alquilantes(EMS/NG)
				- Requiere enzimas "suicidas": el grupo alquilo se une de forma  irreversible  al -SH  de una Cys.
			- El sistema puede saturarse
	2. Reparación por escisión de bases
		-  Proceso
			- Catalizada por una DNA glicosilasa que es capaz de reconocer  un  tipo  específico de base modificada + romper el enlace glucosídico entre el glucido y la base.
			- La reparación de los sitios AP la llevan a cabo las endonucleasas AP de la clase I + II, cortan por el extremo 3' y 5', respectivamente.
			- La DNA  pol I  rellena el hueco.
			- Ligasa sella los extremos
		- Componentes
			- DNA  glicosiladas específicas
			- Endonucleasas AP
			- DNA-Pol I
			- DNA-ligasa
	3. Reparación general por escisión de nucleótidos
		- Reparar daños voluminosos en el DNA que distorsionan su estructura.
		- Esto libera  los posibles bloqueos de las horquillas de la replicación y las paradas de la transcripción.
2. Postreplicativos
	1. Reparación de apareamientos incorrectos
		- El sistema ha de ser capaz
			1.  Reconocer pares de bases mal apareadas
			2. Determinar cuál de las dos bases es la incorrecta
			3. Eliminar la región que contiene el error y repararlo
		- La reparación la realizan los productos de los genes mutH, mutL, mutS y mutH.
		- Para distinguir la hélice de nueva síntesis y así  de eliminar la base incorrecta, el sistema utiliza el retraso de la formación de la nueva hélice al secuencia GATC, porque está metilada en la cadena doble.
		- GATC es reconocida por Metalisa Adenina
			- Codificada por el gen **dam**
		- Sistema mutSLH en *E.coli*
			- ¿Qué es?
				- Es un complejo mutS mutH que provoca esciciones en la cadena no metilada(cadena hija)
			- Proceso
				1. Reconocimiento del emparejamiento incorrecto por parte del complejo
					1. mutS
						- Reconoce el par desapareado.
					2. mutL
						- Es una proteína estabilizadora del complejo de proteínas+DNA
				2. Escisión del GATC de la cadena no metilada por  parte del mutH
				3. Eliminación del segmento de la cadena que tiene el emparejamiento mediante un exonucleasa+endonucleasa.
				4. Estabilización de la cadena sencilla (Proteínas SSB)+Relleno del hueco(DNA pol I).
				5. Metilización de la secuencia GATC por la proteínas DAM.
	2. Reparación por recombinación
3. Errores graves
	1. Reparación SOS
		- ¿Qué es?
			- Es un sistema de emergencia que se activa enfrente a lesiones graves en el DNA+agentes inhibidores de la replicación.
		- Características
			- Sismtea complejo donde intervienen más de 20 genes
			- Objetivo
				- Asegurar la supervivencia celular
		- Principales genes reguladores:
			- LexA
				- Regula la expresión de los genes SOS
				- El dímero se une al  operador inhibiendo la expresión.
			- RecA
				- Proteínas de unión a ssDNA
				- Unida al DNA tiene actividad proteasa.
		- Proceso
			- General
				- El proceso comienza por la activación de la proteína RecA, por parte del ADN sencillo, que a su vez  interactua con LexA, quien es un represor de ciertos genes(uvrA, uvrB, uvrA, sulA y sulB). Estos genes presentan una secuencia llamada caja SOS. Entonces la interacción entre los genes RecA y LexA  impiden la expresión de los genes, pudiendo sintetiza las proteínas correspondientes y repara los daños producidos,
			- Pasos de la **Síntesis de DNA translesión**
				1. Reconocimiento de las regiones sencilla por RecA
				2. Promoción del corte autolítico de 3 proteínas  por RecA
				3. Inactivación del represor LexA
					- Que induce  la expresión de un conjunto de genes
				4. Formación del complejo Umud'  a partir del Umud' +UmuC
					-  El Umud' proviene del corte en esa región por parte del RecA que promueve su corte.
				5. DNA polimerasa V-RecA-ATP añade nucleótidos al azar
					- Gracias a la capacidad que tiene DNA-polimerasa V  de poder añadir nucleótidos sin un DNA molde.
				6. Vuelta a la  normalidad, LexA  vuelve a reprimir la  expresión de muchos genes.
	2. Reparación de roturas de cadenas dobles
		- Existen sistemas de reparación que unen extremos de DNA de doble cadena pudiendo generar reordenaciones cromosómicas si los extremos no eran contiguos en el individuo normal.
		- Las roturas de cadenas dobles inician muchos tipos de recombinación, por tanto, no introducen mutaciones.
--- 
# El mecanismo de la recombinación

En un principio se describió a la recombinación como el responsable del entrecruzamiento e intercambio de segmentos de DNA entre cromosomas homólogos durante la meiosis de las células eucariotas. Poco después, como el proceso implicados en la integración del DNA transferido al genoma bacteriano durante los procesos parasexuales bacterianos.

Actualmente como un reparador posreplicativa del DNA, mientras que la primera definición del proceso sería algo secundario.

A raíz de la recombinación  surgen individuos recombinantes
1. Recombinación homóloga
	- Es necesario una homología de secuencias entre las dos moléculas de DNA implicadas
		- No tienen que ser la misma región de los cromosomas homólogos.
2. Recombinación específica de sitio
	- Restringida a zonas muy concretas
3. Recombinación ilegítima
	- Moléculas con ↓ poca o ninguna homología de secuencias
		- Elementos transponibles

---
# El proceso de la recombinación homóloga
Implica la rotura de y unión de moléculas de DNA

Tipos
1. Recombinación recíproca
	- Las dos moléculas recombinantes son equivalentes
2. Recombinación no recíproca
	- Una de las moléculas actúa como donante
3. Recombinación intramolecular
	- Solo participa una molécula
	- Afecta o se da entre regiones repetidas.

---
# El modelo de rotura y reunión propuesto por Holliday
Hay varios modelos que intentan explicar la **recombinación homóloga**, y todos comparten algunas características comunes.
Primero, todos se basan en las propuestas iniciales que, independientemente, propusieron Robin Holliday y Harold L. K. Whitehouse en 1964.

Proceso
1. Alineación de los cromosomas homólogos+cortes monocatenarios en la misma posición de ambas moléculas de DNA.
2. Migración de un extremo libre de cada cadena a la otra.
3. Unión Holliday(el extremo se une a la otra cadena)+ Inicio del desplazamiento a la cadena complementaria original.
4. Creación de moléculas dúplex a partir del desplazamiento de la cadena pero cunado las dos cadenas nucleótidas intercambina posiciones.
5. Los extremos de los 2 dúplex interconectados se separan uno del otro.
6. Rotación de la mitad inferior de la estructura.


Conclusión
- El modelo de Holliday predice la presencia de DNA recombinante sin entrecruzamiento o con él, lo que depende de la escisión en el plano horizontal o en el vertical.

Enzimas que participan en *E.coli*
- RexBCD
	- Actividad helicasa y nucleasa
	- Realiza  el corte inicial y desenrolla  el  DNA
- SSB
	- Estabiliza el DNA de cadena sencilla
- RecA
	- Afinidad por el DNA de cadena sencilla+necesita ATP.
	- Cataliza la invasión de las cadenas y el desplazamiento de la cadena residual
- RuvA+RuvB
	- Catalizan la migración del punto  de intersección→gastan ATP.
- RuvC
	- Resolución del intercambio de  Holliday

El proceso se sustenta por los productos de los genes rec como RecBCD, quien es la que inicia todo el proceso, porque reconoce la secuencia *chi*, provocando una mella en el  DNA de tal forma que la proteína RecA  provoca el desplazamiento  de una de las cadenas del DNA dúplex homólogo.

Existen variantes del modelo de Holliday
- Modificación del modelo de Holliday propuesta por Meselson-Radding
	- En este modelo se producen dos roturas simultáneas en las dos cadenas, pero se mantiene el proceso globalmente como el intercambio en cruz y la migración de la rama.
- Modelo de rotura de doble cadena
	- A diferencia del modelo de Holliday, se produce un corte bicatenario(no monocatenario)
- Recombinación específica
	- No requiere de amplias homologías
	- +Enzimas  específicas


|             | Modificación del modelo                  | Modelo  de rotura de doble cadena                                                   | Recombinación específica de sitio                                                         |
| ----------- | ---------------------------------------- | ----------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------- |
| Diferencias | 2 roturas simultáneas                    | Corte  bicatenario                                                                  | NO requiere de ↑ regiones de homologías+más enzimas específicas                           |
| Similitudes | Intercambio de crux+migración de la rama | Desplazamiento de las cadenas+síntesis de DNA+resolución de las uniones de Holliday | Invasión de cadenas+intermediarios  de hollliday+migración  de la intersección+resolución |


--- 

# DNA  híbrido, reparación de apareamientos erróneos y conversión  génica

¿Qué es?
- Proceso en el que dos secuencias interaccionan de tal forma que una  de las dos cambia sus secuencias idéntidas a la otra.
	- Es un proceso no  recíproco, porque solo una de las cadenas cambia.

Se puede dar en secuencias similares, independientemente de su localización, pero  la más común se da entre cromosomas homólogos.
## Corrección del  DNA heteroduplex en la región en que difieren los alelos.

Las zonas DNA  heteroduplex son regiones  donde las cadenas están desapareadas porque es el sitio de intercambio. Es el sitio de actuación de las enzimas reparadoras, que reemplazan estas "malas" regiones  por la  adecuada(conversión de un alelo por otro).

Esta conversión puede generar enfermedades. Por ejemplo la conversión  génica en el gen PRSS1 a PRSS2 o  viceversa no resulta dañina porque son un 89% idénticas  pero en  caso que convierta  en otra,  sí que ocasiona graves enfermedades como la pancreatitis hereditaria. 
## El modelo de Holliday explica la conversión génica

La conversión génica es consecuencia de la recombinación del DNA, porque la conversión génica se caracteriza por un intercambio genético *no recíproco* entro dos genes ligados muy próximos. Sin embargo, un intercambio *no recíproco* produce sólo un par, sin el otro.

Para tomar esa expresión como verdad debemos interpretar la conversión  como un mal emparejamiento  de pares de bases durante la formación del heterodúplex en la recombinación genética. Las regiones mal  emparejadas de  las cadenas híbridas se pueden reparar mediante la ecsisión de una  de las  cadenas y la síntesis de la complementaria utilizando de molde la cadena que queda.La escisión puede producirse en cualquiera de las dos cadenas, produciendo dos posibles «correcciones». Una repara el par de bases mal emparejado y reestablece la secuen-
cia original. La otra también corrige el desemparejamiento, pero lo hace copiando la cadena alterada, creándose una sustitución de un par de bases. La conversión puede tener el efecto de hacer alelos idénticos en dos homólogos que eran inicialmente diferentes.
En el ejemplo de la Figura 11.19, suponga que el par G‚C de uno de los dos homólogos corresponde al alelo mutante, mientras que el par A“T forma parte de la secuencia génica silvestre del otro homólogo. La conversión del par G‚C en
A“T tendría el efecto de cambiar el alelo mutante a salvaje,
exactamente como Mitchell observó.