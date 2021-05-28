1. What is the difference between the two `sum` function given below?

```js
// first


in this the output will be sum of two number or if in case of string it will concatinate the result
// second
function sum(a, b) {
  console.log(a + b);
}

in this the output will be undefined
```

2. If we store the returned value of both functions above in variable `first` and `second` what will be the value of `first` and `second`.

ans= The value of 'first' will be the output of the first function and the value of second will be undefined

3. What will be the output when you call above `sum` function (first) with three parameter like `sum(12, 24, 35)`. Explain why?
ans= The output will be 36 since the place holder is define by two variable only i.e a,b so the first two value will get add and the third will be ignore by javascript



4. Can you store the first `sum` function in a variable named `add`. If yes why? If no why?
ans= yes we can add the function in a variable

5. Declare a function named `sayHello` the accepts a parameter `name` and returns the name like `Hello Arya`.
solution=  function sayHello(name){
  return name;

}
sayHello("Hello Arya")// "Hello Arya"

6. What will be the output of the function below and why?

```js
let userName = 'John';

function showMessage() {
  let message = 'Hello, ' + userName;
  return message;
}

showMessage();// "Hello,John"
```

7. What will be the output for `Output1` `Output2` and `Output3` in the code below.

```js
let userName = 'John';

function showMessage() {
  let message = 'Hello, ' + userName;
  return message;
}

alert(userName); // John

showMessage(); // "Hello, John"

alert(userName); // John 
```

8. What is a Anonymous Function give example of three functions.
ans = An anonymous function is a function without a name. An anonymous function is often not accessible after its initial creation. In this example, the anonymous function has no name between the function keyword and parentheses () 
example:-
let show = function () {
    console.log('Anonymous function');
};

show();

9. Can function declaration be a Anonymous Function? Explain
ans= no, because in an anonymous we will not be giving the name to a function and in function declaration we will name the function in between  the function keyword and parantheses()

10. Give 5 example of good naming convention for defining a function. You can read the details below to do that.

ans = 1)function toCelsius(fahrenheit)()
2) function getName()
3) function getNmber()
4) function showMessage()
5) function sum()
```md
Functions are actions. So their name is usually a verb. It should be brief, as accurate as possible and describe what the function does, so that someone reading the code gets an indication of what the function does.

It is a widespread practice to start a function with a verbal prefix which vaguely describes the action. There must be an agreement within the team on the meaning of the prefixes.

For instance, functions that start with "show" usually show something.

Function starting with…

"get…" – return a value,
"calc…" – calculate something,
"create…" – create something,
"check…" – check something and return a boolean, etc.
```
