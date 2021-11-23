1. Convert the function below into different forms of function expression.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}

// Your code goes here
let percentage = function (marks, total) {
  return (marks * 100) / total;   //expression
}
```

2. Write Function Declaration or Function Expression next to the function.

```js
function percentage(marks, total) {
  return (marks * 100) / total;   //declaration
}
// Your answer.   (marks, total) => {
  return (marks * 100) / total;
}
```

```js
let percentage = function percentage(marks, total) {
  return (marks * 100) / total;   // expression
};
```

```js
let percentage = function (marks, total) {
  return (marks * 100) / total; //exoression
};
```

```js
let percentage = (marks, total) => {
  return (marks * 100) / total;   // expression
};
```

```js
let percentage = (marks, total) => (marks * 100) / total;  // expression
```

3. Why is a function definition an expression in JavaScript? Give one example of function expression.

4. Why is a function call an expression in JavaScript? // function call always returns a value that's why it is an expression

5. Write VALID and INVALID next to each example below with the reason.

```js
function add(a, b) {
  return a + b;
}

let five = add(2, 3); // valid 5
five = add; // valid. 
five = five(10, 11); // valid 21
five = function () {
  return 'Hello';
}; // valid
```

6. What is the difference between function definition and function call? Explain with an example.
 expression is an object
call is an expression that returns a value



7. Is the code below valid or invalid. Explain with reason.

```js
function hello() {
  console.log('Hello World!');
}

hello.user = 'Sam'; // valid
```

9. What is higher order function explain with an example.
accepts a function definition or returns a function definition


10. Explain what is callback function. Why you can pass a function inside a function?

function is expression in JS, so we can pass another fn in JS
