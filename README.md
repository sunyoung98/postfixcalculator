# postfixcalculator

Write a C++ program that inputs general real-numerical expressions line by line and then outputs their results. “EOI” means the end of input.
Only non-negative real numbers can be input as operands.
Three types of parentheses can be input.
“( )”, “{ }”, and “[ ]”
Only 4 binary operators can be used as operators:
*, /, +, and -
* and / have higher precedence than + and -.

Notice that, for example, 13.0/5.0 = 2.6 and 13.2+5.3 = 18.5.
Write a C++ program that inputs general real-numerical expressions line by line and then outputs their results. “EOI” means the end of input.
The result is always a real number and it can be a negative value.
Round off to the nearest thousandth. (12.34567  12.346) 
When exceptions such as unbalanced parentheses or “/0.0” occur, print “Error!: {reason}\n” and process next input lines.
Unbalanced parentheses  “Error!: unbalanced parentheses\n”
“###/0.0”  “Error!: divided by zero\n”
