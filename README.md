# Python Carreer
## _Functional Programming_

**_Paradigm in which function definitions are trees of expressions that map values to other values, rather than a sequence of imperative statements which update the running state of the program_**

> Functional programming is the paradigm where a problem is decompose into a set of functions. Ideally, functions only take inputs and produce outputs, and don’t have any internal state that affects the output produced for a given input.

In functional programming each function operates on its input and produces some output. This style discourages functions with side effects that modify internal state or make other changes that aren’t visible in the function’s **returned value**.

> Python programs written in functional style usually **won’t go to the extreme of avoiding all I/O or all assignments;** instead, they’ll provide a functional-appearing interface but will use non-functional features internally. 

For example, the implementation of a function will still use assignments to local variables, but **won’t modify global variables or have other side effects**.

### Pure functions

1. High-level modules should not depend on low-level modules. Both should depend on abstractions.
2. Abstractions should not depend on details. Details should depend on abstractions.

https://www.infoworld.com/article/3613715/what-is-functional-programming-a-practical-guide.html#:~:text=Generally%2C%20functional%20programming%20means%20using,described%20as%20a%20programming%20paradigm.

https://docs.python.org/3/howto/functional.html

https://www.dataquest.io/blog/introduction-functional-programming-python/