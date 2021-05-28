1. Using loops take 10 inputs from user and find the average of all the numbers.

let average = 0;

 for(let i = 0 ; i < 10 ; i= i + 1){
         
    let numA = +prompt(`enter the number`)
     
    average = average + numA
}   

 console.log(average/10); 


2. What will be the output of the code below

```js
let i = 0;
while (i < 3) {
  println('hi');
  i++;
}
 ReferenceError: println is not defined
```

3. Write a function named `getEvenSum` that accepts a parameter `max`. Return the sum of all even numbers. The value of max should default to 10.

function getEvenSum(max){
    let sum = 0;
    for(let i = 0 ; i <=max; i++){        
        if(i % 2 === 0){
            sum = sum + i;
        }
    } return(sum);
}

4. Write a function named `getOddSum` that accepts a parameter `max`. Return the sum of all odd numbers. The value of max should default to 10.

function getEvnenumber(max){
    let sum =0;
    for(let i = 0
    ; i<= max; i++){
        if(i % 2 !==0){
            sum = sum + i;
        }
      }  return(sum)
}
getEvnenumber(max)




5. Write a function named `getProductOfDigits` that accepts a parameter `num`. It returns the product of all the digits in the number.

- If the input value is less than 0 return `not a valid input`
- For example if the input is `123` output should be `6`.



6. What will be the output of the following code below in multiple conditions? Explain with reason?

```js
function check(num) {
  if (num > 5) {
    return 'Bigger than 5';
  }

  if (num < 5) {
    return 'Smaller than 5';
  }

  return num;
}

check(10); // "Bigger than 5"
check(1); //"Smaller than 5"
check(5); // 5
```

7. What will be the output of the following code given below? Explain the reason?

```js
function getOutput(name) {
  if (name === 'Arya') return 'You are arya';
  if (name === 'John') return 'You are john';
  return 'Who are you';
}

getOutput('Arya'); // "You are arya"
getOutput('John'); // "You are john"
getOutput(); // "Who are you"
```

8. What will be the output of the following code given below? Explain the reason?

```js
function getOutput(name) {
  if (name === 'Arya') console.log('You are arya');
  if (name === 'John') console.log('You are john');
  return 'Who are you';
}

getOutput('Arya'); // "Who are you"
getOutput('John'); // "Who are you"
getOutput(); //"Who are you"
```

9. Can a function have multiple return statement? Give one example if possible and explain the reason.

Only one return statement gets executed. If we write more than one return statements and the compiler comes across two return statements consecutively then the compiler may give us an error while compiling. But this doesn't mean we can not use more than one return statements, we may do so but setting appropriate conditions using conditional statements is required, for example…

function getOutput(name) {
  if (name === 'Arya') return 'You are arya';
  if (name === 'John') return 'You are john';
  return 'Who are you';
}

10. What is the difference between `for` loop and `while` loop. What are the different place you can use them? Explain with example.

The 'for' loop used only when we already knew the number of iterations. The 'while' loop used only when the number of iteration are not exactly known. If the condition is not put up in 'for' loop, then loop iterates infinite times. If the condition is not put up in 'while' loop, it provides compilation error.