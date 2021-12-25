# Bash 
GNU nano 6.0               myscrip.sh
#!bin/bash

clear
echo "Hello"
read -p "Please enter your name"
echo "$name">> names.txt
clear
echo -e  "Hello $name\nYour name as been add list."
echo "====================================="
read -p "Enter your password"
echo "$password">> password.txt
clear
echo -e "Congrats!!! you can do"
echo "========================="
echo "Goodbye"
sleep 2
