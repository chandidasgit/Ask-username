# username.sh
#!/bin/bash

clear
echo "Hello"
read -p "Please Enter Your Name: " name
echo "$name">>names.txt
clear
echo -e "Hello $name\nYour name as been added to the list."
echo "======================="
cat names.txt

echo "======================="
echo "Goodbye $name"
sleep 2

