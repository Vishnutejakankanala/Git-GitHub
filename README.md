# GIT-COMMANDS
````
git		:- to show ll git commands
git init	:- to initialize git repository
ls -la		:- to see hidden folders
ls .git		:- to see what is in .git file
.git file is used to track all the program in the git repository.
git status	:- is used to see commit, track fies and what to do next
git add	<filename>	:- to track file ( add file to staging area)
git rm --cached <file name> :- to remove file from staging area
git add .		:- to track all files and folders in repo
git status 	:- to view changs
git diff	:- to view what exact change in file
git commit -m "this is first 1"	:- to write message to program
git log		:- used to see commits
git reset --hard <commit id>	:- to go to which version or commit you want.
git remote -v			:- to view remotes in the folder
git remote add < location url>	:- to add remote repo to local and to push to remote
git push -u origin master 	:- to push local repo to remote repo
````

 # GIT BRANCHES (feature branch creation)
````
git branch -M <branch name>	:- To create branch in local repo
git push origin <branch name>	:- To push created branch in remote repo
git checkout -b <branch name>	:- to create new branch in git
git chechout <branch name>   	:- to switch to other branch
git branch 			:- to list all branches
````
after modifing related changes need to excute (git add, git commit, git push)
Creating a pull request from github management console for to merge into master branch.
after merginging into the master branch 
git checkout master
git branch -D <feature branch> :- To delete feature branch

# TO MERGE BRANCHES (GIT MERGE, GIT REBASE OR GIT CHERRY-PICK)
````
git cherry-pick <commit id> 	:- used to move new commit to old commit
(cherry-pick is eassy to move one or two commits)
git merge <branch name>		:- to merge new branch to main/master
git rebash <branch name>	:- "             ||                "
git log --oneline		:- to show all commits in minimise
git log <branch name> --oneline	:- to show all commits minimise in branch
````

# Git stash
git stash :- Git stash acts as a mechanism to locally store version files hidden from other developers who share the same git repository.
````
1. git stash save 		:- To save changes into stash
2. git stash list		:- To list all the stash IDs
3. git stash apply stash@{0}	:- To apply changes from a specific stash ID. 545. 546. https://git-codecommit.us-east-1.amazonaws.com/v1/repos/mygitremoterepo
4. git push <https://git-codecommit.us-east-1.amazonaws.com/v1/repos/mygitremoterepo>
5. git pull <https://git-codecommit.us-east-1.amazonaws.com/v1/repos/mygitremoterepo>
6. git remote add origin <git remote url>  :- Used to add remote URL. 
7. git push -u <git url> <branch> --> To push the branch to remote repo
````

# Some imp commands
````
git config --global User.Name "vishnu"	:- to add user name
git config --global User.Email "mail id":- to add mail id
git clone <url>			:- to clone remote to local
git fetch	:- To get the difference between remote and local repo
git pull origin <branch name> :- To Bring new changes from remote to local.
dckr_pat_cZ6ceakn00sTBUPa3r0bbPUmtp0
````
# When we open new Repo in gitHub you will see
…or create a new repository on the command line
echo "# git2" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/Vishnutejakankanala/git2.git
git push -u origin main
…or push an existing repository from the command line
git remote add origin https://github.com/Vishnutejakankanala/git2.git
git branch -M main
git push -u origin main
…or import code from another repository
You can initialize this repository with code from a Subversion, Mercurial, or TFS project.


