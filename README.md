# Automation of checking interfaces status of cisco 2960 switches
This repository contains script working with cisco 2960 access layer switches on local network, using ssh coonection. It sends command "show interface status" to all switches, specified in the list and checks if interfaces have problems ("disable" or "err-disable" status). In this case it puts result of the command in .txt file 
