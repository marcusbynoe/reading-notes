## Class 09

## Functional Programming Concepts

1. **What is functional programming?:** programming paradigm — a style of building the structure and elements of computer programs — that treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data.

2. **What is a pure function and how do we know if something is a pure function?:**  A function (a block of code) that always returns the same result if the same arguments are passed. You can tell if something is a pure function by "It not causing any observable side effects".

3. **What are the benefits of a pure function?:** The code is definitely easier to test. We don’t need to mock anything. So we can unit test pure functions with different contexts.

4. **What is immutability?:** When data is immutable, its state cannot change after it’s created. If you want to change an immutable object, you can’t. Instead, you create a new object with the new value.

5. **What is Referential transparency?:**Referential Transparency emphasizes that an expression in a JavaScript program may be replaced by its value or any other variable having the same value without changing the result of the program.

## Node JS Tutorial for Beginners - Modules and require()

1. **What is a module?:**A simple or complex functionality organized in single or multiple JavaScript files which can be reused throughout the Node. js application.

2. **What does the word ‘require’ do?**Facilitates a way to include JavaScript modules in your code.

3. **How do we bring another module into the file the we are working in?:** With the `require` function.

4. **What do we have to do to make a module available?:** With `module.exports`.