# Javascript Interview Question

### What is lexical Scope?

- Lexical scope is the ability for a function scope to access variables from the parent scope.

### What are closures function?

- The functions which have the lexical scope and can access the parent scope even after the parent function has closed.
- A function bundled together with its lexical environment forms a closure.

```
function clos(num){
    var a= 7 ;
    function inner(num2){
        return num + num2
    }
    return inner;
}
var call = clos(5);
console.log(call)
console.log(call(6))
```

#### Advantage of Closures Function:-

- Currying function
- Data hiding

### What is hoisting?

- Hoisting is the javascript behavior of moving declarations at the top of the program.
  var declaration is hoisted up and initialized with undefined
  Let and const declaration are hoisted up but not initialized

- Arrow functions don't have their own ‘this’. In these functions the value of this depends upon the lexical scope.

```console.time(“”)
   function();
   Console.time
```

### What is Node JS?

- Node.js is an open-source and cross-platform runtime environment for executing JavaScript code outside a browser. We often use Node.js for building back-end services APIs like Web App or Mobile App.

### What is scope?

- Scope in JavaScript actually determines the accessibility of variables and functions at various parts in one’s own code or program.

### Difference between promise and callbacks?
