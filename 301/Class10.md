# Class 10

## Understanding the JavaScript Call Stack

1. **What is a ‘call’?:** The call stack is primarily used for function invocation (call).

2. **How many ‘calls’ can happen at once?:** One

3. **What does LIFO mean?:**Last In, First Out (LIFO)

4. **Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.:**

```
  function firstFunction(){
  throw new Error('Stack Trace Error');
  }

  function secondFunction(){
  firstFunction();
  }

  function thirdFunction(){
  secondFunction();
  }

  thirdFunction();
```


5. **What causes a Stack Overflow?:**A stack overflow occurs when there is a recursive function (a function that calls itself) without an exit point.

## JavaScript Error Messages

1. **What is a ‘reference error’?:**This is as simple as when you try to use a variable that is not yet declared you get this type os errors. This is also a common thing when using `const` and `let`.

2. **What is a ‘syntax error’?:**Occurs when you have something that cannot be parsed in terms of syntax, like when you try to parse an invalid object using JSON.parse.

3. **What is a ‘range error’?:**Try to manipulate an object with some kind of length and give it an invalid length and this kind of errors will show up.

4. **What is a ‘type error’?:**Like the name indicates, this types of errors show up when the types (number, string and so on) you are trying to use or access are incompatible, like accessing a property in an undefined type of variable.

5. **What is a breakpoint?:**In the debugger window, you can set breakpoints in the JavaScript code. At each breakpoint, JavaScript will stop executing, and let you examine JavaScript values. After examining values, you can resume the execution of code (typically with a play button).

6. **What does the word ‘debugger’ do in your code?:** Breakpoint can also be achieved by putting a debugger statement in your code in the line you want to break.