For passing values as command line arguments, you have to run the script along the values in a sequence. Later access these values using the $ and input sequence number. 

#!/bin/bash
name=$1
age=$2
echo "My name is $name. My age is $age."


Run the script using:
bash var_example5.sh Tom 12

Output:
My name is Tom. My age is 12.



nikhilpatel@07 passing_values_as_a_commandline % ./values_passing.sh Nikhil 25
My name is Nikhil. My age is 25.
nikhilpatel@07 passing_values_as_a_commandline % 