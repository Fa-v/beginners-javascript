# Sección 2: Tipos de Datos

Si habías jugado con el `console.log()` en la última sección, habrás visto que las palabras (texto) siempre tienen que aparecer entre comillas, sino el código rompe, mientras que los números pueden ir con o sin las comillas. ¿Por qué es eso? Esto se debe a que JavaScript tiene varios tipos de datos. Vamos a aprender los tres principales tipo de datos en esta sección - (más adelante veremos otros tipos de datos, como los objetos y arrays).

## Strings (Cadenas)

Una cadena es solo un trozo de texto y puede ser de un solo carácter hasta párrafos. Cabe destacar que una cadena siempre tiene que estar envuelto en comillas (sencillas o dobles).

```js
'node girls'
```

## Integers (Números)

En JavaScript los números se llaman "integers" (enteros). No hace falta ponerlos entre comillas y se pueden escribir tal cual.

```js
100
```

## Booleans (Lógicos)

Hay un tipo de dato especial en javaScript conocido como un valor "boolean" que indica si una declaración es verdadero o falso. Puede tener un valor de `true` o `false`, y siempre se escribe sin comillas.

```js
true
```

### Pruébalo

Ahora que has visto cómo son, vamos a asegurarnos que son realmente lo que creemos que son. JavaScript tiene el operador `typeof` que nos permite comprbar el tipo de un valor en concreto.

Escribe el siguiente código en tu Repl y haz click en "run":

```js
console.log(typeof 'Hola mundo!');
```

Debes ver `string` impreso en la consola. Eso es por que 'Hola mundo!' es del tipo 'cadena' ('string').

### Mini reto

Ahora, intenta eso tres veces, una para cada tipo de datos. Escribe a la consola el `typeof` tres valores diferentes: `"node girls"`, `1234` y `false`. La salida debe ser diferente para cada uno.

### [Ir a la sección 3 >>>>](https://github.com/node-girls/beginners-javascript/blob/master/step03.md)
