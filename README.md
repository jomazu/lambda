# λ - Dev Container
![lambda logo](https://res.cloudinary.com/jomazu/image/upload/v1641881626/Programming/lambda-calculus.png)

Used with VS Code **Remote - Containers**, as a containerized Docker development environment.

---
## Haskell

Is a **FUNCTIONAL** programming language, treating computation as the evaluation of mathematical functions, avoiding state and mutable data.

In contrast, with **IMPERATIVE** programs, you can execute statement by statement, keeping track of the values of variables (the stack) and where you are in the program (the program counter).
  * There are only expressions in Haskell, i.e. no statements.
* Things that look like assignments in Haskell are not updates of values but equations.

The primary mechanism for executing functional programs is **REDUCTION**.

## Reduction
Is the process of converting an expression to a simpler form. Conceptually, an expression is reduced by simplifying one *reducible expression* (called "**redex**") at a time. Each step is called a reduction.

Reduction is important because it is the sole means of execution of a functional program. There are no statemnts, as in imperative languages; all computation is achieved purely by reducing expressions.

Simplified example of reduction being performed:

```haskell
3 + (5 * (8 - 2))
-->
3 + (5 * 6)
-->
3 + 30
-->
33
```
