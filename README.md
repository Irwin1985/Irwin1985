<h1>    
    Hey 👋, I'm Irwin
    Welcome to my humble abode!
</h1>

Before anything, take a look at my Github Analytics...

### ⌛️ &nbsp; How I did it at GitHub?
<p align="center">
    <a href="https://github.com/irwin1985">
        <img height="180em" src="https://github-readme-stats-eight-theta.vercel.app/api?username=irwin1985&show_icons=true&theme=algolia&include_all_commits=true&count_private=true" />
        <img height="180em" src="https://github-readme-stats-eight-theta.vercel.app/api/top-langs/?username=irwin1985&layout=compact&langs_count=8&theme=algolia" />
    </a>
</p>

[![Github](https://img.shields.io/github/followers/Irwin1985?label=Follow&style=social)](https://github.com/Irwin1985)

I'm a ***Compiler and Interpreter*** lover ❤ so I decided study this huge topic inspired by my goal of creating my first programming language called `Sumerian` or `Sumerio` in Spanish *(yep, I'm latin).* So far I can tell you no much about `SumerioLang` but it's a *Dynamic typed language* which syntax will be inspired on **Ruby, Python, Visual Foxpro, C and Lisp.**

Take a look to its syntax below and let me know if you have some suggestions...

<hr>

🤔 Actually I'm currently working in `Sumerio` syntax and I think this first approach it ok for start:

```xBase
// C-Style comments
/**
* And multi-line comment are also important.
*/

// let's start with variable declaration
var a;

// any statement need a semicolon `;` termination (Sorry for VFP developers).

a = 10; // isolated assignment statement
var b = 5; // declaration and assignment (binding).
?"result:", a + b; // do you like the VFP `?` printing operator? or `print` instead?

// control flow
// if statement
if a + b < 10:
  ?"is less";
elif a + b > 10:
  ?"a is greater";
end

// If your conditional's block is composed by a single statement then 
// check this out:

if a > b -> return "greater";

// Need an else alternative? No problem...
if a > b -> return "greater" -> return "less";

// What about ternary operator like this one:

result = (a > b) <- "greater" -> "less"; // do you like it? is it make any sense?

// Check this branching statement
case a:
  -> 1 : "a is 1";
  -> 2 : "a is 2";
  -> 3 : "a is 3";
  other: "dont know what a is it";
end
// do you like it? or do you miss the `when` keyword?

// functions: in sumerio functions are first class citizen (inspired from LISP)

fun parent():
  var x = "hello";
  func child():
    ?x;
  end
  return child;
end
var f = parent();
f();

// for statement (inspired from Visual FoxPro)
for i=1 to 3:
  ?i; // prints 1,2,3
end
// using step
for i=1 to 10 step 3:
  ?i; // prints 1, 3, 5, 7
end

// down to...
for i=4 to 1 step -1:
  ?i; // prints 4,3,2,1
end

// while statement
var i = 1;
while i < 10:
  ?i;
  i += 1;
end

// Let's see some classes declarations, shall we?
class Animal:
  init(name): // init method is special. Is like a constructor.
    this.name = name
  end
  // class method's don't need the 'fun' keyword.
  walk():
    ?"Walking..."
  end

// Inheritance
class Dog as Animal:
  init(name):
    super(name)
    
  bark():
   ?"Boof..."
  end

// Instances
doggy = Dog("Spike")
for i=1 to 3:
   doggy.bark(); // shut up dog...
end
```
<hr>

**Why the semicolon for terminating the expressions?**

Well, parsing expressions requires any terminator character and the semicolon `;` is the most widely used termination character used in programming, but let me know if you are thinking in another character as good as `;`.

**Why the end closing keyword instead of well known block delimiters `{ block }`**

That's a good question, Sumerio will follow the Lua and Ruby's closing style. I always tend to think `end` keyword is often related to dynamic languages and curly braces with static typed languages, off course this isn't true but if you peek all C-family programming languages you'll notice that most are statically type.

###  🧲 &nbsp;Follow me... 
<p align="center">
    <a href="https://youtube.com/IrwinRodriguez">
        <img src="https://img.shields.io/badge/Youtube-Channel-red" />
    </a>
    <a href="mailto:rodriguez.irwin@gmail.com">
        <img src="https://img.shields.io/badge/Gmail-Contact-yellowgreen" />
    </a>
    <a href="https://twitter.com/irwin_rg">
        <img src="https://img.shields.io/badge/Twitter-irwin__rg-blue" />
    </a>
    <a href="https://instagram.com/irwinrdz85">
        <img src="https://img.shields.io/badge/Instagram-irwinrdz85-red" />
    </a>
    <a href="https://www.linkedin.com/in/irwin1985/">
        <img src="https://img.shields.io/badge/LinkedIn-irwin1985-orange" />
    </a>
</p>
