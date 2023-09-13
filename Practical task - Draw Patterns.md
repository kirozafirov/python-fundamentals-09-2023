# Drow patterns with Python 

Write a Python program that draw various patterns using asterisks ('*') and spaces (' '). The program should take user input to determine the type of pattern, the number of rows, and the direction of the pattern (upward or downward).

# Requirements:

Display a menu to the user with the following options:

1. Draw a Triangle
2. Draw a Rectangle
3. Draw a Pyramid
4. Quit
Based on the user's choice, implement the following pattern types:
---
1. Draw a Triangle: The user should specify the number of rows for the triangle. The triangle can be upward or downward.
Example:
```javascript 
Enter the number of rows for the triangle: 5
Enter 'u' for upward or 'd' for downward: u

*
**
***
****
*****
```
---
2. Draw a Rectangle: The user should specify the number of rows and columns for the rectangle.
Example:
```javascript
Enter the number of rows for the rectangle: 4
Enter the number of columns for the rectangle: 6

******
******
******
******
```
---
3. Draw a Pyramid: The user should specify the number of rows for the pyramid.
Example:
```javascript
Enter the number of rows for the pyramid: 4

    *
   ***
  *****
 *******
```
---
Use loops to generate the patterns based on the user's input.

Handle invalid inputs and provide error messages as needed.

Continue displaying the menu until the user chooses to quit.

```javascript
Pattern Drawing Program

Menu:
1. Draw a Triangle
2. Draw a Rectangle
3. Draw a Pyramid
4. Quit

Enter your choice (1/2/3/4): 1

Enter the number of rows for the triangle: 5
Enter 'u' for upward or 'd' for downward: u

*
**
***
****
*****

Enter your choice (1/2/3/4): 2

Enter the number of rows for the rectangle: 4
Enter the number of columns for the rectangle: 6

******
******
******
******

Enter your choice (1/2/3/4): 3

Enter the number of rows for the pyramid: 4

   *
  ***
 *****
*******

Enter your choice (1/2/3/4): 4

Goodbye!
```

# ®Mario Zahariev - Programing fundamentals course SoftUni
