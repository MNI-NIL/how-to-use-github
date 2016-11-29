# How to use Git/Github?

### Part 1: Git Essentials


Check if you have git installed in your machine with  `git --version`, if not install it via apt-get, brew or bower


Basic Commands:
* `git init` is used to initialize a repository with git version control
* `git add <filename>, git rm <filename>` is used to add or remove a tracking of a file. To add all files, use `git add .`. If you removed files and you added new changes, you can use `git add -u`. 
* `git status` is your best friend. It will tell you what change was done and whether you need to push, pull, or commit. 
* `git commit -m “description of changes made”` is used to issue a commit message to track your change. The convention is to use lower case letters and shortly describe what change you have peformed, such as Fix bug, Add some function, Refactored something. 
* `git push origin master` is used to push your change to the origin remote in the master branch.
* `git pull origin master` is used to pull the change from the origin remote and from the master branch.


Other commands: 
* `git branch` will tell you which branch are you using, the default is `master`* `git remote -v` will tell you the remotes (where are you pushing and pulling to and from)
* `git remote add origin git@github.com:user/repo.git` is used to add a new remote


### Part 2: Github


* Create Personal Account: www.github.com 
* Create your website repository: `username.github.io` and create a branch `gh-pages` to build your website
* Generate SSH Key from here https://help.github.com/articles/generating-an-ssh-key/
* Configure your name and email you used when you signed up for Github with `git config --global user.email "your@email.com"` and `git config --global user.name "Your Name"`.


