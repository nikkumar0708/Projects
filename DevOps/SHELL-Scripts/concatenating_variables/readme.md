To concatenate multiple variables and store them into a single variable, enclose them with a double quotation (“ ”) and then write the variables within {} consecutively.

Ex:--

#!/bin/bash

# Declaration of variables
name='My name is Tom.'
age='My age is 12.'

# Concatenation
info="${name} ${age}"
echo "Result: $info"
Bash
Output:

Result: My name is Tom. My age is 12.