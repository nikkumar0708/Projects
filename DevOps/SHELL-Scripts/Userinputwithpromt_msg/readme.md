Read User Input With Prompt Message
The read command used with option -p allows you to prompt a message along with taking user input. You can use echo $(VARIABLE_NAME) to display the user input on the screen.

example:-

#!/bin/bash

read -p "Enter a number:" num
echo “The number is: $num”

Output:

Enter a number: 12
The number is: 12