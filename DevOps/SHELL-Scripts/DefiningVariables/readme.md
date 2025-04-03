Variables in shell scripting are containers for storing necessary information. In Bash Script, declare a variable by assigning a value to its reference by = operator. Furthermore, print the assigned values using echo $(VARIABLE_NAME).

The syntax for Variables in Shell Scripting is given below:

VARIABLE_NAME=VALUE


The rules for Variables in Shell Scripting are as follows:

Use the equal sign (=) to assign values to variable names.
Variable names are case sensitive i.e. ‘A’ and ‘a’ are different.
To refer to a variable use the dollar sign ($) e. $VARIABLE_NAME.
While updating/changing the variable values use only the variable name with the assignment operator(=) i.e. VARIABLE_NAME= NEW_VALUE.
No need to define variable type while declaring variables.
Enclose multiple words or string values within Single Quote (‘ ‘) to consider all characters as input.