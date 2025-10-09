<h2>MÓDULO Y ASIGNACIÓN (%=)</h2>
<br>
<br>
Este operador calcula el resto de dividir el valor actual de una variable entre otro número y guarda ese resultado en la misma variable.
<br>
<br>
Vamos a ver su sintaxis. Escribe y ejecuta las siguientes líneas de código en Node.js:
<br>
<br>
let x = 17;
x /= 5;
console.log(x) // Saldrá 2
<br>
<br>
Después de esta operación, el nuevo valor de la variable "x" será 2.
<br>
<br>
¿Para qué sirve esto? Pobtener el resto de una división de forma rápida y es últil en cálculos matemáticos, ciclos, lógica para alternar estados o cuando necesitamos saber si un número es par o impar, etc. demás, es una forma abreviada de escribir:
<br>
<br>
let x = 17;
x = x % 2;
<br>
<br>