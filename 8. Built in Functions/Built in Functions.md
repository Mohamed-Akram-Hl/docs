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

The lire() function allows user input.

* Example

Ask for the user's name and write it:

```
ecrire("entrer votre nom:")
var x = lire()
ecrire("bonjour, " + x)
```

### 
