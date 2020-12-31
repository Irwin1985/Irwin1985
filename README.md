### Hey 👋, I'm Irwin

[![Github](https://img.shields.io/github/followers/Irwin1985?label=Follow&style=social)](https://github.com/Irwin1985)

I'm a ***Compiler and Interpreter*** lover ❤ so I decided study this huge topic inspired by my goal of creating my first programming language called `Sumerian` or `Sumerio` in Spanish *(yep, I'm latin).* So far I can tell you no much about `SumerioLang` but it's a *Dynamic typed language* which syntax will be inspired on **Ruby, Python, Visual Foxpro, C and Lisp.**

<hr>

🤔 Actually I'm currently working in `Sumerio` syntax and I think this first approach it ok for start:

```xBase
// variable declaration
var a
a = 10
var b = 5 // declaration and assignment (binding).
?"result:", a + b

// control flow
// if statement
if a + b < 10
  ?"is less"
elif a + b > 10
  ?"a is greater"
end

// functions: in sumerio functions are first class citizen (inspired from LISP)

fun parent()
  var x = "hello"
  func child()
    ?x
  end
  return child
end
var f = parent();
f()

// for statement (inspired from Visual FoxPro)
for i=1 to 3
  ?i // prints 1,2,3
end
// using step
for i=1 to 10 step 3
  ?i // prints 1, 3, 5, 7
end

// down to...
for i=4 to 1 step -1
  ?i // prints 4,3,2,1
end

// while statement
var i = 1
while i < 10
  ?i
  i += 1
end
```
