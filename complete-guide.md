# “Complete” guide to Git and GitHub
ENGLISH VERSION
By Gabriel Souza Silva



 
Introduction - What you will find here ?

 
What is git?
- Git is a free open-source version control system.
What is GitHub?
I'm glad you asked! Many people come to GitHub because they want to contribute to open source projects, or they're invited by teammates or classmates who use it for their projects. Why do people use GitHub for these projects?
At its heart, GitHub is a collaboration platform.
From software to legal documents, you can count on GitHub to help you do your best work with the collaboration and security tools your team needs. With GitHub, you can keep projects completely private, invite the world to collaborate, and streamline every step of your project.
GitHub is also a powerful version control tool.
GitHub uses Git, the most popular open source version control software, to track every contribution and contributor to your project--so you know exactly where every line of code came from.
GitHub helps people do much more.
GitHub is used to build some of the most advanced technologies in the world. Whether you're visualizing data or building a new game, there's a whole community and set of tools on GitHub that can get you to the next step. This course starts with the basics, but we'll dig into the rest later!


What is version control?
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


# Quick Guide to Git and GitHub

If you already read the full guide or know about Git and GitHub, and need to just revise the commands, then this is for you!

Pre-git commands – aka Bash commands 

cd “the path” 	// Change Directory (or folder), changes the directory according to the given
                // path
                
ls	// List Directory (or folder), gives you a list of the current folder content

mkdir	“name of the folder”	// Make Directory, it makes one new directory with the given
                                // name
                                
rmdir	“name of the folder”	// Remove Directory, it removes one existing directory with the 
                                // given name.

touch new-file-name.smth	// creates a new file with the given name

cat file-name	// shows the content of a file in the terminal


Git commands


git --version	// to check the git version

git --help	// to get access to the git commands

git config --global user.name “name_that_chose”		// to register a user

git config --global user.email “your_email_on_GitHub” 		// to register your user email

git config --global core.editor “the_code_editor”		// to assign a code editor


Most used commands:


git init		// initialize the folder as a git repositorygit

git add “file_name”	// the name of the file that you want to commit (track)

git commit -m “just_added_the file”	// to save a version of the file
					// and then you add a description to it
                    
git log	// to se the commits(saves) that you did in the file


git status  // shows the status of your directory such as
            // if you had modified a file and not commited it
            
            
Git commands to interact with GitHub:


git push the-https-link-of-your-dierectory      // it will push all your commits of
                                                // your local git repository to the
                                                // GitHub reposiory

git clone the-https-link-of-the-dierectory      // it will download all your files
                                                // from the GitHub repository into
                                                // the folder of your local machine

git pull the-https-link-of-the-dierectory       // it will update all your files
                                                // from the GitHub repository into
                                                // the folder of your local machine
                                            
git diff




NOTE: If you are looking for a command line and didn't find it here
I would advise you to look at the "complete" guide. In order to not
make this a big guide and overwhelm the reader (which in not what I
want), I will put all the command lines in the complete guide.





