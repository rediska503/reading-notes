Operators
## JavaScript has the following types of operators. 

- Assignment operators

- Comparison operators

- Arithmetic operators

- Bitwise operators

- Logical operators

- String operators

- Conditional (ternary) operator

- Comma operator

- Unary operators

- Relational operators

>JavaScript has both binary and unary operators, and one special ternary operator, the conditional operator. A binary operator requires two operands, one before the operator and one after the operator:

operand1 operator operand2
For example, 3+4 or x*y.

A unary operator requires a single operand, either before or after the operator:

operator operand
or

operand operator
For example, x++ or ++x.

Assignment operators
An assignment operator assigns a value to its left operand based on the value of its right operand. The simple assignment operator is equal (=), which assigns the value of its right operand to its left operand. That is, x = y assigns the value of y to x.

## Comparison operators

      A comparison operator compares its operands and returns a logical value based on whether the comparison is true. The operands can be numerical, string, logical, or object values. Strings are compared based on standard lexicographical ordering, using Unicode values. In most cases, if the two operands are not of the same type, JavaScript attempts to convert them to an appropriate type for the comparison. This behavior generally results in comparing the operands numerically. The sole exceptions to type conversion within comparisons involve the === and !== operators, which perform strict equality and inequality comparisons. These operators do not attempt to convert the operands to compatible types before checking equality.

## Arithmetic operators
      An arithmetic operator takes numerical values (either literals or variables) as their operands and returns a single numerical value. The standard arithmetic operators are addition (+), subtraction (-), multiplication (*), and division (/). These operators work as they do in most other programming languages when used with floating point numbers (in particular, note that division by zero produces Infinity).