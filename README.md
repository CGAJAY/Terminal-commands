# Git Commands

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

### git branch -d <branch_name> - Delete the specific branch.
	This deletes the specific branch even if it has unmerged changes.

### git branch -m <new_branch_name> - Used for renaming branches.
	Renames the current branch I am logged in.

### git branch -m <old_branch_name> <new_branch_name> - Used for renaming branches.
	Renames the branch even if it's not my current branch
	
### mkdir - used to create a directory.
			* eg. mkdir src - creates a folder called src

### touch - used to create a file.
			* eg. touch index.html - creates a html file called index.

  













