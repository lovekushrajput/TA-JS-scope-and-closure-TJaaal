1. What does thread of execution means in JavaScript?
```js
To execute the code line by line in known as thread of execution and this execution is done by javascript engine
```
2. Where the JavaScript code gets executed?
```js
The javascript code is execute in the global execution context.
```
3. What does context means in Global Execution Context?
```js
context means it provide the environment in the code is execute
```
4. When do you create a global execution context.
```js
when there is a program or a code the javascript engine creates a global execution context
```
5. Execution context consists of what all things?
```js
it consist of two kind 
1- global execution context
2- function execution context.

it have two section 
1- where the code is execute
2- where the data is stored known as memory.
```
6. What are the different types of execution context?
```js
it consist of two kind 
1- global execution context
2- function execution context.
```
7. When global and function execution context gets created?
```js
global execution context creates throughout the program
function execution context creates when threre is function.
```

8. Function execution gets created during function execution or while declaring a function.
```js
Function execution gets created during function execution.
```

9. Create a execution context diagram of the following code on your notebook. Take a screenshot/photo and store it in the folder named `img`. Use `![](./img/image-name.png)` to display it here.



```js
var user = "Arya";

function sayHello(){
  return `Hello ${user}`;
}

var userMsg = sayHello(user);
```
<!-- Put your image here -->
 

![](./img/image-name.jpg)



```js
var marks = 400;
var total = 500;

function getPercentage(amount, totalAmount){
  return (amount * 100) / totalAmount;
}

var percentageMarks = getPercentage(marks, total);
var percentageProfit = getPercentage(400, 200);
```

<!-- Put your image here -->

![](./img/image-name.jpg)



```js
var age = 21;

function customeMessage(userAge){
  if(userAge > 18){
    return `You are an adult`;
  }else {
    return `You are a kid`;
  }
}

var whoAmI = customeMessage(age);
var whoAmIAgain = customeMessage(12);
```

<!-- Put your image here -->

![](./img/image-name.jpg)