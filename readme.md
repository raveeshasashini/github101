Basic Git Commands....

1.Initialize a Git repository
    # git init

2.Check the status of your repository
    # git status

3.Stage a specific file for commit
    # git add <filename>

4.Stage all changes for commit
    # git add .

5.Commit changes with a message
    # git commit -m "commit message"

6.Rename the default branch from master to main
    # git branch -m master main

7.View commit history
    # git log

8.Restore a file from a previous commit (using commit ID)
    # git checkout <commit-id> -- <filename>
(Note: Cleaned/previous versions of files are saved in Git history.)

9.Switch back to the latest version (e.g., main branch)
    # git checkout main

 10.Create a new branch 
    # git branch <branch_name>

 11.Switch to the  branch
    # git checkout<branch_name>      
12.Create and Switch to a New Branch
    #git checkout -b <branch_name>

 14.Branch Management
    #git branch
    
    Delete a branch: git branch -d <branch-name>(merged changes)
                     git branch -D <branch-name>(if unmerged)

    Rename a branch:git branch -m <new name>#rename current branch
                    git branch  -m <old-name> <new-name>

    create a new branch starting from an existing branch: git branch <new-branch-name> <existing-branch-name>