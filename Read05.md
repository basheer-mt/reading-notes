# Read: 05 - Operators and Loops

## Comparison Operators:

Evaluate a situation by comparing one value in the script to what you expect it might be. The result will be a Boolean: True or false.

- Is equal to **==** compares two values to check if they are the same

- Is not equal to **!=** compares two values to check if they are not the same

- Strict equal to **===** compares two values to verify that both the value and the data type are the same

- Strict not equal to **!==** compares two values to verify that both the value and the data type are different

- Greater than: 8 **>** 3 returns true

- Less than: 5 **<** 9 returns true

- Greater than or equal to **>=**

- Less than or equal to **<=**


_____________________________________________________________
## Logical Operators
The operators used to return the result of multiple comparison operators

**((5 < 12) || (8 >= 2))**

- Logical AND **&&**

- Logical OR **||**

- Logical NOT **!**

______________________________________________________________

## Loops
A loop is block of code that will keep running as long as the condition is true. The most common types of loops are:

- **For loop**; used when the code has to run specific number of times. It uses a counter as a condition

- **While loop**; used when the number of repetitions is unknown

- **Do while loop**; the fundamental difference between this loop and while loop is that the code will run at least once even if the condition evaluates to false

**  A for loop consists of variable initialization, condition, and update.


***Example***

Loop through the indices of an array to collect the car names from the cars array:


>var cars = ["BMW", "Volvo", "Saab", "Ford"];
v/ar text = "";
var i = 0;
while (i < cars.length) {
  text += cars[i] + "<br>";
  i++;
}   

