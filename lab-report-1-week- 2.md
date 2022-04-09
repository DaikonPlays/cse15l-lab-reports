![Image](screenshot.png)
# How to Log into a Course-Specific Account on ieng6
Disclaimer: I got a new Macbook between the lab and the lab report, so the first step is for Mac while the rest is for Windows
## Step 1: Installing VScode 
![Image](VSCode.png) 

To install VSCode, simply go to this [VSCode download link](https://code.visualstudio.com/) and click the Download Mac Univeral button. Then, just open the installer and drag the application to the application folder. 

## Step 2: Remotely Connecting

For Windows, you must install OpenSSH Client and OpenSSH Server by opening Settings, select Apps > Apps & Features, then select Optional Features. 

Then, on VSCode, type in 

$ ssh cs15lsp22zz@ieng6.ucsd.edu

and replace zz with the letters to your course-specific account.

![Image](RemoteConnecting.png) 

Type yes to the options given and you should get this message in the terminal. 

## Step 3: Trying Some Commands

Try running these commands:
