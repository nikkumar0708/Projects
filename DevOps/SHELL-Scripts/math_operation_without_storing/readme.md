To perform multiple mathematical operations without storing them in a separate variable, write the operations inside echo

#!/bin/bash

read -p "Enter a number: " num1
read -p "Enter a smaller number: " num2

echo "Addition: $(($num1 + $num2))"
echo "Subtraction: $(($num1 - $num2))"
echo "Maultiplication: $(($num1 * $num2))"
echo "Division: $(($num1 / $num2))"


output:-
nikhilpatel@07 math_operation_without_storing % ./math_operations.sh 
Enter a number: 5
Enter a smaller number: 3
Addition: 8
Subtraction: 2
Maultiplication: 15
Division: 1
nikhilpatel@07