# Teoria_JS
## Variables
let recipiente= null;
alert(recipiente) <br>

const numero;
alert(numero); <br> 
<i>Devuelve un error porque la constante tiene que inicializarse y declararse en la misma linea </i>

let numero, numero2, numero3;
let numero4 = 23, numero5 = 24;

let nombre = prompt("Decime tu nombre");
alert(`Hola ${nombre}`); <br>
<i>Backsticks = `` (sirve para concatenaciones con variables, se hace con Alt gr + tecla "}" dos veces )</i>


## ARREGLOS

let frutas = ["banana", "manzana", "naranja"]; <br>

<i>Acceder al índice: frutas[0] con 0 = posicion -> Devuelve "banana"</i>

let pc = {
    nombre : "GXPC",
    procesador: "Intel Core I7",
    ram: "16GB",
    espacio: "460GB"
}
<br>
<i>Se puede consultar el valor del elemento guardado en el arreglo con: pc[nombre] -> Devuelve "GXPC" </i>

## FUNCIONES
<p>Ejemplo de uso de funciones:</p>
<img src="https://github.com/Valentina1012/Teoria_JS/assets/84479987/92704561-f237-4739-a8de-c89f5bd772d9" width="300"><br>

### FUNCIONES DE UNA SOLA LINEA
<img src="https://github.com/Valentina1012/Teoria_JS/assets/84479987/bdbce261-063e-4575-9d10-9c5d43c89e29" width="250"><br>

### FUNCIONES FLECHA
const saludar = (nombre) => {
    let frase = `¡Hola ${nombre}! ¿Cómo estas?`;
    document.write(frase);
} <br>
* <i>La palabra reservada "function" se reemplaza por una flecha =></i>
* Entre paréntesis se colocan los parámetros de la función, en caso de no haber ninguno se deja el paréntesis vacío. También se puede no poner paréntesis si hay sólo un parámetro.
* Si hay sólo una linea a retornar se puede escribir de la siguiente forma: const saludar = nombre => document.write(frase);

### FUNCIONES ANONIMAS
<p>Las funciones anónimas son funciones que no tienen nombre. Se definen y se utilizan en el mismo lugar del código.</p>
<p>Son comúnmente utilizadas como argumentos para otras funciones o como funciones de devolución.</p>
<img src="https://github.com/Valentina1012/Teoria_JS/assets/84479987/9baf8a17-fce0-4169-a02f-64fd8022ce18" width="200">
