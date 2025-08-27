# 🚧🚧🚧🚧REPOSITORIO EN CONSTRUCCIÓN🚧🚧🚧🚧
# CONCEPTOS BÁSICOS DE JAVASCRIPT APLICADOS EN UNA WEB - EJEMPLOS (para desarrolladores web frontends)

Si estás estudiando programación de páginas web y estás aprendiendo JavaScript (o intentando entenderlo y no lo consigues), quizás este repositorio te sirva para comprender su base de manera sencilla y global. En él podrás encontrar ejemplos explicativos muy concisos ¡échale un vistazo!  
<br>
Y si te ha servido y crees que puede ser útil para alguien que conozcas, compártelo 🙂  
<br>
¡Gracias!
<br>
<hr>
<br>
Javascript es un lenguaje para programar (entre otras muchas cosas) páginas web con las que puedas interactuar, es decir, páginas web dinámicas. Al principio es normal que sea muy lioso entenderlo. De hecho, hay cientos de cursos de Javascript por toda la web que te enseñan Javascript desde cero, cierto, pero no te explican qué hace let name = "Lucía" en una web, es decir, siempre te enseñan a abrir la consola en el VS Code y ¡hala! ¡a declarar variables y comprobar que el código funciona y se ve en el prompt! Practicar la lógica de JS desde una consola está bien para practicar y aprender los conceptos tal cual y memorizarlos pero, a la hora de la verdad... si tienes que programar un botón para que el usuario desde ahí accedar a una página de login, ¿qué utilizas de JavaScript?, ¿qué tienes que combinar de los conceptos de Javascript?
<br>
<br>
Vale, declaramos let name = "Lucía" pero, ¿qué?, ¿eso en una web dónde va?, ¿para qué sirve?, ¿dónde lo inserto?, ¿qué hace?
<br>
<br>
Siempre digo que <b>la teoría sin la práctica no sirve de nada</b>. Programando, practicando y viendo y entendiendo ejemplos (y volver a reproducirlos tú) es como creo que de verdad se aprende y se entiende, por eso he creado este mini repositorio con ejemplos visuales de la teoría básica de JavaScript aplicado en una web, para "abrir" la mente y pensar como un programador. Porque sí, porque un programador no piensa igual que el resto de usuarios de la informática y si quieres programar, tienes que pensar como un programador.
<br>
<br>
<h2>VARIABLES</h2>
<br>
<br>
Javascript intenta que el mundo real pueda ser representado y entendido por un ordenador de alguna forma y para que eso ocurra, JS tiene unos conceptos básicos que, combinados, pueden hacer que eso sea posible (hasta cierto punto). Javascript es el encargado que dejamos para que interactúe con el usuario que está al otro lado del cable. Imaginemos que no sólo hay un usuario, sino decenas, cientos, miles. No podemos atender a todos a la vez, y aunque sólo hubiera una persona, no podemos estar escribiendo código constantemente para atender las peticiones de esa persona en nuestra web, así que, para eso se programa, propiamente dicho, y para eso está JS, para que él haga de nosotros.
<br>
<br>
Para empezar vamos a hablar de lo básico que hay que saber en JS: las variables. Las variables son "las cosas" (ojo, NO objetos) que el ordenador tiene que saber que existen para que luego podamos hacer cosas con ellas. Por ejemplo, si yo quiero que el ordenador sepa que en una web tenemos que trabajar (entre otras cosas) con el nombre de un usuario, tengo que decirle <i>(declararle)</i> que ese nombre existe. En este caso, para decirle que en nuestra web, en el perfil, hay un nombre de usuario, tengo que usar texto o una concatenación de texto <i>(cadena de texto/string)</i>.
<br>
<br>
Imaginemos que ya tenemos listo el html y el css de nuestra web. Quiero que la web me muestre en una esquinita de la página el nombre de usuario de la persona que ya se haya logueado. Pues, entre todo ese html y css, tengo que insertar Javascript, que es el encargado de mostrar a ese usuario logueado. Como el nombre de usuario es texto (una cadena de texto, un string), se representaría como se muestra en el ejemplo 
