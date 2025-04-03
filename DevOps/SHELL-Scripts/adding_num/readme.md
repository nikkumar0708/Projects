Run an addition operation using the + operator between defined variables and enclose them with $((..)).

ex:-

#!/bin/bash

num1=10
num2=20
sum=$(($num1+$num2))
echo "The Sum is: $sum"


Output:
The Sum is: 30


NOTE:---

[ ... ] (single brackets) are used for string comparisons and conditional checks.

(( ... )) is used for arithmetic expressions.