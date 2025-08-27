<h2>DECLARAR VARIABLES - LET Y CONST</h2>
<br>
<br>
Javascript intenta que el mundo real pueda ser representado y entendido por un ordenador de alguna forma y para que eso ocurra, JS tiene unos conceptos básicos que, combinados, pueden hacer que eso sea posible (hasta cierto punto). Para que la máquina pueda entender los conceptos y cosas de nuestro mundo (tipos de datos), hay que decirles que existen, es decir, hay que declarárselas y para ello, antes de cada tipo de dato hay que utilizar let o const (variables).
<br>
<br>
Let y const son las variables y éstas son dos introductoras que declaran qué tipos de datos queremos que la máquina entienda qué es y qué va a pasar con ellos. Por ejemplo, si yo quiero que la máquina sepa cómo es mi nombre, le podré decir:
<br>
let name = "Lucía"
<br>
ó
<br>
const name = "Lucía"
<br>
<br>
¿Cómo saber cuándo tengo que poner let o const? Si el dato que le vamos a dar a la máquina es un dato que puede cambiar, pondremos let antes del tipo de dato, sin embargo si le queremos decir a la máquina que ese dato no puede cambiar, pondremos const.
<br>
<br>
En la carpeta "ejemploVariableLet" podemos ver en el index un contador web. En la etiqueta "script" se ha insertado el código JS donde se declara una variable let contador = 0 porque los números del contador van a cambiar en función de si pulsamos el botón de sumar o restar
<br>
<br>
En la carpeta "ejemploVariableConst" podemos ver en el index un elemento estático, en este caso el nombre de un usuario en una página web donde no queremos que se cambie nunca jamás el nombre de esa persona.