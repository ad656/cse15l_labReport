# Lab Report #3

**Lab - Copy whole directories with scp -r**

Copying markdown-parse directory onto ieng6

![image](p7.png)

After typing ```scp -r```, the terminal copies the files onto the ieng6 server and saves it there. We are then able to see all the files that were copied under the original command or by typing ```ls```. 


**Running MarkdownParse on ieng6**

![Image](p8.png)

After using ```ssh``` to get onto the ieng6 server, we change the directory to the newly copied over MarkdownParse directory and run the test. The file properly compiles and runs. The failures of the tests are intentional. 

**Combining commands to copy and run in one line**

![Image](p9.png)
![Image](p10.png)

By combining the ```scp```,```;```, ```javac```, and ```java``` calls, we are able to copy the file onto the ieng6 server, compile, and 
run it in one commnad. Since the output was so long, two images are provided to show all of what is outputted. The result at the end is 
the same as the previous part, where there are two intentional failures in the tests. 