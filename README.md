# my-5th-project

 Code Explanation (Multiplication Example)
 Overview

This TypeScript code demonstrates how to declare numeric variables, assign values to them, perform a multiplication operation, and print the result to the console.

Step-by-Step Explanation
let num1: number; 
let num2: number; 
let num3: number;
let num4: number;


Four variables are declared: num1, num2, num3, and num4.

Each variable is explicitly typed as number.

Type annotations ensure type safety by restricting values to numeric data only.

num1 = 10;
num2 = 89;
num3 = 83;


Three variables are assigned numeric values:

num1 = 10

num2 = 89

num3 = 83

num4 = num1 * num2 * num3;


The multiplication operator * is used to multiply the three numbers.

The calculation is performed from left to right:

10 × 89 = 890

890 × 83 = 73870

The final result 73870 is stored in num4.

console.log(num4);


The console.log() function prints the value of num4 to the console.

The output will be:

73870

 What the Code Does

Declares four numeric variables.

Assigns values to three of them.

Multiplies the three numbers together.

Stores the result in a fourth variable.

Prints the result to the console.

 Learning Purpose

Understanding variable declaration in TypeScript.

Using type annotations (number).

Performing multiplication operations.

Storing computed results in a variable.

Displaying output using console.log().
