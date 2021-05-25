# Chapter 10 JS Debugging (pg 450)

## Order of Execution
- When looking at an executed fucntion, the function may need an actualy value that is inputted by the user then executed by the function that takes the input then places it in a string. *Pg.452*
**Execution Context** 
- Global context = code that is in script, but not in the fucntion.
- Function Context = Code that is being run within the function.
- Eval Context = text is executed like code in an internal function that is called.
**Variable Scope** 
- Global scope = variables that are declared outside of a fucntion, it can be used anywhere becasue it has global scope.
- function-level scope = variables that are declared within a function, can only be used within that function.

## Execution Context & Hoisting
1. Prepare: The new scope is created/ Variables, functions, and arguments are created.
2. Execute: Now it can assign values to variables/ Reference functions and run their code/ Execute statements.
**Understanding Scope**
- Within a function there is the ability to use the inner fucntion to refer to the outter function.
```
function foo() {
  // "foo" function scope
  let count = 0;
  console.log(count); // 0
}

function bar() {
  // "bar" function scope
  let count = 1;
  console.log(count); // 1
}

foo();
bar();
```

**Understanding Errors** 
- Error objects helps with understadning what errors to pikc out of the code.
- Besides the generic Error constructor, there are other core error constructors in JavaScript. For client-side exceptions, see Exception handling statements.
**Types of Errors**
*EvalError*
Creates an instance representing an error that occurs regarding the global function eval().
*RangeError*
Creates an instance representing an error that occurs when a numeric variable or parameter is outside of its valid range.
*ReferenceError*
Creates an instance representing an error that occurs when de-referencing an invalid reference.
*SyntaxError*
Creates an instance representing a syntax error.
*TypeError*
Creates an instance representing an error that occurs when a variable or parameter is not of a valid type.
*URIError*
Creates an instance representing an error that occurs when encodeURI() or decodeURI() are passed invalid parameters.
*AggregateError*
Creates an instance representing several errors wrapped in a single error when multiple errors need to be reported by an operation, for example by Promise.any().
*InternalError*
Creates an instance representing an error that occurs when an internal error in the JavaScript engine is thrown. E.g. "too much recursion".
