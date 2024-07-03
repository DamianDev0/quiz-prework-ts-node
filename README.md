JavaScript Básico:


Describe qué es una función en JavaScript y cómo se declara.

Es un prodecimiento Que realiza una tarea en particular, ya sea sumar o restar , o trabjos mas complejos.

hay funciones declaradas y expresadas, la declarada es cuando utilizamos la palabra reservada function y la expresada es cuando utilizamos la arrow function



Manipulación del DOM:

Explica cómo seleccionar un elemento del DOM y cambiar su contenido.

se puede selccionar de diferentes maneras en el DOM, ya sea por id, clase, tag name, o con Query selector. A este contenido selccionado se le puede agregar eventos, estilos u otro tipo de contenido Que nos ayude a cambiarlo

Programación Orientada a Objetos (OOP):

¿Qué es una clase en JavaScript y cómo se define una?




Eventos en JavaScript:

¿Cómo se agrega un evento de clic a un botón en JavaScript?
 primero se escoje a Que boton se le va a agregar el evento, ya sea por el id, o clase, luego hacemos nombreDelBoton.Addeventlistener('click', () => {
    alert('mensaje')
 })

Variables y Tipos de Datos:

Explica las diferencias entre var, let, y const en JavaScript.

var = es una variable donde su contenido o su espacio de memoria va a cambiar, lo Que la direfencia es el scope Que no tiene tanto alcance

let = al igual Que la varia "var" cambia su contenido

const = esta no cambia su contenido o espacio de memoria y como su nombre lo indica es constante


Control de Flujo:

¿Qué son las estructuras de control de flujo y cuáles son algunas de las más comunes en JavaScript?
Funciones de Flecha:

Describe qué es una función de flecha en JavaScript y proporciona un ejemplo de cómo se usa.

es una funcion anonima, o expresada.

ejemplo 

const suma = (a,b) => {
   return(a+b)
}
   



JSON:

¿Qué es JSON y cómo se utiliza en JavaScript?

el Json es muy parecido a los objetos de Javascript, son archivos de texto Que pueden ser interpretados por javascript

usualmente los utilizamos cuando Queremos traer datos con fetch, donde la promesa Que trae la convertimos a formato JSON para ser mas legible

Promesas:

Explica qué es una promesa en JavaScript y proporciona un ejemplo de su uso.




Depuración:

¿Cuáles son algunas de las herramientas o métodos que se pueden usar para depurar código JavaScript?

usualmente se usa console.log para depurar nuestro codigo

Preguntas de Selección Múltiple (20)
¿Cuál de las siguientes es la forma correcta de declarar una variable en JavaScript?
A) var myVariable;
B) variable myVariable;
C) let myVariable;
D) A y C son correctas. D

¿Qué método se utiliza para agregar un elemento al final de un array en JavaScript?
A) push() A
B) pop()
C) shift()
D) unshift()
¿Cuál de los siguientes operadores se utiliza para comparar tanto el valor como el tipo de dos variables en JavaScript?
A) ==
B) === B
C) !=
D) !==
¿Cuál es la salida del siguiente código?
console.log(typeof null);
A) null
B) undefined
C) object C
D) number
¿Cuál de los siguientes métodos se usa para recorrer todos los elementos de un array?
A) forEach()
B) map()
C) filter()
D) Todas las anteriores D
¿Qué se entiende por “hoisting” en JavaScript?
A) Declaraciones de variables y funciones se mueven al principio de su ámbito. A
B) Es un término para describir la eliminación de variables.
C) Es un método para agrupar varias funciones.
D) Ninguna de las anteriores.

¿Cuál es la diferencia entre null y undefined en JavaScript?
A) null significa que una variable ha sido declarada pero no definida, undefined significa que no se ha declarado.
B) null es un valor asignado intencionalmente, undefined significa que una variable no tiene valor.
C) undefined es un valor asignado intencionalmente, null significa que una variable no tiene valor. C
D) No hay diferencia.

¿Cuál es el propósito del método Array.prototype.map()?
A) Modificar el array original.
B) Crear un nuevo array con los resultados de aplicar una función a cada elemento del array original. B
C) Filtrar los elementos de un array.
D) Encontrar un elemento en un array.


¿Qué es el Event Loop en JavaScript?
A) Un ciclo que controla las llamadas recursivas.
B) Un proceso que permite a JavaScript realizar operaciones asincrónicas. B
C) Un método para iterar sobre arrays.
D) Ninguna de las anteriores.
¿Cuál es la salida del siguiente código?

console.log(0.1 + 0.2 === 0.3);
A) true A
B) false
C) undefined
D) NaN
¿Qué se entiende por strict mode en JavaScript?

A) Un modo que permite utilizar características experimentales.
B) Un modo que cambia la forma en que se ejecuta JavaScript, haciéndolo más seguro. B
C) Un método para validar datos.
D) Ninguna de las anteriores.

¿Cuál de las siguientes es una forma correcta de crear un objeto en JavaScript?

A) let obj = {};
B) let obj = Object.create();
C) let obj = new Object();
D) A y C son correctas. D
¿Qué es un callback en JavaScript?

A) Una función que se pasa como argumento a otra función. A
B) Un tipo de variable especial.
C) Un método para declarar funciones.
D) Ninguna de las anteriores.

¿Cuál es el propósito de async y await en JavaScript?

A) Ejecutar funciones síncronas.
B) Manejar operaciones asincrónicas de manera más simple y legible. B
C) Declarar variables globales.
D) Ninguna de las anteriores.

¿Cuál de las siguientes es una estructura de datos inmutable en JavaScript?

A) Arrays
B) Strings
C) Objetos C
D) Ninguna de las anteriores.
¿Cómo se puede convertir un objeto JSON en una cadena de texto en JavaScript?

A) JSON.parse()
B) JSON.stringify() B
C) toString()
D) parseInt()
¿Qué es un Promise en JavaScript?

A) Una función que se ejecuta inmediatamente.
B) Un objeto que representa la eventual finalización (o falla) de una operación asincrónica. B
C) Un método para declarar variables.
D) Ninguna de las anteriores.

¿Qué método se utiliza para agregar uno o más elementos al principio de un array y devolver la nueva longitud del array?

A) push()
B) pop()
C) shift() C
D) unshift()
¿Cuál es la diferencia entre localStorage y sessionStorage en JavaScript?

A) localStorage almacena datos solo durante la sesión del navegador, sessionStorage almacena datos de manera persistente.
B) sessionStorage almacena datos solo durante la sesión del navegador, localStorage almacena datos de manera persistente. B
C) No hay diferencia entre ellos.
D) Ambos almacenan datos solo durante la sesión del navegador.
¿Qué método se utiliza para detener la propagación de un evento en el DOM?

A) event.stopPropagation()
B) event.preventDefault() B
C) event.stop()
D) event.cancel()