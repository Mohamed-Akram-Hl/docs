# Built in Functions

### ecrire() Function

The `ecrire()` function prints the specified message to the screen, or other standard output device.

The message can be a string, or any other object, the object will be converted into a string before written to the screen.

* Example

Write a message onto the screen:

```
ecrire("Hello World")
```

### lire() Function

The `lire()` function allows user input.

* Example

Ask for the user's name and write it:

```
ecrire("entrer votre nom:")
var x = lire()
ecrire("bonjour, " + x)
```

### alea() Function

The `alea()` function returns an integer number between 0 and a given integer.

* Example

Return a number between 0 and 10 (10 is not included):

```
ecrire(alea(10))
```

### absolu() Function

The `absolu()` function returns the absolute value of the specified number.

* Example 

Return the absolute value of a number:

```
var x = absolu(-7.25)
```

### racine() Function

The `racine()` function returns the square root of a complex number.

* Example

Find the square a number:

```
ecrire(racine(4))
```

### arrondir() Function

The `arrondir()` function returns returns the nearest integer.

* Example

Round a number:

```
var x = arrondir(2.2424)
ecrire(x)
```
