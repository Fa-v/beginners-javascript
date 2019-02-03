# Sección 9: Objectos

Ahora verémos el último tipo de datos: los objetos. Como los array, los objetos pueeden almacenar varios trozos de información. La diferencia es que los objetos almacenan esta información en propiedades ("claves"). Por ejemplo, tal vez quieres guardar el nombre, modelo y color de un coche, o el nombre, hora y lugar de una pélicula que se va a estrenar.

La sintaxis de un objeto es así:

```js
{
  property1: "value1",
  property2: "value2",
  property3: "value3"
}
```

Los nombres a mano izquierda ("property1") son las propiedades o "claves" ("keys"). Puedes nombrarlas cualquier cosa y asignarlas cualquier valor: cadenas, lógicos, números o funciones.

## Pruébalo

Vamos a definir un objeto que representa una persona:

```js
var persona = {
  firstName: "Virginia",
  lastName: "Woolf",
  occupation: "escritora",
  age: 59,
  alive: false
};
```

Podemos hacer un `console.log()` del objeto entero, pero tmabién podemos sacar solo una de sus propiedades. Ejecuta este código:

```js
console.log(persona.firstName);
```

## Mini reto

Usando un objeto que representa una persona, hacer un `console.log()` de una frase que presenta la persona. Tienes que imprimir lo aiguiente:

```js
"Hola, mi nombre es {firstName} {lastName}. Tengo {age} años, y trabajo como {occupation}."
```

Una pista: puedes construir una cadena añadiendo varias cadenas y valores con el operador de <strong>concatenación</strong>: `+`. Esto incluye las claves y valores de objetos. Por ejemplo:

```js
var animal = {
    species: "cat", 
    name: "Tabitha"
};
console.log("Mi " + animal.species + "se llama " + animal.name + ".");
```

No te olvides de incluir espacios dónde hagan falta.

### [Ir a la Sección 1 >>>>](https://github.com/node-girls/beginners-javascript/blob/master/challenge01.md)
