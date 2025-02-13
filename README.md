
# Lesson - 4
```
    Table of Contens
            |
        |--------|
  Recursion     Clouser
```
## 1) Recusion - Recursion in programming is like a
function that keeps calling itself. When a
function does this, its called a
recursively defined function.

But there is a rule it has to follow: it must
have a way to stop calling itslef,

or it will go on forever. This stopping rule
is called the base case

## Example:
```
function factorial(n) {
    if (n === 0 || n === 1) return 1; // Base case
    return n * factorial(n - 1); // Recursive case
}

console.log(factorial(5)); // Output: 120

```

A recursive function function must have a condition to stop calling itself. Otherwise function is
called indefinetelly.

Once the condition is met, the function stops calling itself. This called the base condition

First, you need a base condition num === 0.

You also need the recursive call
findFactorial(num - 1) to ensure the number
keeps reducing at each call when you pass a
new parameter of n-1.

Then you multiply the result with the previous
number num * findFactorial(num - 1) until the
base condition is met.

## 2)Closure is the combination of a function bundled together (enclosed) with references to its
surrounding state (the lexical enviroment). In other words a closure gives you access to an
outer functions scope from an inner function


## Example:
```
function outerFunction(outerVariable) {
    return function innerFunction(innerVariable) {
        console.log(`Outer: ${outerVariable}, Inner: ${innerVariable}`);
    };
}

const closureExample = outerFunction("Hello");
closureExample("World"); // Output: Outer: Hello, Inner: World
```
A closure is a function that remembers its outer variables and
can access them. In some languages, this is not possible, or
the function must be written in a special way to create a
closure.


# Thank you Be happy and Smila 😁!

![Снимок экрана 2025-02-13 154519](https://github.com/user-attachments/assets/c0b3a3d6-2ba1-4cf4-8fc7-f14d8325f149)
