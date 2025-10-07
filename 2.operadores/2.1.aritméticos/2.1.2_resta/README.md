<h2>RESTA (-)</h2>
<br>
<br>
Solo sirve para restar números. Al contrario que la suma, no tiene sentido utilizar restas con strings. Es más, si se intenta utilizar la resta con strings, JavaScript intentará convertirlos a números y si no puede, el resultado será NaN (Not a Number).
<br>
<br>
Puedes probar a ver este resultado en la consola de Node.js escribiendo el siguiente código:
<br>
<br>
let a = "Hola";
let b = "Mundo";
let resultado = a - b; // Esto NO elimina "Mundo" de "Hola"
console.log(resultado); // NaN