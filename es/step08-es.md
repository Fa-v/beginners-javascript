# Sección 8: Arrays

Antes mencionamos que hay otros tipos de datos aparte de cadenas, números y lógicos. Un array es uno de ellos. Los array nos permite almacenar varios valores junto de una forma sencilla.

Se ponen los valores entre corchetes, separados por comas. Aquí tienens un ejemplo de la sintaxis:

```js
[value1, value2, value3]
```

Se puede usar un array para almacenar cualquier tipo de dato: cadenas, números, lógicos, incluso otroso array o objetos (veré,mos esto en la siguiente sección).

## Pruébalo

Se define un array como una variable de esta manera:

```js
var animals = ["tiger", "puppy", "snake", "llama"];
```

¡Mola! Ahora tienes todos los animales juntos en un grupo y no has tenido que crear una variable para cada uno por separado. Puedes ver cuantos animales hay usando el método `.length`:

```js
console.log(animals.length);
```

Si quieres referir a un miembro específico del array, puedes usar su "número de índice" así:

```js
console.log(animals[1]);
```

Adivina cúal de los animales se imprime a la consola.

Spoiler: va a imprimir "puppy". Eso parece raro hasta que sepas que JavaScript es un lenguaje del tipo "0-índice". Esto significa simplementge que JavaScript empìeza a contar con 0. Así que `animals[0]` imprime "tiger". No hacemos las reglas...

## Mini reto

¿Cómo harías un `console.log()` del nombre de cada anaimal en el array?

Si estás pensando en usar un bucle "for, has acertado. Esta es la oportunidad perfecta para usar nuestros nuevos conocimientos para resolver un problema.

Si te atascas, usa Google para encontrar la respuesta. Saber hacer búsquedas en Google es una parte fundamental de la vida de un@ desarrolladora.

### [Ir a la Sección 9 >>>>](https://github.com/node-girls/beginners-javascript/blob/master/step09.md)
