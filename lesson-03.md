# Lesson #3

**GIT:**
Means sharing code and collaboration, DVCS for the masses, 
Allows multiple developers to work on the same code
VCS: GIT is a Version Control System
Shows a history of changes to your files
Keeos all your project files in one repository

**GitHub:**
Not GIT
A way to share code with others
An online place to store your code
Manage your team's work, version tracking, reviewing changes


**What is a repository?**
- A repository is a collection of files you've told Git to pay attention to
- When making a repository always make sure to add a README.md (for now)
- To get a repository on your computer, you can copy the SSH link (in the code drop down), then you can go to your terminal to open it up: type: git clone LINK_HERE

**Updating from Local To Remote**
- Run command in terminal: git status, which will show you files, if they are red they haven't been added yet.
- Run: git add . to add everything now into the remote, they will now be green if they are added
- Now you need to add a snapshot, git commit -m "Added HTML & CSS" (which adds a message to what update you have made)
- Now you can push it onto github: git push

**Updating For A Whole Team**
- It is best practice to do the command: git pull before every session
- This way you have an up to date version before every session