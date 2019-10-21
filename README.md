# Hello-GitHub
Repository for GIT Basic(s), first pull request(s), first contribution(s)

## 'How-To' Create a copy / clone of repository

	git clone <URL of Repository>
	
	Example: 
		git clone https://github.com/ai-gaanv/Hello-GitHub.git

## 'How-To' Create a branch of repository on premise (or local machine)
	
	git checkout -b <New Branch Name>
	
	Example:
		git checkout -b Children-OnPremise-Branch_one
		
## 'How-To' Create a branch of repository on GitHub Cloud

	Click on button
	
	![Click on button] ( https://github.com/ai-gaanv/Hello-GitHub/blob/master/images/branch.png)
	Type branch name in textbox and Hit Enter


## 'How-To' Merge changes from one branch to other

	Checkout the branch where to add the changes, then hit the merge.

		Checkout to branch where to add the changes:
		
			git checkout <BranchName-To-MergeIn>

		Merge command with path of branch to pull the changes from:
		
			git merge <Source-BranchName>
			git merge origin/Children-branch-one


## 'How-To' Stage the Changes

	Use Add command to stage the changes for next commit
	git add images/branch.png

## 'How-To' Commit the Changes
	
	-m <message>. This adds the message for commit

	git commit -m "Change Details"

## 'How-To' Stage & Commit the Changes

	-a Includes all changed files in commit.
	
	git commit -a -m "Change titles and styling on homepage"

	-amend helps to rewrite the last commit


## 'How-To' Push the Changes

	Ensure the expected branch is checked out(if not, Can use git checkout)

	To push the changes:
	
	git push <target> <source>
		ex: git push origin <branch-name>
	
	Once push(s) is done, one can use below one as connection is now there
	git push
