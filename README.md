# practica-visualizacion

Los ejercicios se han realizado según los pedido en la práctica, pero en algunos casos, considero que es necesario poner una pequeña explicación, o destacar alguna cosa que se ha realizado de forma distinta o que ha presentado una dificultad un poco mayor.

## Ejercicio 1

El ejercicio esta realizado tal y cómo se pide en el enunciado. Se ha decidido usar un gráfico de anillo, ya que el tamaño es más fácil de observar que el angulo. Como algo destacable es que la etíqueta del total de compras del gráfico de anillo cambia entre nacional y el nombre del estado cuando no hay ningún estado seleccionado. 

Los colores de fondo se han elegido para dar un aspecto más moderno.

## Ejercicio 2

De nuevo como el enunciado pedia. La única Se muestran los valores de ventas filtrados por  ganancias maxímas y perdidas máximas para cada uno de las regiones. La elección de colores (verde/rojo) es para indicar de un golpe de vista que son ganancias y que son perdidas, ya que esos colores son standard para la representacion de ganancias y perdidas.

## Ejercicio 3

La parte complicada de este ejercicio ha sido cambiar la escala cuando se elige una vista distinta. Para ello se ha empleado un 'hack' ya que la leyenda de color de los valores no seleccionados se esconde detras del resumen de ventas/total compradores/total registros/compras por región, y la leyenda usada se muestra. Si no se hiciese esto, la leyenda estaría con valores ```Null``` y no quedaría agradable visualmente.

El resto del ejercicio ha sido realizado según el enunciado.

## Ejercicio 4
La idea de este dashboard es mostrar una "Máquina del Tiempo". Es decir, mostrar que información vería un analista en una fecha determinada y permitir entender su proceso de decisión vista la información que tenía en ese momento.
Al mover el slider de fecha elegida, nos filtra toda la información que había en ese momento, pudiendo ver la cotización, el volumen de negociación y el valor de mercado. Así como el reparto del volumen del mercado para las distintas criptos, y la evolución del mercado vs número de criptomonedas hasta esa fecha.

Además, al pasar sobre cada uno de las distintas criptomonedas, podemos ver un tooltip con los parametros para la última semana, y, si pinchamos en una en concreto, veremos su cotización historica.

He convertido el csv de entrada en un fichero excel, ya que al realizar la información, y debido a la configuración regional de mi máquina, Tableau no era capaz de importar los valores en notacion cientifica de forma correcta, y convertia esos valores en ```Null```. Al pasar por excel, que te da más opciones de importación evito ese error.
