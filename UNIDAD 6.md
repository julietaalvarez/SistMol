##UNIDAD 6. PRUEBAS ESTADÍSTICAS PARA LAS HIPÓTESIS FILOGENÉTICAS##

- Acabamos de aprender cómo se hacen los análisis filogenéticos, sin embargo siempre debe quedar claro que los árboles resultantes de estos análisis son hipótesis.
- Siempre cabe la probabilidad de que los resultados a los que llegamos no sean verídicos.
- El árbol más óptimo **no debe ser asumido como el árbol verdadero**
- Todas las hipótesis filogenéticas deben ser tomadas en cuenta como estimaciones de la historia verdadera.

###6.1 Detectanto no-azar en los datos###

- Nosotros siempre asumimos que los árboles que obtuvimos provienen de señal filogenética derivada de los datos con los que armamos el árbol.
- Y esto se refiere a que muchas veces podemos encontrar árboles que estén mejor resueltos y mejor "soportados" sólo por mera probabilidad
- Es por ello que es importante determinar que los datos estén libres de azar, es decir que la topología no haya resultado por azar.
- Para saber si estamos tratando con topologías azarosas, podríamos prestar atención en los grupos donde tengamos conflictos, donde haya taxa "sobrelapados", pues tienen homoplasia.
- En la matriz de datos nosotros podemos observar los caracteres donde una caracter contradiga a otros. 

> NOTA: es sumamente difícil discernir a *ojo de buen cubero* cuáles son los caracteres moleculares que muestran homoplasia

###6.2 Mediciones del soporte de los clados###

- Aunque los datos sí contengan señal filogenética, eso no quiere decir que todos los clados estén igualmente soportados en los árboles estimados.
- Necesitamos tener la forma de anotar en los clados el **soporte** de los datos
- Una medida simple del soporte de los clados es observando las diferencias entre las puntuaciones de los árboles más óptimos. 

> En el caso de **parsimonia** se usa el ***index decay***, o también llamado el soporte de Bremer.
En **máxima verosimilitud** se utiliza el ***likelihood ratio***, que es la diferente entre los valores de log-likelihood en los árboles óptimos. Tanto el *index decay* como el *likelihood ratio* se pueden entender en el contexto del universo de árboles.
Estos son útiles como valores de soporte de los clados, sin embargo el número de caracteres y los estados de caracter afectan estos valores.

###6.3 Análisis de Bootstrap no paramétrico###
- El ***bootstrap* no paramétrico** o sólo *bootstrap* ha sido fuertemente usado para evaluar el soporte de los clados en análisis filogenéticos. Este fue propuesto por Felsenstein en 1985.
- El *bootstrap* trata de evaluar sus posibilidades de recuperar un clado de nuevo si hemos si pudiéramos remuestrear un nuevo conjunto de caracteres.
- Esta herramienta lo que genera es un remuestreo, con reemplazamiento, de los datos. A esto se le conoce como **pseudoréplicas** porque en realidad estamos tomando nuestros datos ya existentes y volvemos a tomarlos.
- Como el *bootstrap* muestrea diferentes caracteres, puede dar resultados de un árbol óptimo diferente al árbol óptimo "original". Es decir, los árboles de máxima parsimonia y máxima verosimilitud pueden no corresponder con el árbol más óptimo encontrado por *bootstrap*
- Entonces una vez hecho el *bootstrap*, se calcula el valor de *bootstrap* o su porcentaje.
- Es común que en las publicaciones se muestre el **árbol consenso de *bootstrap***, que está compuesto por el árbol con mejores soportes de bootstrap en sus clados.
