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
                    
 ** git restore is used to restore or discard the uncommitted local changes of files
            $ git restore Names.txt
            
    Unstage a file from the staging area
            $ git restore --staged Names.txt
    
   
