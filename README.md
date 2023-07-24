## learning-git

Pratical git commands to learn git


Create a github repository with a README.md file (or any other file)

Go to your projects directory and clone the github repo there

        UserName
        |
        |--------File
        |
        |--------OtheFile
        |
        |--------Projects (You must git clone here)
                 |
                 |------Project A
                 |
                 |------Project B
                 
                 

> git clone https://github.com/{github-url-to-clone-in-your-computer}.git


        UserName
        |
        |--------File
        |
        |--------OtheFile
        |
        |--------Projects (You must git clone here)
                 |
                 |------Project A
                 |
                 |------Project B
                 |
                 |------learning-git
                 
                 
Edit this file and prepare to upload it with these commands (go inside learning-git folder in the command line):


> git status

to see files status

> git add README.md

> git commit -m "README.md was modified"

> git push

Trying to submit this new change, but there's already a new change in the main repository

> git pull

to get that new file in the main repo, and push again.

> git reflog

to see commit history

Change made in github (by colleague)
