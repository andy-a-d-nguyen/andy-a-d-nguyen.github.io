---
layout: page
title: "Class 07"
permalink: /reading-notes/class-07/
---

## Global and Nonlocal Keywords

According to <https://realpython.com/python-scope-legb-rule/#the-global-statement>, the global scope is the highest scope in a Python program and variables defined in the global scope are available everywhere in the Python program.

On the other hand, a nonlocal scope refers to a scope that is created in a function that contains one or more functions. A function that is inside another function is also called a nested function.

By using the `global` keyword, a variable defined in a local scope is treated as being in the global scope.

By using the `nonlocal` keyword, a variable inside a nested function is treated as being in the scope of the nest function's enclosing function.

## Bookmarks and Review

<https://artofproblemsolving.com/wiki/index.php/Basic_Programming_With_Python#Program_Example_1_3>

## Things I want to know more about

- When is it necessary to use the `global` keyword and the `nonlocal` keyword?
