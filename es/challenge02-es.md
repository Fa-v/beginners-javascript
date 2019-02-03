# Reto 2: escritores famosos

¿Sabías que también se puede crear un array de objetos? Hemos creado uno para ti a continuación. Itera el array asignado a la varibale 'escritores' y para cada objeto escribe a la consola (`console.log()`) la siguiente frase:

```js
"Hola, mi nombre es {firstName} {lastName}. Tengo {age} años y trabajo como {occupation}."
```

Ignora las llaves. Solo sirven para marcar las palabras que hay que reemplazar con otros valores. La frase que logueas a la consola debe ser como ésta:

```js
"Hola, mi nombre es Virginia Woolf. Tengo 59 años, y trabajo como escritora."
```

Aquí tienes el array:

```js
var escritores = [
  {
    firstName: "Virginia",
    lastName: "Woolf",
    occupation: "escritora",
    age: 59,
    alive: false
  },
  {
    firstName: "Zadie",
    lastName: "Smith",
    occupation: "escritora",
    age: 41,
    alive: true
  },
  {
    firstName: "Jane",
    lastName: "Austen",
    occupation: "escritora",
    age: 41,
    alive: false
  },
  {
    firstName: "Bell",
    lastName: "Hooks",
    occupation: "escritora",
    age: 64,
    alive: true
  },
];
```

Si quieres otro reto, solo haz el `console.log()` de los escritores que siguen vivos.

### [Ir al Reto 3 >>>>](https://github.com/node-girls/beginners-javascript/blob/master/challenge03.md)
