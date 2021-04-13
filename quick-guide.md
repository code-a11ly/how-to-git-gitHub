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


git push the-https-link-of-your-dierectory

git clone the-https-link-of-the-dierectory

git pull the-https-link-of-the-dierectory


Git commands to look at
git diff
