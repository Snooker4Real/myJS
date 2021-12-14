# myJS

## Spread syntax operator

Le spread operateur (...) prend un tableau ou un objet (ou autre iterable) et étend ses items dans leur valeur individuel

```
let sandwiches = ['tuna', 'turkey', 'pb&j'];

// logs ["tuna", "turkey", "pb&j"]
console.log(sandwiches);

// logs tuna turkey pb&j
console.log(...sandwiches);
```

Cet opérateur ne peut être utiilisée dans une fonctions, un tableau et un objet. Tu ne peut pas l'utiliser tout seul.

Un exemple qui renverrait une erreur ❌
```
// Uncaught SyntaxError: Unexpected token '...'
...sandwiches;
```
