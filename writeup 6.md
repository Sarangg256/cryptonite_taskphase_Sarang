Module 6: practicing piping 

This module is about the input and output redirection.

For the first few challenges I used the echo command to redirect an output to a certain file and then catted those files to print the flag. 

The third challenge also showed how we can redirect input in append mode using >> instead of >. I solved this challenge using the logic given. I had to use >> instead of > as trunciation mode would overwrite the first file and the flag would be lost.

In the fourth challenge, I had to redirect errors by redirecting the out of /challenge/run. 

I also learned how to grep errors using the >& operator. For this challenge, I grepped the standard error in order to get the flag. 

For the grepping live output challenge, /challenge/run gave a lot of lines of text which also had the file. I used the grep command in order to get the flag from it. 

I also learned how to redirect input from programs using < operator. I redirected the PWN file to /challenge/run with the value as COLLEGE and solved the challenge. 

![image](https://github.com/user-attachments/assets/fd4038ef-aa90-4c86-8823-749aab016d31)
