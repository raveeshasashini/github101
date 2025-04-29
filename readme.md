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