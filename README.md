# calculator
This program is a simple calculator implemented in Python. It allows users to perform basic arithmetic operations such as addition, subtraction, multiplication, and division.

Here's a summary of how it works:

1. It imports two modules: `clear` from `replit` and `logo` from `art`. The `clear` function is used to clear the console screen, and `logo` presumably contains some art for the calculator logo.

2. Four basic arithmetic functions are defined: `add`, `subtract`, `multiply`, and `divide`, each taking two parameters (`n1` and `n2`) and returning the result of the corresponding operation.

3. A dictionary called `operations` is created, which maps arithmetic operation symbols (`+`, `-`, `*`, `/`) to their corresponding functions.

4. The `calculator` function is defined, which serves as the main logic for the calculator.

5. Inside the `calculator` function, it first prints the logo.

6. It prompts the user to input the first number (`num1`).

7. It then iterates over the keys of the `operations` dictionary and prints them, allowing the user to see which operations are available.

8. It sets up a loop (`while should_continue`) to continuously prompt the user for an operation and the second number (`num2`), and then performs the calculation using the selected operation.

9. After each calculation, it asks the user if they want to continue with the result (`answer`) or start a new calculation.

10. If the user chooses to continue, it updates `num1` with the result of the previous calculation and repeats the loop. If the user chooses to start a new calculation, it clears the screen and calls the `calculator` function recursively to start over.

Overall, this program provides a simple and interactive way for users to perform basic arithmetic calculations.
