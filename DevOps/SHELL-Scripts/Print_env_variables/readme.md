Print Environment Variable Using Bash Script

You can store an Environment Variable like other variables and print it using ${!..} syntax.

#!/bin/bash
read -p "Enter an Environment Variable name:" var
echo "Environment:${!var}"

Output:

nikhilpatel@07 Print_env_variables % ./print_env_variables.sh
Enter an Environment Variable name:HOME
Environment:/Users/nikhilpatel
nikhilpatel@07 Print_env_variables % 
