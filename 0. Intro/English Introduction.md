# Welcome to Lesko


<h1 align="center">
  <img src="https://github.com/Mohamed-Akram-Hl/docs/blob/main/assets/Logo.png?raw=true" width="200px"/>
</h1>

### What's Lesko?


Lesko is a compiled programming language designed to be as near as possible to the algorithmic language.

A compiled programming language is a type of programming language where the source code is translated into machine code (binary code) before being executed by the computer. In other words, the code is compiled into a form that the computer can understand and execute directly.


For example, when you write code in C, C++ or Fortran, it needs to be compiled into machine code before it can be executed. The compiler reads the code, checks for errors and translates it into a form that the computer can understand. This compiled code is then saved as a separate executable file, which can be run independently.

But in this case, I used C# to build the compiler so the source code will be translated to native C# code if there is no error then it will be excuted.

### The Purpose of Lesko

Since we study algorthims at school and there is no way that the computer can understand it. I made this language to be as near as possible to the algorithmic language with a visual studio code extension, so, we can write it directly into visual studio code and excute the code there without the need to rewrite the algorthim in python.


We can solve some basic problems like simply calculating the sum of two given numbers:


```
ecrire("entrer a: ")
var a = entier(lire())
ecrire("entrer b: ")
var b = entier(lire())
var c = a + b
ecrire("a + b = " + chaine(c))
```

* The result will be:

```
entrer a: 
10
entrer b:
20
a + b = 30
```

> Image from the code editor

![sum](https://raw.githubusercontent.com/Mohamed-Akram-Hl/docs/main/assets/Screenshot%202023-02-10%20195930.png)

Or we can go even further to calculate the solutions of a quadratic equation:

```
ecrire("spécifier a:")
var a = reel(lire())
ecrire("spécifier b:")
var b = reel(lire())
ecrire("spécifier c:")
var c = reel(lire())
var delta = b ** 2 - 4 * a * c
si a == 0 {
    ecrire("Cette equation n'est pas de second dégré.")
}
sinon si delta > 0 {
    var x = (-b - racine(delta)) / (2 * a)
    var y = (-b + racine(delta)) / (2 * a)
    ecrire("Les solutions sont:")
    ecrire(x)
    ecrire(y)
}
sinon si delta == 0 {
    var x = -b / (2 * a)
    ecrire("La solution est:")
    ecrire(x)
}
sinon {
    ecrire("L'equation n'a pas de solutions.")
}
```

* The result will be:

```
spécifier a:
1
spécifier b:
-3
spécifier c:
2
Les solutions sont:
1
2
```

> Image from the code editor


![quad](https://raw.githubusercontent.com/Mohamed-Akram-Hl/docs/main/assets/Screenshot%202023-02-10%20200951.png)
