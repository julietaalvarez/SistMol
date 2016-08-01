#UNIDAD 4. EVOLUCIÓN DE CARACTERES#

- Imaginemos que tenemos una población donde todos tienen píleos color rojo y tras una mutación se forma el fenotipo azul. Después de varias generaciones los píleos azules se vuelven más comunes. En este caso el color rojo es **ancestral** y el azul es **derivado**.
- Con el paso de varias generaciones el píleo azul incrementa su frecuencia y favorece al hongo. Finalmente después de muchas generaciones, toda la población adquiere el píleo de color azul hasta haberse **fijado**.

![drift.png](drift.png)

- A nivel de especie, a través de las generaciones el fenotipo evolucionó. La población inicial tenía un **estado de caracter ancestral**: píleo rojo. Y después de muchas generaciones se fijó un **estado de caracter derivado**, el píleo azul.
- El tiempo de mutación a fijación del estado de caracter derivado lleva muchas más generaciones que las que generalmente una vida humana puede observar.
- Por eso usamos los árboles filogenéticos como  hipótesis de los cambios en la evolución de los organismos.

>OJO: tenemos que saber discernir entre lo que es un caracter y sus estados de caracter.

 ```
Ejercicio: sugieran caracteres y estados de caracter de su hongo favorito
 ```

>Por ejemplo la hipótesis de la evolución de las trufas

![sequestrate_evolution.gif](sequestrate_evolution.gif)
![truffle.gif](truffle.gif)

Tomada de Lassoe & Hansen (2007)

###4.1 Estados de caracter ancestrales y derivados###
- Cualquier caracter con dos estados alternativos tienen **polaridad**, es decir la dirección de evolución: uno de ellos es el ancesttral y el otro derivado.

- Determinar la polaridad de los caracteres es importante para la evidencia filogenética.
- En este sentido hay caracteres que son **plesiomórficos**, es decir estados de caracter ancestrales y **apomórficos**, estados de caracter derivados. Los estados de caracter derivados compartidos se llaman **sinapormorfias**.  Y los grupos que comparten estados de caracter ancestrales se conocen como **simplesiomorfias**.

>Debemos tener como objetivo *siempre encontrar sinapormofias*, evidenemente asociados a grupos monofiléticos.

###4.2 Evolución de secuencias de DNA###
- El *fenotipo* siempre es el resultado de los cambios en el DNA, mientras que *no todos los cambios en el DNA son visibles*. 
- Prácticamente todos los cambios en el fenotipo son heredables y son atribuidos a cambios en el DNA.
- Recordemos que la doble cadena del DNA está compuesta de nucleótidos. Si tenemos una copia idéntica de la posición de los nucleótidos en todos los descendientes, hablamos de **homología**.
- La replicación del DNA es imperfecta, lo que puede generar mutaciones puntuales en las posiciones de nucleótidos. Si el nucleótido es reemplazado por uno distinto le llamamos **sustitución**.

 ![substitution.jpg](substitution.jpg)

- También podemos encontrar en las secuencias **deleciones**, es decir pérdida de nucleótidos o **inserciones**. 

>Cuando hacemos alineamientos a las inserciones/deleciones se les llama ***indel***.

- Tanto las sustituciones como caracteres morfológicos son interpretados como evidencia independiente de la estructura del "árbol verdadero".

###4.3 Introducción a la homología###
- Como dijimos antes, en las secuencias de DNA se considera homología sino hay sustituciones. Sin embargo, la morfología no tiene que ser completamente idéntica a su ancestro; aunque los caracteres fenotípicos son heredables.

-También existen caracteres que evolucionan de manera independiente en dos organismos distintos, a lo cual llamados **convergencia evolutiva**. No es homología.

- Hay casos donde este caracter que parece ser **autapomorfias** (caracteres derivados únicos), en realidad podrían tratarse de **reversiones** de un estado ancestral.

>Recuerden que la homología se basa en tener un ancestro en común, no similitud. Por ejemplo:

 ![Thelephora.jpg](Thelephora.jpg)
 ***Thelephora versatilis* Ramírez-López & Villegas** 
 ![Tversa.jpg](Tversa.jpg)
 ***Thelephora pseudoversatilis* Ramírez-López & Villegas** 
 ![Tpseudo.jpg](Tpseudo.jpg)
 
Tomada de Ramírez-López et al. 2015

###4.4 Homoplasia y consistencia###
- La **homoplasia** se da cuando los estados de caracter se encuentran en más de un grupo dentro de un árbol. La convergencia evolutiva es un tipo de homoplasia.
>OJO: Homología *NO* es lo opuesto a homoplasia. Homología se refiere a la relación entre caracteres en diferentes taxa, mientras que homoplasia se refiere a la relación entre la variación de los caracteres en un árbol en específico.

- La **consistencia** es lo opuesto a la homoplasia. Un caracter es consistente cuando evoluciona sin cambios extra o cambios de estado. 

>Por ejemplo: píleo rojo o píleo azul; sólo hay un cambio entre ellos

- La consistencia se mantiene si el número de cambios de caracter es uno menos que el número de estados de caracter.

- Una forma útil de cuantificar la consistencia es usando el ***consistency index* (CI)**. Este índice reporta el número de cambios mínimos necesarios para explicar la evolución de los caracteres (**Lmin**), que es uno menos que el número de estados de caracter; dividido entre el número de cambios de estado observados (**Lobs**).

 ```
CI=Lmin/Lobs
 ```
 
![CI.png](CI.png)
Tomado de Tree thinking

- También existe el **índice de retención (RI)** que también es ampliamente usado. Este corrige el número máximo de pasos que el caracter puede tener en un árbol (Lmax).

```
RI=(Lmax - Lobs)/(Lmax - Lmin)
 ```
> Muchas veces se prefiere el RI ya que usa un rango del 0 al 1.

- Ambos índices proveen una forma de medir la concordancia entre los caracteres y el árbol. **Entre más alto sea el CI o RI, hay MENOS homoplasia implicada**.

- Para poder encontrar al árbol verdadero (el que exprese las relaciones de ancestro-descendiente) podemos usar el árbol que tenga el mayor promedio de CI (**"el árbol más parsimonioso"**)
