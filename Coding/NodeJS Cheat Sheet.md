# NodeJS Cheat Sheet

- [NodeJS Cheat Sheet](#nodejs-cheat-sheet)
    - [Concepts](#concepts)
        - [Scope](#scope)
    - [Variables](#variables)
        - [Defining Variables](#defining-variables)
            - [The Difference Between `let` and `var`](#the-difference-between-let-and-var)

## Concepts

### Scope

The scope of a variable is the locations the variable can be accessed. A variable with a global scope can be accessed from anywhere, while a scoped variable is only accessible in some locations (the function in which it was declared, for instance).

```js
let x = "Hello!";

function foo() {
    let y = "Hi!";
    console.log(x); // prints "Hello!"
    console.log(y); // prints "Hi!"
}

foo();

console.log(x); // prints "Hello!"
console.log(y); // Gives a reference error
```

## Variables

### Defining Variables

- `let x = 1;` - Basic variable definition
- `var x = 1;` - Basic variable definition (see [The Difference Between let and var](#the-difference-between-let-and-var))
- `const x = 1;` - Define an unchangeable, constant variable

#### The Difference Between `let` and `var`

`let` and `var` accomplish essentially the same thing. The difference is [scope](#scope): a variable defined with `let` is only accessible in the immediate closing brackets `{}`, but `var` is accessible anywhere in the function.
