Module 5: File Globbing

This module is about globbing. Globbing lets you reference files without typing them all out, or typing out their full paths.

I solved the first challenge by changing my directory to /challenge by not doing it in more than 4 characters. I did this by using globbing by touching a file named challenge and using echo look to find it. Then I used /challenge/run to get the flag.

For the next challenge i had to use ? instead of *. To change the directory i could not use c and 1 in the argument to cd. So by globbing using the ? character i changed the directory to /challenge and used /challenge/run to get the flag.

The next few challenges were a bit tricky. I had to use globbing by using square brackets [] in order to select the files. I did this by changing the directory to the required one and then used globbing.

I did the last challenge by filtering out the unwanted letters by using square brackets []. 

![image](https://github.com/user-attachments/assets/c0aec59a-dbf2-4b84-b7e9-9553bf8d486c)
