# GIT Cheatsheet

1. git config [options]
Sets the username and mail address for commits.
* `git config --global user.name "git-username"`
* `git config --global user.email "your@email.com"`

2. git init  
initialize repository as git  
`git init`

3. git clone [URL]
Clones repository from server like Github, gitlab.
* `git clone https://github.com/user/example.git`
* `git clone git@github.com:lZzozZl/cheatsheatsanddocs.git`

4. git status
Checks the current status of workig tree
* `git status`

5. git add [filename(s)]
Puts the unstage files to staging area
* `git add index.html style.css script.js`
* `git add . // add all unstage file/s`  

6. git commit -m [Message]
Records changes to the git repo by saving a
log message to gather with a commit ID.
* `git commit -m "fixed bug"`
* `git commit -a 	// commit all file without message`

7. git remote [Options] [Variable] [URL]
Connects your local repository to the remote repository over a server
* `git remote add origin https://github.com/user/repo`

8. git push [Options] [Variable] [Branch]
Push the content of your local repository to the added remote repository
* `git push -u origin main 	// -u means upstream`

9. git pull [Variable] [Branch] or [URL]
Fetch and integrate the contents of the remote repository to your
local repository
* `git pull origin main`
* `git pull https://github.com/user/repo`

10. git chekout [Branch]
Move from one branch to another branch
* `git chekout devbranch2`

11. git checkout [Options] [Branch]
Create specified branch and simultaneously switches to it
* `git checkout -b devbranch3`

12. git branch [Options] [Branch]
Performs operations over the specified branch
* `git branc -d devbranch2`

13. git merge [Branch]
Merge the history of specified branch into the current branch
* `git checkout devbranch3`

14. git log
Shows the log of the commits made so far the current branch
* `git log`

15. git show [Commit ID]
List the meta-data for the specific commit
* `git show (some incredably long number)`

