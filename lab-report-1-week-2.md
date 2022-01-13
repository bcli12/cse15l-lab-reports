# ieng6 Login Tutorial

**1. Installing VSCode**

* Install VSCode for the appropriate system from the [website](https://code.visualstudio.com/).
* Once you open the application, you should see a similar screen as the one in the screenshot below.

![Image](VSCodeSetup.png)

**2. Remotely Connecting**

* If you're on Windows, install [OpenSSH](https://docs.microsoft.com/en-us/windows-server/administration/openssh/openssh_install_firstuse) to allow connection from your local computer to another computer. Then, look up your [CS15L account](https://sdacs.ucsd.edu/~icc/index.php).
* Open a new terminal in VSCode and type in the following command (id is replaced by your 3 letters):
```
$ ssh cs15lwi22<id>@ieng6.ucsd.edu
```
* Answer `yes` to the following message and enter your UCSD account password. A similar screen should appear now:
![Image](SSH.png)