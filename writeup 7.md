Module 7: Shell variables 

This module is about getting to know how to use variables in linux. (setting, printing, and using these variables)

The first challenge is about printing variables. I solved it by using the echo command and prepending the variable name with a $. This therefore printed the flag variable.

The next few challenges were mainly about setting variables. To solve this challenge i set the PWN variable to 'COLLEGE'. After setting the variable, I printed the flag using the echo command. This therefore gave me the flag.

The next few challenges are about exporting variables. Here I exported the PWN variable and set it to the value COLLEGE and I set the COLLEGE variable to the value PWN without exporting. After that i did /challenge/run and got the flag.

You can also store outputs of certain commands to a variable using Linux. I solved the challenge by passing the output of /challenge/run to the variable PWN and it contained the flag. 

The last 2 challenges are about reading input and files. I solved it by using the read command to set the PWN variable to the required value (i.e COLLEGE). 
