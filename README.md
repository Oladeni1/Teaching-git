## Teaching git and github
olatunde Oladeni
Houston, Texas, USA

## Logo
https://www.google.com/imgres?imgurl=https%3A%2F%2Flawtomated.com%2Fwp-content%2Fuploads%2F2017%2F07%2Fgithub-logo.png&imgrefurl=https%3A%2F%2Flawtomated.com%2Fopen-source-contracts-part-1%2Fgithub-logo%2F&tbnid=8N75RXOALo1VlM&vet=12ahUKEwjgrv3xzoPxAhUFZRoKHQMXDBMQMygXegUIARD6AQ..i&docid=6er-BiqYi8C3tM&w=2000&h=665&q=github%20logo&safe=strict&ved=2ahUKEwjgrv3xzoPxAhUFZRoKHQMXDBMQMygXegUIARD6AQ

https://www.google.com/imgres?imgurl=https%3A%2F%2Fcdn.freebiesupply.com%2Flogos%2Fthumbs%2F2x%2Fgit-logo.png&imgrefurl=https%3A%2F%2Ffreebiesupply.com%2Flogos%2Fgit-logo%2F&tbnid=AJKqZQfs10F7WM&vet=12ahUKEwjgrv3xzoPxAhUFZRoKHQMXDBMQMyg4egQIARBf..i&docid=0J0YWbOH0SerZM&w=800&h=600&q=github%20logo&safe=strict&ved=2ahUKEwjgrv3xzoPxAhUFZRoKHQMXDBMQMyg4egQIARBf


### Git Commands:

## Creating a new repository
mkdir project
cd project
git init
git remote add origin git@github.com:yourlogin/your-repo.git
git add .
git commit -am “new repository”
git push -u origin master

## Cloning existing repository
git clone https://github.com/username/your-repo.git

## Creating branch
git checkout -b feature-1
you are now in a branch, you can edit and create new files
git add .
git commit -am “new feature”

## Getting status of changes
git status

## Getting log of commits
git log

## To show last 2 commits
git log -2

## To check changes made to file
git diff

## To show what has been committed
git show enter the commit tag number 

## To reset back to latest master commit
git reset --hard

## To reset back to specific commit
git reset enter the commit tag number 

## Merging branch to master
git checkout master
git merge feature-1
git push

## Deleting branch
git branch -d feature-x

## List all branches
git branch -a

## Switching branch
git checkout feature-x

## Switch to master branch
git checkout master

## Listing Remote repositories
git remote -v

## Replacing remote repository
# In case your remote repository changes, or you want to switch from HTTPS->SSH or SSH->HTTPS
git remote remove origin
git remote add origin git@github.com:yourlogin/your-repo.git

## Git workflow
git fetch
git pull
git checkout -b "specific branch"
> Make/save your changes
git add .
git commit -m "commit message"
git push
> Do pullrequest & merge your changes
git pull
git checkout master or main

## More resources
git commands: https://www.atlassian.com/git/tutorials/comparing-workflows/
git flow: http://danielkummer.github.io/git-flow-cheatsheet/



