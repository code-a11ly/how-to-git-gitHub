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







