# Git Commands

	If we have a file that we do not want to track, we just put it inside the .gitignore file. .gitignore file contains a list of configurations that affects the behavior of git commands.

### git config --global user.name "YOUR NAME"
	Sets username used by Git to identify the user

### git config --global user.email "YOUR EMAIL"
	Sets email used by Git to identify the user

### cd - used to navigate to a directory. Takes an arguement of directory file path.
  				* eg. cd desktop -navigates to desktop.

### git init - initializes a new git repo in your local machine. That's when you want to place a project under revision control.

### git branch - lists all the branches in my local repo. Marks the current branch with an asterick(*).

### git branch <branch_name> - creates a new branch, To start adding commits to it, I need to select it with (git checkout) and then use the standard git add and git commit.
	* <branch_name> - name of the branch I want to create 

	branches are just pointers to commits. When I create a branch all git does is create a new pointer, it doesn't change the repo. The repo history remains the unchanged. All I get is a new pointer to the current commit.

### git checkout -b <branch_name> - Creates a new branch and switch to it in one step.
	* git checkout - used to switch branches.
	* -b - used to create a new branch. Stands for "create branch"
	* <branch_name> - name of the branch I want to create 
	
### git checkout <branch_name> - Switches to a different branch.

### git branch -d <branch_name> - Delete the specific branch.
	This is a safe way in that git prevents me from deleting the branch if it has unmerged changes.

### git branch -D <branch_name> - Delete the specific branch.
	This deletes the specific branch even if it has unmerged changes.

### git branch -m <new_branch_name> - Used for renaming branches.
	Renames the current branch I am logged in.

### git branch -m <old_branch_name> <new_branch_name> - Used for renaming branches.
	Renames the branch even if it's not my current branch
	
### mkdir - used to create a directory.
			* eg. mkdir src - creates a folder called src

### touch - used to create a file.
			* eg. touch index.html - creates a html file called index.

### git remote -v 
     checks for present link b2n local repo and remote repo

### git remote add upstream <upstream-url> 
	  creates link b2n local repo and original repo

### git pull upstream <branch-name> 
		 fetches from the original upstream repository, updating your remote-tracking branches, and merging any changes into your local branches 

### git rm 
		removes files from both the working directory and the Git index (also known as the staging area). When you use git rm, Git removes the specified files from your working directory and stages their removal in the index. This means that the files will be deleted from both your filesystem and the Git repository history when you commit the changes.

### git rm --cached
		 removes files only from the Git index (staging area), leaving them intact in your working directory. When you use git rm --cached, Git removes the specified files from the index/staging area but leaves them untouched in your working directory. This means that the files are no longer tracked by Git, but they remain in your filesystem. It's commonly used when you want to stop tracking files that were previously added to the repository but you still want to keep them locally.

### git config alias
	helps us to create shortcuts.
	So if we wanted to type git st and have it function like git status, we would type git config alias.st status. Now we can type git st and have the same output as if we typed git status.

	If you would like your alias to be a part of your global configuration, add the --global command after git config. For example, to alias git i to git init globally, you would type git config --global alias.i init.

### git log
	lists all the commits made


  













