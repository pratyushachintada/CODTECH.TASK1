NAME : CHINTHADA PRATHYUSHA
ID : CT08DS1243
MENTOR : SRAVANI
DURATION : 25/5/2024 TO 25/6/2024
COURSE : JAVA PROGRAMMING
DURATION : 
          The Java program `BasicCalculator` is designed to function as a simple interactive calculator capable of performing arithmetic operations based on user input. Here’s a detailed description of how the program works and its components.

### Program Structure and Functionality

1. **Imports and Class Declaration**:
   - The program starts with necessary imports (`Scanner` for input reading) and defines a single class `BasicCalculator`.

2. **Main Method**:
   - The `main` method initializes variables `num1`, `num2` to store user-entered numbers and creates a `Scanner` object (`sc`) to read input from the console.
   - It prompts the user to input two numbers (`num1` and `num2`), which are read using `sc.nextDouble()`.
   - Next, it prompts the user to input an operator (`+`, `-`, `*`, `/`) which is read as a `char` using `sc.next().charAt(0)`.

3. **Arithmetic Operations**:
   - A `switch` statement is used to determine the operation based on the operator input (`op`).
     - **Addition (`+`)**: Adds `num1` and `num2`.
     - **Subtraction (`-`)**: Subtracts `num2` from `num1`.
     - **Multiplication (`*`)**: Multiplies `num1` and `num2`.
     - **Division (`/`)**: Divides `num1` by `num2`. Note: Division by zero is not explicitly handled in this basic implementation.
   - If an invalid operator is entered, the program prints an error message indicating incorrect input.

4. **Output**:
   - After performing the operation, the program prints the result in the format `num1 operator num2 = result`.
   - It provides clear feedback to the user about the operation performed and the calculated result.

### Program Flow and User Interaction

The program's flow begins with prompting the user for numeric inputs and an operator, which facilitates interactive operation. The use of `Scanner` ensures that inputs are read dynamically, allowing for flexible interaction without predefined values. The `switch` statement efficiently selects and executes the appropriate arithmetic operation based on the user's choice of operator, enhancing program logic and user experience.
 
  Conclusion :

In summary, the `BasicCalculator` Java program exemplifies fundamental principles of input handling, decision making with `switch` statements, and output formatting. It serves as an accessible tool for basic arithmetic computations, demonstrating core concepts of Java programming such as variable declaration, user input management, and conditional execution. This program is ideal for learning purposes and provides a solid foundation for expanding functionality through additional operations or error handling mechanisms.
