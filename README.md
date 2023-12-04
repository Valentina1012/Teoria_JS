# Teoria_JS

let recipiente= null;
alert(recipiente) <br>

const numero;
alert(numero); <br> 
<i>Devuelve un error porque la constante tiene que inicializarse y declararse en la misma linea </i>

let numero, numero2, numero3;
let numero4 = 23, numero5 = 24;

let nombre = prompt("Decime tu nombre");
alert(`Hola ${nombre}`); <br>
<i>Backsticks = `` (sirve para concatenaciones, se hace con Alt gr + tecla "}" dos veces )</i>


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

## BUCLE DO WHILE
let nro = 0;

do {
    document.write(numero + "<br>");
    numero ++;
}

while (numero > 6); <br>
<i>Ejecuta el código al menos una vez y luego pregunta por la condición del bucle</i>


## CONTINUE EN UN BUCLE
<i>Sirve para pasar a la siguiente iteración del bucle sin ejecutar lo que hay después del continue</i>

for (let i = 1; i <= 5; i++) {
    if (i == 4) {
        continue;
    }
    document.write(i);
}
<i>Estas lineas de código impremen 1, 2, 3, 5 (se saltea la impresión del número 4)</i>

document.write("<br>");

let animales = ["gato", "perro", "jirafa"];

## FOR IN
<i> Recorre por índice de un arreglo y muestra su indice además de propiedades del objeto </i>

for (animal in animales) { <br>
  document.write(animal + "<br>"); <br>
}

## FOR OF
<i>Recorre por el elemento de un arreglo</i>

for (animal of animales) { <br>
  document.write(animal + "<br>"); <br>
}
