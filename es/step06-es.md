# Sección 6: Los bucles "For"

Programar es genial ya que nos permite automatizar tareas repetitivas, como, por ejemplo, escribir lo mismo una y otra vez. En JAvaScript, un bucle "for" hace esto. Basicamente los bucles "for" nos permite llevar a cabo la misma operación un número dado de veces, cada vez con un valor diferente.

Un bucle "for" tiene la siguiente sintaxis:

```js
for (declaración 1; declaración 2; declaración 3) {
  // código a ejecutar
}
```

La declaración 1 define una variable para el bucle. Normalmente es un número que se incrementará cada vez que el bucle termine. Esto nos permite saber dónde estamos en cada iteración. Se puede asignar cualquier número a esta variable, pero normalmente se empieza por 0.

```js
var i = 0;
```

La declaración 2 define cuantas veces el bucle va a iterar. Normalmente se usan los operadores 'menor que' (`<`) o 'menor o equal a' (`<=`) para asignar el número iteraciones.

```js
i < 10
```

La declaración 3 define por cuánto hay que incrementar el valor de la variable `i` cada vez. Si solo lo quieres incrementar por uno, puedes poner `i++` (esta sintaxis es equal a `i = i + 1`), o puedes incrementarlo por otros números así:

```js
i += 2 // esto es equal a i = i + 2
```

Dentro de las llaves ponemos el código que quieres que se ejecute cada vez que el bucle itera. Puedes referir a la variable `i` en el código que se pone dentro de las llaves.

### Pruébalo

Aquí tienes un ejemplo de un bucle "for" que imprime los números del 1 al 10:

```js
for (var i = 1; i <= 10; i++) {
  console.log(i);
}
```

Fíajte que se asigna el número `1` a la variable `i` ya que queremos empezar a contar con 1. El largo del bucle se setea en menor que o equal a 10 debido que queremos que el bucle pare en ese número. También estamos incrementando el valor de `i` por uno cada vez.

### Mini reto

Escribe un bucle "for" que itera de 0 a 100, imprimiendo solo los números pares (incluyendo 0). Debe devolver `0, 2, 4, 6, 8, 10...`.

### [Ir a la Sección 7 >>>>](https://github.com/node-girls/beginners-javascript/blob/master/step07.md)
