
## Technical training for elev8 Microsoft-ATO cohort 3 on how to set up git locally&push to git
## Preparing to use Git
Download Git bash https://git-scm.com/downloads  
##  Initial Git Setup  
git config --global user.name "username"  
git config --global user.email "email address"
## Pushing to GitHub
mkdir website  
cd website  
git init  
git remote add origin <URL>  
this should be the url from your created repo(use https) 
touch index.html  
git add index.html
git commit -m "Create index.html"
git push origin master
  
