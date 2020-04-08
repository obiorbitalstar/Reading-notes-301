# Functional Programming in Javascript
 Functional programming is a programming paradigm — a style of building the structure and elements of computer programs — that treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data — Wikipedia

 ## pure functions 
 It returns the same result if given the same arguments

 ### Reading Files
If our function reads external files, it’s not a pure function — the file’s contents can change.
 ### Random number generation
Any function that relies on a random number generator cannot be pure.
 ### It does not cause any observable side effects
Examples of observable side effects include modifying a global object or a parameter passed by reference.
 ### Pure functions benefits
The code’s definitely easier to test. We don’t need to mock anything. So we can unit test pure functions with different contexts:
Given a parameter A → expect the function to return value B
Given a parameter C → expect the function to return value D

## Immutability
Unchanging over time or unable to be changed.
When data is immutable, its state cannot change after it’s created. If you want to change an immutable object, you can’t. Instead, you create a new object with the new value.