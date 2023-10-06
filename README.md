# Notas Javascript language:

## Arrays:
 ```
var letras = ['a', 'b', 'c', 'd', 'e'];

//La función forEach recibe una función anónima (arrow fuction) en la que se puede procesar cada uno de los elementos del Array.
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

*Las funciones push(), shift() y pop() son de tipo mutable, es decir, transforman el array

### Map

Recibe una funcion anónima (arrow function) en la que procesa cada uno de los elementos y los transforma de acuerdo a la lógica de la función, no muta el array inical

```
var people = ['Paco', 'Pepe', 'Rosa', 'Paula', 'Pedro'];

var peopleObjs = people.map((nombre)=> {
    return {
        nombre,
        startsP: nombre.startsWith('P') ? true : false
    }
});

```

