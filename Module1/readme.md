# Module 1  - Git

This first module is going lead you through the basics of using Git. For some, this might be a refresher. For others, you might ask why do I even need this? Having a source for reference and a place for collaboration should always be encouraged. Git is awesome because there is a lot to it, but you don't neccessarily need a lot to use it. We will be using Github, but know the Git commands aren't particular to it and can be used in Gitlab, Bitbucket, etc.

#### Let's get started.

1. While logged in to Github, click the 'Fork' in the top right. A dialog window should pop-up asking you where to fork it. Select your username and it will start copying into your account. You should now have your very own 'startup' in your account. 
2. We now want to bring down this project to your local computer. To do this, we need to clone the repository.
3. On your computer, open up a terminal, command prompt, shell. Whatever you have.
4. In the prompt, type 'git clone https://github.com/495315836713/startup.git' and hit enter.
5. We now want to switch into this directory, but before we do, let us try out some basic commands:
   A. 'pwd' - present working directory will tell you where you are at in the terminal. 
   B. 'ls' - lists directories and files
   C. 'cd $NAME_OF_DIRECTORY' - changes directory to where you need to go.
   D. 'cd ..' - will take you back one level in your directory
6. Change in to the startup directory. 'cd ./startup'
7. Now go back a folder 'cd ..'
8. Now, type 'cd ./s' and hit the tab button. It should have autocompleted the folder. If it choose the wrong folder, hit tab again until it is ./startup. Hit enter to confirm that is where you want to navigate.
9. See if you can navigate to this page in your terminal and read out this page using the 'cat' command.

#### Now that you have the projects, let us make some edits to it.
1. Navigate back so that you are in the ./startup directory.
2. If you are in Powershell, type 'ls -h' Linux/Mac users type 'ls -alh. Do you see the .git file? You weren't seeing this before because it is a hidden folder. This folder contains all the information required for version control. This is what makes this folder different from regular folders. 
3. There are plenty of ways to organize your development flow. For simplicity, we are going to do branch and merge. 
4. In your terminal, type 'git branch'. The branch should indicate that it is 'main'
5. Create a new branch called 'develop' by typing 'git checkout -b develop'. This should switch you to a new branch. 
6. This branch is completely different from the main branch. Any changes you make here will not affect the main branch. 
7. Let us create a file named TEST with the words 'my first commit'.   echo 'my first commit' > TEST
8. Read out this file using the 'cat' command.
   
