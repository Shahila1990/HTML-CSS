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

1. git fetch origin master/main
    
Then follow these steps to merge:

2. git pull origin master
3. git add .
4. git commit -m 'your commit message'
5. git push origin master/main
