This project is a simple graphical calculator built using Python's Tkinter library. The calculator allows users to perform basic arithmetic operations such as addition, subtraction, multiplication, and division. It also supports special operations like modulus, and the use of parentheses for complex expressions.

Features
Basic Arithmetic Operations: Add, subtract, multiply, and divide numbers.
Modulus Operator: Calculate the remainder of a division.
Parentheses: Use parentheses to structure complex mathematical expressions.
Floating Point Numbers: Supports operations on decimal numbers.
Error Handling: Displays "Error" for invalid operations such as division by zero.
Enter numbers and arithmetic operations using the buttons.
Use the C button to clear the current input.
Use the = button to evaluate the expression.
The calculator supports the following operations:
Addition (+)
Subtraction (-)
Multiplication (x)
Division (/)
Modulus (%)
Parentheses ((, ))
How it Works
The calculator uses a graphical user interface (GUI) to display an input field where users can enter arithmetic expressions using buttons. The GUI is created with the Tkinter library.

Entry Field: This is where the user's input or expression is displayed.
Buttons: Each button corresponds to a number, operator, or function.
When a button is pressed, its value is appended to the entry field.
When the = button is pressed, the expression is evaluated using Python's built-in eval() function.
Error Handling: If the user inputs an invalid expression (e.g., division by zero), the calculator displays an error message.
