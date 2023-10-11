**Tutorial on WebStorm, Git, GitHub**

Part 1: Driections on WebStorm

Step 1: Installing and Setting Up WebStorm 

1. Download WebStorm by going to the website: (https://www.jetbrains.com/webstorm/download/)
2. Using the instruction the install the applications to your device
3. Launch WebStorm and activate it using your JetBrain account

Step 2: Configuring Git on WebStorm 
1. Launch the WebStorm application and open the project you want to work on
2. Configure Git by going to version control. (For Mac you can do this by pressing command and , together). Make sure that the excutable path is correctly set.
3. Configure GitHub by going to version control and add your GitHub account. 

Part 2: Using Git for Version Control

Step 1: Configuring Git 
1. Make sure Git is installed on your system
2. Configure Git by opening up the terminal and run the commands:
   * git config -- global user.name " Your Name"
   * git config -- global user.email " Your Email"

Step 2: Creating a Git Repository 
1. Create a New Directory by running the commands:
    * mkdir my_project
    * cd my_project
2. Initialize a Git Repository by running the commands:
    * git init
3. To make changes to the files run the following commands:
    * git add .
    * git commit -m " Initial Commit"

 Part 3: Utilizing GitHub for Collabarations

 Step 1: Create a Repository on GitHub 
 1. Set up a account a account on GitHub and Login
 2. Create a new repository on GitHub by selecting the new button on the top right corner, then using the prompt 
    shown create the new repository.

 Step 2: Pushing to GitHub 
 1. Link local repository to GitHub by following the steps on GitHub repository creation
 2. Push local changes to Github by running the commands:
     * git remote add origin <repository_url> 
     * git branch -M main 
     * git push -u origin main 


Glossary:
1. Branch: A different line of development that basically allows you to continue to work on a feature or fix issues without effect the main codebase. 
2. Clone: Making a copy of a repository to work on it on a local machine.
3. Commit: Saves changes to the local repository with a message describing it. 
4. Fetch: Grabs the most recent changes from a remote repository without merging them.
5. Git: A version control system that allows for tracking of changes in source code. 
6. GitHub: A platform that is web-based used for hosting and collbarating on Git repositories. 
7. Merge: Putting changes from different branches into each other.
8. Merge Conflict: When Git is unable to resolve differences in a situation automatically during code changes that occur during a merge. 
9. Push: Putting up your local commits to an area such as a remote repository where others are able to gain access to it.
10. Pull: Fetching and merging the most recent changes occuring from a remote repository to your local repository. 
11. Remote: When a repository is hosted on a server such as Github and is able to be accessed by others.
12. Repository: An area where versioning information for projects and other files are stored. 

References: 
1. JetBrain Download Webstorm: (https://www.jetbrains.com/webstorm/download/)
2. Git Information: (https://git-scm.com/about)
3. GitHub: (https://docs.github.com/)
4. WebStorm Tutorial: (https://youtu.be/bTAWd6hxVtI?feature=shared)


