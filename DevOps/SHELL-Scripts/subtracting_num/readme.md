Subtract two numbers using the "-" operator between defined variables and enclose them with "$(())".

NOTE:---

[ ... ] (single brackets) are used for string comparisons and conditional checks.

(( ... )) is used for arithmetic expressions.


EX:-

#!/bin/bash

num1=30
num2=20
dif=$(($num1-$num2))

echo "The difference is: $dif"

Output:
The difference is: 10

