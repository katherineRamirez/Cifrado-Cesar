# Cifrado-Cesar

Pedir al usuario ingresar una frase y a esa misma frase aplicar el algoritmo de Cifrado César, la cual devuelve el mismo mensaje encriptado con un desplazamiento de 33 espacios hacia la derecha.

Reto: 

Usar el algoritmo de Cifrado César:
-fórmula:
           (x - 65 + n) % 26 + 65
 
 x = número de la letra (ASCII)
 n = valor fijo
 % 26 = residuo de 26
 
 Requerimientos Técnicos:

 El proyecto fue realizado de la siguiente manera:
 
 - Crear una función llamada cipher. function cipher(){}
 - Crear una variable llamada frase que le pida al usuario por medio de un prompt ingresar una frase "Ingrese una frase con        mayúscula.
 - Crear una variable llamada respuesta que almacene la frase ingresada por el usuario.
 - Crear un for que recorra la frase en la variable respuesta.
 - Crear una variable llamada dígitos no válidos la cual tendrá los números del 0 al 9.
 - Luego hacer condicionales:
     - Usar if (si) la frase ingresada contiene algún número retornar una frase que le pida al usuario "Ingrese una frase              correcta".
     - De lo contrario devuelva la frase.
 - Crear otro función llamada decipher. function decipher(){}
 - Aplicar el algoritmo de Cifrado César a la frase ingresada. fórmula: (x - n) % 26
 - Retornar la nueva frase decifrada.
 
