<h2>DECLARAR VARIABLES - LET Y CONST</h2>
<br>
<br>
Javascript es un lenguaje intermediario entre el lenguaje binario de una máquina y nuestro lenguaje humano, compuesto de una serie de "conceptos" o "piezas" que, combinadas, pueden hacer que esa interactividad entre un ser humano y una máquina sea posible. Javascript se inventó para que en la web no sólo se imprimiera texto en pantalla, sino para que además se pudiera interactuar y trabajar con ellas de otra manera más dinámica. Para ello, la máquina tenía que "saber" y "entender" nuestro mundo real y Javascript hizo que el mundo real pudiera ser representado de manera digital (hasta cierto punto). 
<br>
<br>
Para que la máquina pueda entender los conceptos y cosas de nuestro mundo, primero hay que decirles que existen, (en lenguaje de programación: hay que declarárselas) y para ello, antes de cada dato que le queremos decir que existe, hay que utilizar let o const.
<br>
<br>
Let y const son dos introductores que declaran qué tipos de datos queremos que la máquina entienda qué son y qué va a pasar con ellos. Por ejemplo, si yo quiero que la máquina sepa cómo es mi nombre, le podré decir:
<br>
<br>
let name = "Lucía"
<br>
ó
<br>
const name = "Lucía"
<br>
<br>
¿Cómo saber cuándo tengo que poner let o const? Si el dato que le vamos a dar a la máquina es un dato que puede cambiar, pondremos let antes del tipo de dato, sin embargo, si le queremos decir a la máquina que ese dato no puede cambiar, pondremos const.
<br>
<br>
En el ejemplo indexLet.html (más arriba en esta página) podemos ver un contador web. En la etiqueta "script" se ha insertado el código JS donde se declara una variable let contador = 0 porque los números del contador van a cambiar en función de si pulsamos el botón de sumar o restar
<br>
<br>
En ejemplo indexConst.html (más arriba en esta página) podemos ver un elemento estático, en este caso el nombre de un usuario en una página web donde no queremos que se cambie nunca jamás el nombre de esa persona.