You can make a new folder on the GitHub website by making a new file and adding a '/' at the end of the line to initialize a new folder as well as a file

To check if the repository is up to date or has any changes: `git status` 

To pull a repository on the command line, use the following command (using this repository as a guideline). Say we wanted to add a new file called file.py to the master branch. We first want to pull the branch and then push the changes through through: 
```
git clone -b master https://github.com/AKHughes1994/GitHubGuide.git
touch file.py
git add -A
git commit -m "Added File"
```

If we want to update the directory, we would write:
```
git push -u origin master
```

If we want to sync the local repository with the remote
```
git pull origin master
```
