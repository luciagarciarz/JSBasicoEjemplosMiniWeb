<h2>SYMBOL</h2>
<br>
<br>
El symbol es un dato único. Puede ser textual o numérico pero el symbol es un dato que no es ni string ni number, es symbol. Con el ejemplo de la carpeta 6_ejemploSymbol se puede ver muy bien.
<br>
<br>
En el código que empieza desde la columna 36, el código de JS, se declaran 3 variables symbol (filas 38, 39 y 40). Todas empiezan por const (esto es importante, es muy raro declarar una variable symbol con let ya que los symbol son inmodificables, lo normal es declarar los symbol con const) y se le asigna un nombre (en este caso ID, ROL y TOKEN) y en las tres variables, se declaran symbol que, aunque sea la misma palabra, la variable va a ser distinta y única siempre porque previamente hemos declarado qué es ese symbol (un ID, un ROL y un TOKEN) pero la palabra symbol siempre es la misma. No es const symbol = id, const symbol = rol o const symbol = token. 
