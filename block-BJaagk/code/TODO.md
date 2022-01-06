1. Convert the function below into different forms of function expression.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}

// Your code goes here

//1st-form
let percentage = function percentage(marks, total) {
  return (marks * 100) / total;
}

//2nd-form
let percentage = function(marks, total) {
  return (marks * 100) / total;
}

//3rd-form
let percentage = (marks, total)=> {
  return (marks * 100) / total;
}
```

2. Write Function Declaration or Function Expression next to the function.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}
// Your answer
// Function Declaration
```

```js
let percentage = function percentage(marks, total) {
  return (marks * 100) / total;
};
// Your answer
// Function Expression
```

```js
let percentage = function (marks, total) {
  return (marks * 100) / total;
};
// Your answer
// Function Expression
```

```js
let percentage = (marks, total) => {
  return (marks * 100) / total;
};
// Your answer
// Function Expression
```

```js
let percentage = (marks, total) => (marks * 100) / total;
// Your answer
// Function Expression
```

3. Why is a function definition an expression in JavaScript? Give one example of function expression.
Because the function defination means when function is starting with the keyword function thai is kniwn as function defination. and in the function expresssion we can store the function defination in a variable with the name of the function(optional).
eg-
```js
let store =  function addition (num1,num2){
  return num1 + num2
}
```


4. Why is a function call an expression in JavaScript?
```js
// function expression is starting with expression that kind oof function is known as function expression
//and expression is anything that results into a value so the function call an expression in javascript


```
5. Write VALID and INVALID next to each example below with the reason.

```js
function add(a, b) {
  return a + b;
}

let five = add(2, 3); // Answer VALID because on the right hand side of equal to is function expression
five = add; // Answer VALID because on the right hand side of equal to is variable
five = five(10, 11); // Answer VALID because on the right hand side of equal to is function expression
five = function () {
  return 'Hello';
}; // Answer VALID because it is function expression.
```

6. What is the difference between function definition and function call? Explain with an example.
The difference between function definition and function call is in function defination we have the keyword function and while in function call we don`t have keyword function we have name of the function.
```js
//function defination
function fullName (firstname,lastname){
  return `${firstname} ${lastname}`
}

//function call
fullName(lovekush,rajput)
```
7. What is the similarities between function definition and function call?
both have the function name.
8. Is the code below valid or invalid. Explain with reason.

```js
function hello() {
  console.log('Hello World!');
}

hello.user = 'Sam'; // valid or invalid it is valid because here function behaving like object and function is an special kind of object that can be execute
```

9. What is higher order function explain with an example.
The function that accepts a function defination as an argument it is known as higher order function.

eg-
```js
function add (num1 , num2){
  return num1+num2
}

let fillterAdd = (arr,fn)=>{
  console.log(fn(1,2))
  return arr
}
//filterAdd is higher order function
//fn is function defination as arguments
filterAdd([1,2,3,4],add)
```
10. Explain what is callback function. Why you can pass a function inside a function?
A callback function is a function that is to be executed after the another function is execute.thta is known as callback function. 
because function is an expression.
 