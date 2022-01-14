# Week 2 Lab Report

1. Installing VSCode (for Windows)
    * Go to the [VSCode website](https://code.visualstudio.com/) and follow the download instructions.
    * Once download is complete, open VSCode. The screen should look something like this: ![Image1](vschomescreen.png)

2. Remotely Connecting
    * Download [OpenSSH](https://docs.microsoft.com/en-us/windows-server/administration/openssh/openssh_install_firstuse)
        * Check if **OpenSSH Client** and **OpenSSH Server** are installed by going to  
            > Settings > Apps > Apps & Features > Optional Features
        * If not, select **Add a feature** and install both.
        * Once installation finishes, they should both show up in **Optional Features**.
    * Search for your course-specific account in the [Account Lookup](https://sdacs.ucsd.edu/~icc/index.php)
        * Make sure you [reset the password](https://password.ucsd.edu/).
    * Open a new terminal ![Image2](newterminal.png)
    * Enter the following command, writing your course-specific account in the blank.
        ```
        $ ssh cs15lwi22______@ieng6.ucsd.edu 
        ```
    * You will be asked if you are sure you want to continue connecting. If you log on in the future, you will probably not see it again. Type 'yes' in the terminal, then your password when prompted.
        * Your password will be hidden for confidentiality. This is normal!
    * Now, you are connected to the ieng6 server. You should be notified if you logged in successfully with a similar message: ![Image3](successfullogin.png)
        * If the terminal keeps prompting you for your password, make sure you entered it correctly.

3. Trying Some Commands
    * Once you are logged in, you can try some of the commands below:
        * `cd` - change directory
        * `ls` - list files
        * `pwd` - print working directory
        * `mkdir` - make directory
        * `cp` - copy
        * `exit` (or ctrl-d) - log out

        * Here are some sample commands in my terminal: 
        ![Image4](commands.png)           

4. Moving Files with `scp`

5. Setting an SSH Key

6. Optimizing Remote Running
