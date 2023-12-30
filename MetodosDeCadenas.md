### METODOS DE CADENAS
* CONCAT(): Junta dos o más cadenas y retorna una nueva. Ej: let cadena = "cadena de prueba";
resultado = cadena.concat("hola"); <br> <i>// resultado = cadena de prueba hola </i>

#### METODOS DE BUSQUEDA
* STARTSWITH(): Si una cadena comienza con los caracteres de otra cadena, devulelve true, sino devuelve false. Ej: let cadena = "cadena de prueba";
cadena2 = "cadena"; resultado = cadena.startsWith(cadena2); <br> <i>// resultado = true </i>
* ENDSWITH(): Es parecido a startsWith() sólo que devuelve true en caso de que la cadena termine con los mismo caracteres que otra cadena, en caso contrario devuelve false.
* INCLUDES: Si una cadena puede encontrarse dentro de otra cadena, devuelve true, sino devuelve false. Ej: let cadena = "cadena de prueba";
cadena2 = "prueba"; resultado = cadena.includes(cadena2); <br> <i>// resultado = true </i>
* INDEXOF(): Devuelve el índice del primer caracter de la cadena, sino existe, devuelve -1.
Ej: let cadena = "cadena de prueba";
resultado = cadena.indexOf("prueba"); <br> <i>// resultado = 10 </i>
* LASTINDEXOF(): Devuelve el último índice del primer caracter de la cadena, sino existe, devuelve -1. Agarra la última conincidencia de la cadena. 
Ej: let cadena = "cadena de prueba prueba prueba";
resultado = cadena.lastIndexOf("prueba"); <br> <i>// resultado = 24 </i>

#### METODOS DE RELLENO
* PADSTART(): Rellena cadena al principio con los caracteres deseados. Sintaxis: padStart(cantidadCaracteres, "letra o palabra para rellenar"). También está padEnd() que rellena al final de la cadena.
Ej: let cadena = "abc";
resultado = cadena.padStart(6, "a"); <br> <i>// resultado = aaaabc </i>
* REPEAT(): Devuelve la misma cadena pero repetida la cantidad de veces especificada. Ej: let cadena = "123 ";
resultado = cadena.repeat(2); <br> <i>// resultado = 123 123 </i>

#### METODOS DE TRANSFORMACIÓN DE CADENAS
* SPLIT(): Divide la cadena como le especifiquemos y devuelve un array por cada separación.
  <i> Ej: "Hola como estas" -> split("como") -> Hola , estas </i> 
* SUBSTRING(): Devuelve una parte del string.
  Sintaxis: substring(posDesde, posHasta). <i> Ej: "ABCDEFG" -> substring(0, 2) -> AB </i>
* TOLOWERCASE(): Convierte una cadena en minúscula.
* TOUPPERCASE(): Convierte una cadena en mayúscula.
* TOSTRING(): Devuelve una cadena que representa al objeto especificado.
* TRIM(): Elimina los espacios en blanco al principio y al final de una cadena.
* TRIMEND(): Elimina los espacios en blanco al final de una cadena.
* TRIMSTART(): Elimina los espacios en blanco al principio de una cadena.
* VALUEOF(): Retorna el valor primitivo de un objeto especificado.




