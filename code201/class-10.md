# Error Handling and Debugging

- If you understand execution contexts (which have two stages) and stacks, you are more likely to find the error in your code.
- Debugging is the process of finding errors. It involves a process of deduction.
- The console helps narrow down the area in which the error is located, so you can try to find the exact error.
- JavaScript has 8 different types of errors. Each creates its own error object, which can tell you its line number and gives a description of the error.
- If you know that you may get an error, you can handle it gracefully using the try, catch, finally statements. Use them to give your users helpful feedback.


### ***JavaScript Error Types***

Besides the generic Error constructor, there are other core error constructors in JavaScript. For client-side exceptions, see Exception handling statements.

- **EvalError**

Creates an instance representing an error that occurs regarding the global function eval().

- **RangeError**

Creates an instance representing an error that occurs when a numeric variable or parameter is outside of its valid range.

- **ReferenceError**

Creates an instance representing an error that occurs when de-referencing an invalid reference.

- **SyntaxError**

Creates an instance representing a syntax error.

- **TypeError**

Creates an instance representing an error that occurs when a variable or parameter is not of a valid type.

- **URIError**

Creates an instance representing an error that occurs when encodeURI() or decodeURI() are passed invalid parameters.

- **AggregateError**

Creates an instance representing several errors wrapped in a single error when multiple errors need to be reported by an operation, for example by Promise.any().

- **InternalError** 

Creates an instance representing an error that occurs when an internal error in the JavaScript engine is thrown. E.g. "too much recursion".

### ***If you are implementing error handling mechanism you can check which kind of error you are catching from code***

```
try {
    throw new TypeError();
}
catch (e){
    if(e instanceof Error){
        console.log('instance of general Error constructor');
    }

    if(e instanceof TypeError) {
        console.log('type error');
    }
}
```
In such case ```e``` will be an instance of ```TypeError```. All error types extend the base constructor ```Error```, therefore it's also an instance of ```Error```.

Keeping that in mind shows us that checking ```e``` to be an instance of ```Error``` is useless in most cases.