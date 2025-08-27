Javascript es un lenguaje para programar (entre otras muchas cosas) páginas web con las que puedas interactuar, es decir, páginas web dinámicas. Al principio es normal que sea muy lioso entenderlo. De hecho, hay cientos de cursos de Javascript por toda la web que te enseñan Javascript desde cero, cierto, pero no te explican qué hace let name = "Lucía" en una web, es decir, siempre te enseñan a abrir la consola en VSCode y ¡hala! ¡a declarar variables y comprobar que el código funciona y se ve en el prompt! Practicar la lógica de JS desde una consola está bien para practicar y aprender los conceptos tal cual y memorizarlos pero, a la hora de la verdad... si tienes que programar un botón para que el usuario desde ahí acceda a una página de login, ¿qué utilizas de JavaScript?, ¿qué tienes que combinar de los conceptos de Javascript?
<br>
<br>
Vale, declaramos let name = "Lucía" en un documento .js en VSCode o en una pestaña en blanco en Chrom pero, ¿qué?, ¿eso en una web dónde va?, ¿para qué sirve?, ¿dónde lo inserto?, ¿qué hace?
<br>
<br>
Siempre digo que <b>la teoría sin la práctica no sirve de nada</b>. Programando, practicando y viendo y entendiendo ejemplos (y volver a reproducirlos tú) es como creo que de verdad se aprende y se entiende, por eso he creado este mini repositorio con ejemplos visuales de la teoría básica de JavaScript aplicado en una web, para "abrir" la mente y pensar como un programador. Porque sí, porque un programador no piensa igual que el resto de usuarios de la informática y si quieres programar, tienes que pensar como un programador.
<br>
<br>
<h2>VARIABLES</h2>
<br>
<br>
Javascript intenta que el mundo real pueda ser representado y entendido por un ordenador de alguna forma y para que eso ocurra, JS tiene unos conceptos básicos que, combinados, pueden hacer que eso sea posible (hasta cierto punto). Javascript es el encargado que dejamos para que interactúe con el usuario que está al otro lado de la pantalla de nuestra web. Imaginemos que no sólo hay un usuario, sino decenas, cientos, miles. No podemos atender a todos a la vez, y aunque sólo hubiera una persona, no podemos estar escribiendo código constantemente para atender las peticiones de esa persona en nuestra web, así que, para eso se programa, propiamente dicho, y para eso está JS, para que él haga de nosotros también.
<br>
<br>
Para empezar, vamos a hablar de lo básico que hay que saber en JS: las variables. Las variables son "las cosas" (ojo, NO objetos) que el ordenador tiene que saber que existen para que luego podamos hacer cosas con ellas. Por ejemplo, si yo quiero que el ordenador sepa que en una web tenemos que hacer que se visualice el nombre de usuario cuando una persona hace clic en el botón de login, tengo que decirle <i>(declararle)</i> que ese concepto (el nombre de usuario) existe. En este caso, para decirle que en nuestra web, en el perfil, hay un nombre de usuario, tengo que usar texto o una concatenación de texto <i>(cadena de texto/string)</i>.
<br>
<br>
Imaginemos que ya tenemos listo el html y el css de nuestra web. Quiero que la web me muestre en una esquinita de la página el nombre de usuario de la persona que ya se haya logueado. Pues, entre todo ese html y css, tengo que insertar Javascript, que es el encargado de mostrar a ese usuario logueado. Como el nombre de usuario es texto (una cadena de texto, un string), se representaría como se muestra en el ejemplo 
