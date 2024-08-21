# Implementation of Calcualtor Application Using UART in Embedded C:
# Introduction:
- This project is implemented using hardware communication protocol i.e UART protocol.
- Embedded C is used to implement this protocol
# Features:
- It allows one to give arithmetic string expression as input.
- And the result is displayed after evaluating it according to the rules of arithmetic
# Working:
1. Break down the string into individual tokens (numbers, operators, and parentheses).
2. Convert to Postfix Notation: The infix expression (standard arithmetic notation) is converted to postfix notation (Reverse Polish Notation).
3. Use a Stack for Evaluation:
    + Push numbers and operators onto this stack, ensuring to respect operator precedence and associativity.
4. Evaluate the Expression:
   + Operator Precedence: Ensure that operators with higher precedence (like multiplication and division) are evaluated before those with lower precedence (like addition and subtraction).
5. Final Calculation: After processing all tokens, the stack should contain the final result of the expression.
# Test file:
- Calculator_Application_Version_3.o.hex:
  
