1. Some teminology
- Direction: Thư mục
- Terminal: command line
- cli: Command Line interface
- cd: change direction
- code editor
- repository: Kho chứa
- git: the system to manage version and storage code
- github: storage code
2. With stored code in github repo
- Clone: Bring the code that hosted some where like github into a folder on your local machine.
- add: track code that is untracked. When add a new code line or new code. let's use command "git add >" to tracked code
- commit: save your code into git ( local machine). 
Command to commit code: git commit -m "your meassage" (-m: message).
- push: Push coded on github server. Command: git push
3. With code is the first time connect with github
- direct in the project folder
- init git: git init
- checking git status: git status
- track code: git add .
- save code into git: git commit -m ""
- push file:
+ when push the first repo to github: " git push origin master"--> an error: fatal: 'origin' does not appear to be a git repository. 
. Create an empty repo on github
. Connect local repo to empty repo on git hub: git remote add origin repo_url
. checking remote connect status: git remote -v
. push repo the first time into github: git push -u origin master
. the next time: git push


