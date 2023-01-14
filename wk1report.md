# Topic: Remote Access (MacOS)

## Step 1: Installing VScode
1. Use this [link](https://code.visualstudio.com/) to go to the VScode website and follow the instructions to install on your device.
2. Once installed (like I have done already!), open VScode. You should see something like the image below. 
* Don't worry if your's is in a different colour. Mine is in dark mode!

![image](https://raw.githubusercontent.com/cheahfulnic/cse15l-lab-reports/main/step1image.png)


## Step 2: Remotely Connecting
1. Open up a new terminal by clicking on Terminal -> New Terminal in the menu bar.
2. Enter the following code (leaving out the $)
> $ ssh cs15lwi23xxx@ieng6.ucsd.edu
* The xxx should be replaced by your own personal id (which can be found using this [link](https://sdacs.ucsd.edu/~icc/index.php))
* The link above should also detail how to change your password for the course-specific account.
* Important tips: Choose 'NO' when asked to change your MyTritonLink password and "YES" when asked to change your course-specific account passwords.
3.  When asked whether you wish to continue connecting to the new server, enter “yes” into the terminal.
4. You will then be prompted to enter your password to your course-specific account. Despite typing it in, you will not be able to see the password (but it’s there!). Click enter.
5. Your computer (the client) should now be connected to the computer in the CSE Basement (the remote server). You should see something like the image below.

![image](https://raw.githubusercontent.com/cheahfulnic/cse15l-lab-reports/main/step2image.png)


## Step 3: Trying Some Commands
1. Go ahead and type in a couple of commands that you’ve learnt up until now. Here are a couple of examples (sourced from the CSE15L teaching staff) if you’re having trouble remembering:
*  `cd`, `ls`, `pwd`, `mkdir`, and `cp`. You can also log out of the remote terminal using `exit` or clicking Ctrl+D.
*  Alternatively (and more specifically):
```
cd ~
cd
ls -lat
ls -a
ls <directory> where <directory> is /home/linux/ieng6/cs15lwi23/cs15lwi23xxx #where the xxx is another student’s username
cp /home/linux/ieng6/cs15lwi23/public/hello.txt ~/
cat /home/linux/ieng6/cs15lwi23/public/hello.txt
```
2. If you’ve done everything right so far, you should get a similar result as the ones below.

![image](https://raw.githubusercontent.com/cheahfulnic/cse15l-lab-reports/main/step3image.png)

3. You’re all set! Enjoy the rest of the quarter!
