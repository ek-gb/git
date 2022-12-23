# **Main Git Commands Guide**

## **git init**
This command is used to start a new repository.

    git init [repository name]

***
## **git add**
This command adds a file to the staging area.

    git add [file]

***
## **git commit**
This command records or snapshots the file permanently in the version history.  

    git commit -m "[ Type in the commit message]"

or

    git commit -a

This command commits any files you’ve added with the git add command and also commits any files you’ve changed since then.
***
## **git diff**
This command shows the file differences which are not yet staged.

    git diff
or

    git diff –staged

This command shows the differences between the files in the staging area and the latest version present.

or

    git diff [first branch] [second branch]

This command shows the differences between the two branches mentioned.
***
## **git status**
This command lists all the files that have to be committed.

    git status

***
## **git log**
This command is used to list the version history for the current branch.

    git log
or

    git log –follow[file]

This command lists version history for a file, including the renaming of files also.
***
## **git show**
This command shows the metadata and content changes of the specified commit.

    git show [commit]

***
## **git checkout**
This command is used to switch from one branch to another.

    git checkout [branch name]

or

    git checkout -b [branch name]

This command creates a new branch and also switches to it.
***
## **git merge**
This command is used to merge another branch to switched branch.

    git merge [branch name]
***
## **git clone**
Makes a clone of the repository at the specified URL:

    git clone URL
***
## **git remote add**
Links a local repository and an online repository at the specified URL:

    git remote add origin URL
***
## **git push**
Pushes local changes to the specified branch of the online repository:

    git push origin branch_name
***
## **git pull**
Pull changes from the online repository into local repository:

    git pull origin branch_name
***
## **git fetch**
Only downloads new data from a remote repository - but it doesn't integrate any of this new data into your working files.

    git fetch
***
## **git remote**
You can see the current remote repositories linked to your local git repo by typing:

    git remote -v

Next to switch to a new github remote repository:

    git remote set-url origin git@github.com:USERNAME/REPO.git
*** 