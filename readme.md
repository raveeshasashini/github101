Basic Git Commands....

Initialize a Git repository
    git init

Check the status of your repository
    it status

Stage a specific file for commit
    git add <filename>

Stage all changes for commit
    git add .

Commit changes with a message
    git commit -m "commit message"

Rename the default branch from master to main
    git branch -m master main

View commit history
    git log

Restore a file from a previous commit (using commit ID)
    git checkout <commit-id> -- <filename>
(Note: Cleaned/previous versions of files are saved in Git history.)

Switch back to the latest version (e.g., main branch)
    git checkout main