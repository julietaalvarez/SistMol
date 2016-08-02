##UNIDAD 5. INFERENCIA FILOGENÉTICA CON DISTANCIA, MÁXIMA VEROSIMILITUD Y MÉTODOS BAYESIANOS##

- Estos modelos matemáticos tienen como punto central los **modelos de sustitución**; estos especifican la forma en que los estados de caracter tienen permitido cambiar, así como las tasas relativas de cambio evolutivo.
- Todos los modelos usan los **modelos de Markov**, es decir, decriben un proceso en el que la P de que ocurra un evento en un momento en el tiempo depende sólo del estado actual e independientemente de cómo llegó a ser ese estado.
 

 ``` 
Por ejemplo: el lanzamiento de una moneda. La probabilidad de que caiga águila siempre será 0.5, independientemente de los demás lanzamientos
```
- Trabajar con secuencias de DNA es fácil, pues sólo hay 4 estados de caracter. Los ***indels*** no están incluidos en los modelos de sustitución ya que agrega mucha complejidad a los análisis. Los ***gaps*** se toman como datos faltantes, es decir que podría ser cualquier nucleótido.
- Los modelos de sustitución pueden ser **reversibles**: la probabilidad de cambio es igual en cualquier dirección.
- Se debe asumir que todas las posiciones de DNA son ocupadas por alguna de las cuatros bases, en cualquier momento. Las mutaciones se pueden presentar de dos maneras: a)puede haber una sustitución del nucleótido por otro nucleótido igual o b) puede sustituirse por uno distinto.

![baraja.png](baraja.png)

 ``` 
Por ejemplo: Pensemos en una baraja donde tenemos 4 palos. Esos palos van cambiando de manera impredecible a otras cartas a una velocidad tan rápida que ninguno de nosotros lo puede ver. 
Esa velocidad de cambio es una tasa de cambio a la cual llamamos  **μ**.
Si asumimos que μ=0.6 por minuto, entonces en una hora tendremos 36 cambios (0.6x60 min). Aunque haya momentos en que vaya más rápido y otros más lento.
Si observamos durante mucho tiempo la misma posición es probable que veamos los cuatro palos.
```
![baraja2.png](baraja2.png)
