#Commandline with aliases 
These are the files that enable you configure the windows command line with alias. Used in combination with [Chocolately and Git for Windows](http://www.jamessturtevant.com/posts/5-Ways-to-install-git-on-Windows/#using-chocolatey) you have a decent cmd experience.

## Setup
1. Open Regedit and navigate to ```HKEY_CURRENT_USER\SOFTWARE\Microsoft\Command Processor```.
2. Add the key ```Autorun``` with value to path of files (etc ```C:\\aliases\\shell-startup.cmd```)

Now when you open any command prompt you will have the defined aliases.  Combined with ```Windows Key + X + C``` and you have prompt up and running when you need it.