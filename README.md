# GIT-Tutorial

SCM- Source Control Management
    - Track modification to source code repo
    - It trackes a running history of changes to a code base and helps resolve conflicts when merging updates from multiple contributors.
    
Benefits:
    - Work together
    - Collaborate with other people
    - Verion history
    - Generate release notes 
    - Back up code
    
    
VCS- Version Control System
    - Saving the history of the project 
    - Maintaining the histrory of the project

GIT- Git is a distributed revision control and source code management system with an emphasis on speed. Git was initially designed and developed by Linus Torvalds for        Linux kernel development. Git is a free software distributed under the terms of the GNU General Public License version 2.

    - Git is a version control system.
    - Git helps you keep track of code changes.
    - Git is used to collaborate on code

GitHub  
    - GitHub is a code hosting platform for collaboration and version control
    - Its webbased git repo which provides web interface to upload files.
    
    
    
    Step by Step executing git basics commands
    
    1. Create directory
            $ mkdir project
            
    2. Change diretory
            $ cd project
            
    3. Create a new blank repository and make an existing project as a Git project
            $ git init
            
    4. Show all files and subdirectories in the current directory
            $ ls -a
            
    5. Create a text file using vi editor
            $ vi Names.txt
           
    6. Display the state of the repository and staging area.
            $ git status
            
    7. Add changes in the working directory to the staging area
            $ git add .  ( Note:   . -> adds all the files )
            
    8. Performs a commit, and the -m " message " adds a message
            $ git commit -m "Names.txt ia added"
            
    9. git clone: This command is used to clone an existing Git repository from a remote source
            $ git clone https://github.com/user/my-project.git
            
    10. git push: This command is used to push the committed changes in the local repository to the remote repository
            $ git push origin
          
    11.  git pull: This command is used to pull the changes from the remote repository to the local repository
            $ git pull origin
            
    12. git branch: This command is used to list, create, or delete branches in a Git repository
            $ git branch New_Branch
            
    13.  git checkout: This command is used to switch between branches in a Git repository
            $ git checkout main
          
    14.  git log: This command is used to display the commit history of a Git repository.
            $ git log
            
    15. git stash: This command is used to save the local changes in a Git repository without committing them.
            $  git stash 
            
    16.  git tag: This command is used to add tags to specific commits in a Git repository
            $ git tag v1.0
            
    17. git merge: This command is used to merge one branch into another branch in a Git repository.
            $ git merge New_Branch
            
    18. git reset: This command is used to reset the state of a Git repository to a previous commit.
            $ git reset HEAD
            
    19. git config: This command is used to configure settings for a Git repository. For example, you  can use the following command to set 
                    the user name and email address for the repository
            $ git config --global user.name "Sudheer"
            $ git config --global user.email "sudheer@gmail.com"
            
    20.  git remote: This command is used to manage the remote repositories for a Git repository. For example, you can use the following command 
                     to add a new remote repository called origin
            $ git remote add origin git_url
            
    21.  git fetch: This command is used to download the objects and references from a remote repository to the local repository
            $ git fetch main
            
    22.  git blame: This command is used to view the commit history for each line of a file in a Git repository
            $ git blame file.txt
          
    23. git show: This command is used to show the details of a specific commit in a Git repository. 
            $ git show New_Branch
            
    24. git grep: This command is used to search for a specific pattern in the files in a Git repository.
            $ git grep foo file.txt
            
    25. git rebase: This command is used to reapply the commits from a branch on top of another branch in a Git repository 
            $ git rebase main new_branch
            
    26. git mv: This command is used to move or rename a file in a Git repository
            $ git mv f1.txt f2.txt  ------ rename the file name
            $ git mv f1.txt Move    ------ Move the file f1.txt into Move directory
            
    27. git ls-files: This command is used to list the files in the index and the working tree of a Git repository.
            $ git ls-files
                    
 ** git restore is used to restore or discard the uncommitted local changes of files
            $ git restore Names.txt
            
    Unstage a file from the staging area
            $ git restore --staged Names.txt
    
 ** git stash command saves the previously written code and then goes back to the last commit for a fresh start
            $ git stash      
            $ git stash pop  // Bringing back to staging area
            $ git stash clear
            
            
 ** The crontab is used to automate all types of tasks on Linux systems
