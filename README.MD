To initialize a new local repository:  
- `git init`
    
To make Feature_A branch, make changes and commit them:  
- `git checkout -b Feature_A`
- `git add .`
- `git commit -m "Made some changes"`

Create Feature_B branch, make changes and commit them:  
- `git checkout -b Feature_B`
- `git add .`
- `git commit -m "Made some changes"`

Create Feature_C branch, make changes and commit them:  
- `git checkout -b Feature_C`
- `git add .`
- `git commit -m "Made some changes"`

Create Feature_D branch:  
- `git checkout -b Feature_D`

Copy all Feature versions in another branch D:
- `git merge Feature_A`
- `git merge Feature_B`
- `git merge Feature_C`

Merge Feature_D branch to master branch:
- `git checkout master`
- `git merge Feature_D`

Check if you have all changes in master branch:
- `git checkout master`
- `git pull`

Check what was changed and what was added commit by commit:
- `git log --raw`

Change git to a remote origin which is your gitlab/github account:
- `git remote add origin https://github.com/egijakalnina/hands_on_task_git.git`
- `git push`


