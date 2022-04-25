# Html-Css

# git commands
git init
    git add .
    git commit -m "my commit"
    git remote add origin <remote repository URL>
    git push origin master
  
# git push to main from master
  git checkout master   
git branch main master -f    
git checkout main  
git push origin main -f 
    
# error and warning
    As it is stated in the Error message you have to "fetch first." This worked for me. Use the command:

git fetch origin master
Then follow these steps to merge:

git pull origin master
git add .
git commit -m 'your commit message'
git push origin master
