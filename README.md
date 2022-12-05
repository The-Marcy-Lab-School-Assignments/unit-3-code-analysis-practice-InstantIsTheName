# unit-3-code-analysis-practice

Using markdown, identify what the following code block does and explain how the `forEach` function works.

```js
function forEach(arr, action) {
  for (let i = 0; i < arr.length; i++) {
    action(arr[i]);
  }
}

forEach(['a', 'b', 'c'], console.log);
```

**Guiding Questions:**
* What does the code do (what does it print? are any variable reassigned? etc...)
* What are the expected data types for each of the parameters?
* When the function is invoked, what value are provided as arguments?
* How does `forEach` use the provided arguments?

**Key Terms to use**: parameters, arguments, invoke/invocation, iterate, "element of the array", increment,  

<hr>

Your explanation here...

In the first line the funciton `for each` is declared with two parameters: `arr` and `action`. Within the block scope, arr is iterated to `arr.length` and each element is changed by the parameter's function. When `for each` is involked, it has an array with the values `a,b,c` and the action of console logging. Laslty, it's iterated through the array and console logged. 
