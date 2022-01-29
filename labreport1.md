# Lab Report 1
**Part 1**


![Image](images/p1.png)
I already had vscode installed from CSE 11, so all I had to do was open a file. As shown, I have an example file open from an assignment from CSE 12. 
Link to download vsCode [link to download vsCode](https://code.visualstudio.com/download)

**Part 2**

![Image](images/p2.png)

After resetting my password, I was able to remotely connect by entering my login and password. After connecting, the terminal shows some information about my connection. We log in by using ``ssh`` + login address and then inputting the password. 

Link to reset password - [link to reset password](https://sdacs.ucsd.edu/~icc/index.php)

**Part 3**
![Image](images/p3.png)
After being able to connect, I tried out some commands such as ```ls```, which lists all the computer files. Another command I tried was ls-a, which will show all files, even hidden ones. 

**Part 4**
![Image](images/p4.png)
After creating a new file(WhereamI.java), I was able to create a copy of it on the server. After copying it onto the server using the ``scp`` command, we can run the ```ls``` command and confirm that the file is indeed present on there. 

**Part 5**
![Image](images/p5.png)

By running the ```ssh-keygen``` command in the terminal, we are able to generate a key to log in without the use of a password. After generating the key, we can safely exit the remote connection and log back in with the key. When logging in with the normal```ssh``` login, I used 49 keystrokes but with the key I only had to use 22 keystrokes to login. 

**Part6**
![Image](images/p6.png)
There are additional ways to run some of the basic commands in terminal in easier ways, such as adding ```ls``` directly to the ssh command to have the list of files appear right after logging onto the server. Other tricks include running multiple commands on one line, seperated with semicolons. 
