## Description
```Calculator``` This is an HTML page that provides a simple calculator.
 The purpose of this program is to show the simplicity and convenience of using JavaScript 🧡 codes from that time.

## Installation
To use this program, do the following steps :
1. Simulate your repository:``` git clone https://github.com/MaryaJamali/Calculator.git```
2. Open the HTML file in your browser.

## Notable point
In the calculator section, when the user clicks on the "=" button, this part of the code is executed.
```JavaScript 
<input type="button" class="equal-button" value="="
onclick="calculator.input.value =eval(calculator.input.value)">
```
First, the value entered in the text input, i.e. the mathematical expression, is received using ```calculator.input.value```.
Then this expression is calculated using the ```eval() function``` . The ```eval() function``` executes the mathematical expression
as JavaScript code and returns its result. Finally, the value of the calculation result is set as the new input value for
 the calculator's text input, allowing the user to see the result of the operation.

## Author:
Maryam Jamali 🤍
