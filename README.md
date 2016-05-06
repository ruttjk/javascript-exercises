# javascript-exercises
Exercises in the Javascript language from a recent training class with Douglas Crockford.

| File | Exercise Description | Example |
|------|----------------------|---------|
| [exercise1](blob/master/src/exercise1.html) | *Identity*. Write a unary function that will return the argument that was passed in. | `identity(3) === 3`|
| [exercise2](blob/master/src/exercise2.html) | *Basic math functions*. Write binary functions that will return the sum, difference, and product of the numbers that were passed in. | `(add(3, 4) === 7)`,`(sub(3, 4) === -1)`, `(mul(3, 4) === 12)` |
| [exercise3](blob/master/src/exercise3.html) | *Identity function*. Write a binary function that will return a function that returns the value that was passed to the function. | `identityf(3) === 3` |
| [exercise4](blob/master/src/exercise4.html) | *Add function*. Write a unary function that will return a unary function that returns the value of a number that is added to the original number. | `addf(3)(4) === 7`  |
| [exercise5](blob/master/src/exercise5.html) | *Curry*. Write a binary function that takes a binary function as the first argument and a number as the second argument and returns a unary function that returns the evaluation of the function and the 2 arguments. | `var add3 = curry(add, 3); add3(4) === 7` |
| [exercise6](blob/master/src/exercise6.html) | *Reverse curry*. Write a binary function that takes a binary function as the first argument and a number as the second argument and returns a unary function that returns the evaluation of the function and the 2 arguments IN REVERSE ORDER. | `var sub3 = curryr(sub, 3); sub3(11) === 8` |
| [exercise7](blob/master/src/exercise7.html) | *Lift*. Write a unary function that takes a binary function as an argument and returns a unary function that takes a number as an argument and returns a unary function that takes a number as an argument and evaluates the original function and the 2 numbers. | `var laddf = liftf(add); laddf(3)(4) === 7; liftf(mul)(5)(6) === 30` |
| [exercise8](blob/master/src/exercise8.html) | Without writing any new functions, show 4 ways to create an increment (plus 1) function. | |
| [exercise9](blob/master/src/exercise9.html) | *Twice*. Write a unary function that takes a binary function as an argument and returns a unary function that takes a number as an argument and evaluates the original function passing the number as both arguments. | `var dbl = twice(add); dbl(11) === 22` |
| [exercise10](blob/master/src/exercise10.html) | *Reverse*. Write a unary function that takes a binary function as the argument and returns a binary function that takes 2 number arguments and evaluates the original function with the number arguments in reverse order. | `var bus = reverse(sub); bus(3, 2) === -1` |
