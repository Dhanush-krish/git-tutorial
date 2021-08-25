
Learning git basics

Git Visualizer : https://git-school.github.io/visualizing-git/


Cheat Sheet
.....................................................................................................................................................................

Git - History
    git log : shows all the commit
    git log --oneline: show the commit id and commit message
    git log --graph: shows graphical representation of commit
    git log --oneline --graph --all: graphical representation of all the branches
    git log -p: Prints full details of each commit
    git log --grep-reflog=<pattern>: Shows the list of commits when commit message matches regular expression pattern
    git log --follow ./path/to/filename: Shows the history for the current file
    git show <commit_id>: Outputs content changes of the specified commit
    git diff --color-words: Output has only the color-coded words that have changed
    git diff –staged: Shows the file differences between staging and the last committed version
    git diff .path/to/file: Shows changes in a file compared to the previous commit

Git - Branch
    git branch: Prints the current working branch
    git branch -a: Lists all the branches
    git checkout <branch>: switches to the branch
    git checkout -b <branch>: creates a new branch and switch to it
    git branch -m <old_name> <nem_name>: renaming local branch
    git push :<old_name> <new_name>:  renaming remote branch
    git branch -d <branch_name>: deleting local branch
    git branch -D <branch_name>: forcefully deleting a branch
    git push origin -d <branch_name>: deleting remote branch

