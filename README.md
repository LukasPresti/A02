# A02

GIT Tutorial

Step 1: Open your browser and go to (https://git-scm.com/download/win)
Step 2: Click on the top link that says "Click here to download," then run through the installer.
Step 3: Once the installation is complete, open the application and type the following commands:

git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"

Step 4: To confirm your setup, type:

git config --global --get user.email
git config --global --get user.name

Step 5: Type git init to create a repository.
Step 6: Connect a remote repository by typing:

git remote add origin https://github.com/username/repository.git

(Replace https://github.com/username/repository.git with your actual repository link.)

Step 7: Add files to the staging area with:

git add file

or type git add . to add all files.

Step 8: Commit your changes with:

git commit -m "Put your message here"


Github Tutorial

Step 1: Open your browser and go to (https://github.com/)
Step 2: Sign up for an account by clicking on the upper right-hand corner of the website.
Step 3: Refer to the Git installation tutorial as Github operates on Git.
Step 4: Create a repository by clicking on your profile -> Your repositories -> New.
Step 5: This repository is your project. Add a README file by checking the "Add a README file" box to provide a brief explanation of your project.
Step 6: To add code to your project, click Add file -> Upload files, then drag and drop the files of your choice.
Step 7: Ensure you click "Commit changes" to save any edits you make.

Source: DevMountain: What is GitHub and How Do You Use It?

Webstorm Tutorial

Step 1: Copy and paste this URL into your browser. https://www.jetbrains.com/webstorm/
Step 2: Click the big download button, then proceed to run through the installer.
Step 3: When you open the application, you will need to create an account and choose a pricing plan (or start a free trial).
Step 4: Start a new project and select the programming language you want to code in.
Step 5: Right-click on the project folder and click on New -> whichever file you want to create.
Step 6: When you are done editing, click the three bars in the top left and save the project.
Step 7: The arrow in the bottom left part of the screen (or ALT + 4 for shortcut) will run the code to test if it works.
Step 8: If you are writing an HTML page, hover over your code and click on the browser icon to view it in the webpage.


TERMS

Branch - a way to safely fix bugs by isolating your work from your respository to a safe environment to avoid accidently breaking your code
Clone - this copies a respository and makes a new copy of of the respository in a new directory at a new location
Commit - this is a revision, a commit saves your work
Fetch - This is a command that downloads commits, files and refs from a remote respository into the local one
GIT - This is an open source version control system that allows developers to work on projects together and keep track of revisions while properly merging code changes
Github - This is the webbased interface that uses GIT, it allows users to publish code, revise code, and allows developers to simultaneously work on code projects
Merge - This allows for a forked history to merge back together again. That is two independant git branches into one single branch
Merge Conflict - This is when two people edit the same line of code in the same file or someone edits a file while someone else deletes the file
Push - The command uploads local respository content commits to a remote respository
Pull - This command downloads content from a remote respository and updates the local respository with that content
Remote - This is to refer to a remote respository which is usually hosted on a server accessible for anyone on the local network
Respository - The place where any and all project files are stored as well as revision history
