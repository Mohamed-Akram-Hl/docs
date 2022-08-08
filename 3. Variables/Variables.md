# Lesko Variables

### Variables

Variables are containers for storing data values.

### Creating Variables

Variables are declared using `var` or `let`.

* Example

```
var x = 5
var y = "bonjour"
ecrire(x)
ecrire(y)
```

Variables do not need to be declared with any particular type, and can even change type after they have been set.

* Example

```
var x = 4       // x is of type int
var x = "bonjour" // x is now of type str
ecrire(x)
```
> Comments can be used to explain Lesko code Just by typing `//` then write the comment you want.

> Comments can not be  executed when testing code.

### Casting

If you want to specify the data type of a variable, this can be done with casting.

```
var x = chaine(3)    // x will be "3"
var y = entier(3)    // y will be 3
var z = reel(3)  // z will be 3.0
```
