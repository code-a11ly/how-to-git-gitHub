# “Complete” guide to Git and GitHub
ENGLISH VERSION
By Gabriel Souza Silva



 
### Contents:

######      What is git?
######      What is version control?
######      Pre-git commands – aka Bash commands
######      Git commands
######       - Most used commands
######       - Git commands to interact with GitHub



 
## What is git?
- Git is a free open-source version control system.

## What is GitHub?

- still to add.


## What is version control?
-	The management of changes to documents, computer programs, large websites, and other collection of information.

Terms 
-	Directory -> Folder
-	Terminal or Command Line -> Interface for Text Commands
-	CLI -> Command Line Interface
-	cd -> Change Directory 
-	Code Editor -> Word Processor for Writing Code
-	Repository -> Project, or the folder/place where your project is kept
-	GitHub -> A website to host your repositories online

Git commands
-	clone  -> Bring a repository that is hosted somewhere like GitHub into a folder on your local machine
-	add -> Track your files and changes in Git
-	commit -> Save your files in Git
-	push -> Upload Git commits to a remote repository, like GitHub
-	pull -> Download changes from the remote repository to your local machine, the opposite of push

 

To create and push a new repository and push (with git)
Echo “# repository-name” >> README.md
git init
git add “file_name”
git commit -m “your commit”
git branch -m main
git remote add origin “https://github.com/the ssh link to the GitHub repository”
git push -u origin main

to push an existing directory
git branch -m main
git remote add origin “https://github.com/the ssh link to the GitHub repository”
git push -u origin main


to bring a directory down to your local machine
git clone “https://github.com/the ssh link to the GitHub repository”



## Pre-git commands – aka Bash commands 

    cd “the path”
Change Directory (or folder), changes the directory according to the given
path
                
    ls
List Directory (or folder), gives you a list of the current folder content

    mkdir	“name of the folder”	
Make Directory, it makes one new directory with the given name
                                
    rmdir	name-of-the-folder	
Remove Directory, it removes one existing directory with the 
given name.

    touch new-file-name.smth
creates a new file with the given name

    cat file-name
shows the content of a file in the terminal


## Git commands


    git --version
to check the git version

    git --help
to get access to the git commands

    git config --global user.name “name_that_chose”
to register a user

    git config --global user.email “your_email_on_GitHub”
to register your user email

    git config --global core.editor “the_code_editor”
to assign a code editor


### Most used commands:


    git init
initialize the folder as a git repositorygit

    git add “file_name”
the name of the file that you want to commit (track)

    git commit -m “just_added_the file”
to save a version of the file and then you add a description to it
                    
    git log
to see the commits(saves) that you did in the file

    git log --graph
to see the commits(saves) that you did in the file in a tree like form
                
    git log --graph --all
to see the commits(saves) that you did in all the files
in a tree like form

    git status
shows the status of your directory such as if you had modified a file
and not commited it
            
            
### Git commands to interact with GitHub:


    git push the-https-link-of-your-dierectory
it will push all your commits of your local git repository to the
GitHub reposiory

    git clone the-https-link-of-the-dierectory
it will download all your files from the GitHub repository into
the folder of your local machine

    git pull the-https-link-of-the-dierectory
it will update all your files from the GitHub repository into the folder
of your local machine
                                                
    git branch
shows all the branchs and main as well

git branch
                                            
git diff first-file-name second-file-name

    git merge branch-name
it will make the content of the main the same as
the one in the chosen branch


__NOTE:__ If you are looking for a command line and didn't find it here
I would advise you to look at the "complete" guide. In order to not
make this a big guide and overwhelm the reader (which in not what I
want), I will put all the command lines in the complete guide.





