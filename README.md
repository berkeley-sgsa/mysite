
# mysite

Copy of website files for internal use. 

*Document History* 

Created by Alan Aw (`alanaw1`) on Sep 2, 2020.

**What is this for?** 

This repository contains files and data enabling the user to update the UC Berkeley SGSA website. Permission should only be given to maintainers of the website. See instructions below for details on updating the SGSA website. 

**Instructions**

Read the Google doc for details (and examples) on the instructions below. (You should have access to the Google doc.)

1. For first time users, clone this repository and the _berkeley-sgsa.github.io_ repository to your local computer.
2. Else, `git pull` the repository _mysite_ to your local computer.
3. On a terminal/shell of your local computer, go to the directory of _mysite_.
4. (Update locally) Type `hugo server` and edit files locally.
5. (Compile updates) After ending the local update session, type `hugo` to tell Hugo to compile all updates to the "public" folder. 
6. (Update output repo) Copy and paste contents in the "public" folder (not the folder itself!) to your local directory of the _berkeley-sgsa.github.io_ repo.
7. (Push updated output to Github) `git commit` and `push` the updated local directory onto the _berkeley-sgsa.github.io_ repo.
8. (Push updated input to Github) `git commit` and `push` the updated mysite folder onto the _mysite_ repo.

:bulb: Steps 1, 2, 7 and 8 can be performed with a few clicks if you use Github Desktop. Entirely up to you, but just FYI. 

