# Notas Javascript language:

## Arrays:
 ```
var letras = ['a', 'b', 'c', 'd', 'e'];

//La función forEach recibe una función anónima en la que se puede procesar cada uno de los elementos del Array.
letras.forEach((e) => {
     console.log(e);
});

//La función push() añade un elemento al final
letras.push('f');

//La función shift() extrae el primer elemento del array 
let x = letras.shift(); //x = 'a'

//la función pop() extrae el último elemento del array
let y= letras.pop(); //y = 'f'

 ```
