# In Memory Storage

## Understanding the JavaScript Call Stack

1. **What is a ‘call’?**

    A call is the invocation of a function.

2. **How many ‘calls’ can happen at once?**

    Only one call can happen at a time.

3. **What does LIFO mean?**

    Last In, First Out. It means that the last function to get pushed into the call stack is the first to be popped out.

4. **Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.**



5. **What causes a Stack Overflow?**

    A stack overflow happens when a recursive function, or function that calls itself, does so without having an exit point to stop calling itself.

## JavaScript error messages

1. **What is a ‘reference error’?**

    A reference error is an error that happens when you attempt to use a variable that has not been declared yet.

2. **What is a ‘syntax error’?**

    A syntax error is caused by having improper syntax that prevents the interpreter from parsing the code such as missing syntax or unexpected syntax.

3. **What is a ‘range error’?**

    A range error happens when you try to assign an invalid length to an object that has length such as an array.

4. **What is a ‘type error’?**

    A type error is an error that happens when the type of data is incompatible with what you are trying to do such as trying to access a method on something that isn't an object.

5. **What is a breakpoint?**

    A line in the code you specify which you want the interpreter to pause on before moving forward so you can review everything that has happened from the code up until that point.

6. **What does the word ‘debugger’ do in your code?**

    It will add a breakpoint.

## Things I want to know more about

- What are the use cases for a recursive function?

## References

- [freeCodeCamp: The JavaScript Call Stack - What It Is and Why It's Necessary](https://www.freecodecamp.org/news/understanding-the-javascript-call-stack-861e41ae61d4)
- [codeburst: JavaScript error messages && debugging](https://codeburst.io/javascript-error-messages-debugging-d23f84f0ae7c)
