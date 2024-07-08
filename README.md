Arrays_JS
Un array es una zona de almacenamiento continuo, donde se puede introducir varios valores, cada uno de ellos ubicado por la posición que ocupa en el array, también son denominados o conocidos arreglos o vectores y cuando son de dos dimensiones son llamados matrices.

Los arrays nos brindan la capacidad de almacenar una coleccion de elementos y acceder a ellos de manera individual.

Cada elemento se identifica mediante su posición en el array de manera índice y estos indices son siempre secuenciales en Javascript son altamente flexibles en términos de los diferentes tipos de datos quepodemos almacenar en cada posición del array.

Crear un array

Declarando un array con elementos en linea.
let miArray = [1, 2, 3]
console.log("--------------------");
console.log("Arrays en Javascript");
console.log("--------------------");
console.log("1. Declarando un array con elementos en lines");
let miArray = [1, 2, 3];
console.log(miArray);

Explicar

Declarando un array con la sintaxis new array()
let miArray2 = new Array (1,2,3);
console.log(miArray);

Explicar

Declarando un array con un tamaño especifico utilizando la sintaxis new array y asignando valores despues:
let miArray3 = new Array (3);
miArray[0] = 1;
miArray[1] = 2;
miArray[2] = 3;
console.log(miArray3);

Explicar

Declarando un array con elementos de diferentes tipos de datos
let miArray3 = [1, "dos", true, {nombre: "Juan", edad:30}];
console.log(miArray4);
Explicar
Accediendo a la información de un array
Propiedad length
Devuelve la cantidad de elementos del array
Operador [pos]
Permite acceder para leer o modificar el elemento post del array
metodo at(pos)

Devuelve el elemento dela posicion pos. El parametro admite valores negativos, lo que significa que empieza a contar por el final del array.
const letters = ["A", "B", "C"];
console.log(letters.length):
console.log(letters(2));
console.log(letters(5));

Explicar

añadir o eliminar elementos
push(ele1, ele2): añade uno o varios elementos la final del array. Devuelve el tamaño del array.
let miArray = [1, 2, 3];
miArray.push(4);
console.log(miArray); 

Explicar

pop(): Devuelve el ultimo elemento del array y lo elimina
let miArray = [1, 2, 3];
miArray.pop();
console.log(miArray); 

Explicar


unshift(ele 1, ele2): añade uno o varios elementos al inicio devolviendo el tamaño del array despues de añadidos
let miArray = [1, 2, 3];
miArray.unshift(0);
console.log(miArray); 

Explicar

shift(): devuelve el elemento del array y lo elimina
let miArray = [1, 2, 3];
miArray.shift();
console.log(miArray); 

Explicar

concat(ele1, ele2): concatena dos arrays
let miArray = [1, 2, 3];
let miOtroArray = [4, 5];
let nuevoArray = miArray.concat(miOtroArray);
console.log(miArray);
console.log(miOtroArray); 
console.log(minuevoArray); 

Explicar

split(separador): a partir de una cadena, crear un array dividiendo dicha cadena en elementos delimitados por separador
let miString ="hola, ¿como estas?";
let miArray = miString.split(" ");
console.log(miArray);

Explicar

join(separador): a partir de un array, crea una cadena separando cada elemento con el separador.
let miArray =["hola,", "¿como", "estas?"];
let miString = miArray.join(" ");
console.log(miString);

Explicar

Busqueda de elementos en un array
includes(elemento): devuelve true o false si el elemento existe o no dentro del array
indexOf(elemento): devuelve la posición de la primera aparición del elemento. Si no existe, devuelve -1.
lastIndexOf(elemento): devuelve la posición de la ultima aparición del elemento. Si no existe, devuelve -1.
Modificar el array o crear fragmentos
slice(inicio, fin): devuelve un array con los elementos desde la posición inicio hasta la posición fin, ambos excluidos.

Ordenar elementos de un array
Reverse(): invierte el orden de los elementos de un array
sort(): ordena el array alfabeticamente
sort(criterio): ordena el array con el criterio determinado por la funcion criterio.
Borrar elementos de un array
Se puede borrar el contenido de un elemento de un array poniendo su valor a null o asignando una cadena vacia " ".
Para eliminar completamente un elemento del array se utiliza el operador delete.
recorrido de un array
recorrer con un bucle clasico pasando por todos los elementos.
var dias = ["lunes", "martes", "miercoles", "jueves", "viernes", "sabado", "domigo"];
for(i=0;i<dias.lengt;i++)
{
    console.log(dias[i]);
}

Explicar

Recorrer con un while, pasando por todos los elementos.
var dias = ["lunes", "martes", "miercoles", "jueves", "viernes", "sabado", "domigo"];
var i = 0;
whiel(i<dias.lengt)
{
    console.log(dias[i]);
    i++;
}
Explicar

Explicar
usando la setencia for,,,,in.
var dias = ["lunes", "martes", "miercoles", "jueves", "viernes", "sabado", "domigo"];
for(let index in dias)
{
    console.log(dias[index]);
}
Explicar

Explicar
Array multidimensionales
const matrix = [
    [1,2,3],
    [4,5,6],
    [7,8,9],
];
Explicar
Explicar
Recorrer una matriz utilizando bucles andiados
var dias = ["lunes", "martes", "miercoles", "jueves", "viernes", "sabado", "domigo"];
for(let i=0;i<matriz,length;i++)
{
    for(let j=0;matriz(i),length; j++)
    {
        console.log(matriz[i][j]);
    }
}
Explicar
Explicar
Ejercicios
Dada una lista de números separados por coma, calcular la suma, el mayor, el menor y la media de todos.

Introducir dos cadenas con elementos separados por coma, y con un boton concatenar las dos cadenas y mostrarlas en pantalla.

