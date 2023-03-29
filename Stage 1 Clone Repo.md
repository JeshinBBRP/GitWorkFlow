Step 1
- Install Visual Studio Code https://code.visualstudio.com/Download

Step 2
- Install Git for Windows Setup https://git-scm.com/downloads
- Advise you to select Windows Explorer Integration > Git Bash Here > Git GUI Here > all options below minus Git Bash Profile
- Choosing default editor used by Git > drop down menu > Use Visual Studio Code as Git's default editor
- Select overrirde the default branch name for new repositories > type main in the text field
- Select Git from the command line and also from 3rd-party software
- Select Use bundled OpenSSH
- Select Use the OpenSSL library
- Select checkout as-is, commit as-is
- Select Use MinTTY (the default terminal of MSYS2)
- Select Default
- Select Git Credential Manager
- Enable file system caching

Step 3
- Open Visual Studio Code
- Select the overlapping pages icon (Explorer)
- Select the open folder option
- Create or Select folder you want to store files downloaded from GitHub (mine is desktop\Repos>

Step 4
- Go to view
- Select Terminal
- At bottom of screen the Terminal will appear
- Open web browser and go to https://github.com/JeshinBBRP/GitWorkFlow
- Within the  repo click the green < > CODE button
- Select HTTPS and copy the line
- In the visual studio terminal type git clone <b>paste HTTPs line you copied</b>
- Login to github via pop up

Step 5
- Top left you will see a new folder from github
- Right click folder and select open integrated terminal
OR
- in terminal type cd <folder-name-here>


You have successfully cloned the repo from github, created your own branch, and can now make changes to the branch as needed. You can now make txt code changes from visual studio code or if you update the repo manually by moving new files/folders in or replacing them it will display in your visual code studio as updated. When you have finished follow the second stage of instructions for taking the edits from your local machine and merging them back into github where they can be pushed onto the dev server itself.
