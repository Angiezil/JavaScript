# JavaScript
JavaScript Exercises 
Activity 1 - Vanilla JS Basics
Write a JavaScript program to print the result of the following operations.
Test Data:
a. -5 + 8 * 6 
b. (55+9) % 9 
c. 20 + -3*5 / 8 
d. 5 + 15 / 3 * 2 - 8 % 3

<script>

// Operation a
const data1 = -5 + 8 * 6;
console.log( "Result of data 1:" , data1);
// Operation b
const data2 = (55 + 9) % 9;
console.log("Result of data 2:", data2);

// Operation c
const data3 = 20 + -3 * 5 / 8;
console.log("Result of data 3:", data3);

// Operation d
const data4 = 5 + 15 / 3 * 2 - 8 % 3;
console.log("Result of data 4:", data4);
</script>





Activity 2 - Vanilla JS Basics
Write a JavaScript program to divide two numbers, using the input from the user, and print the result on the screen.
Expected Output :
Input the first number: 6
Input the second number: 2
The division of the first number and the second number is: 3
// Prompt the user to input the first number
let number1 = prompt("Input the first number:");

// Prompt the user to input the second number
let number2 = prompt("Input the second number:");

// Perform the division
let resultadoDivision = number1 / number2;
console.log("The division of the first number and the second number is:", resultadoDivision);



Activity 1 - Control Statements
Write a JavaScript program that accepts three numbers and prints "All numbers are equal" if all three numbers are equal, "All numbers are different" if all three numbers are different and "Neither all are equal or different" otherwise.
Test Data:

let firstNumber = 2
let secondNumber = 3
let thirdnumber = 4

if (firstNumber === secondNumber && secondNumber === thirdnumber) {
  console.log("All numbers are equal");
}
else if (firstNumber !== secondNumber && secondNumber !== thirdnumber) {
  console.log("All numbers are different");
}
 else {
  console.log("Neither all are equal or different");
 }
</script>

Activity 2 - Control Statements
Write a JavaScript program that accepts three numbers from the user and prints "Increasing order" if the numbers are in the increasing order, "Decreasing order" if the numbers are in the decreasing order, and "Neither increasing or decreasing order" otherwise.
Test Data:
Input first number: 1524
Input second number: 2345
Input third number: 3321

let firstNumber = 1524
let secondNumber = 2345
let thirdnumber = 3321

if (firstNumber < secondNumber && secondNumber < thirdnumber) {
  console.log("Increasing order");
}
else if (firstNumber > secondNumber && secondNumber > thirdnumber) {
  console.log("Decreasing order");
}
 else {
  console.log("Neither increasing or decreasing order");
 }
</script>

Activity 1 - Vanilla JS Loops
Write a JavaScript program that will iterate from 0 to 15. For each iteration, it will check if the current number is odd or even, and display a message to the screen.
Expected Output:
"0 is even"
"1 is odd"
"2 is even"
<script>
    // program that will iterate from 0 to 15 it will check if the current number is odd or even
    for (let i = 0; i <= 15; i++) {
  if (i / 2 === 0) {
    console.log(i + " is even");
  } else {
    console.log(i + " is odd");
  }
}
</script>


Activity 2 - Vanilla JS Loops
Write a JavaScript program to create the multiplication table (from 1 to 10) of a number.
Expected Output:
Input a number: 5
<script>
const number = 5
const n = 10
for (let i = 1; i <= n; i++) {
    const result = number * i;
    console.log(number + " x " + i + " = " + result);
}
</script>





Activity 1 - Vanilla JS Arrays
a JavaScript program to sum values of an array.
Test Data:
Sample Array:
[1, 2, 3, 4, 5, 6, 7, 8, 9, 10]
Expected Output:
The sum is 55.

<script>
let numbers = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10];
console.log(numbers);

let sum = 0

for (let i = 0; i< numbers.length; i++) {
sum += numbers[i]; }
console.log("The sum is " + sum + ".");

</script> 


Activity 2 - Vanilla JS Arrays
Write a JavaScript program to calculate the average value of an array elements.
Test Data:
Sample Array:
[20, 30, 25, 35, -16, 60, -100]
Expected Output:
Average value of the array elements is : 7.7.


<script>
let sample = [20, 30, 25, 35, -16, 60, -100];
let sum = 0;

for (let i = 0; i < sample.length; i++) {
  sum += sample[i];
}

let average = sum / sample.length;

console.log("Average value of the array elements is: " + average.toFixed(1) + ".");

</script> 

