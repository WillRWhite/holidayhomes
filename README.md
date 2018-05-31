# holidayhomes

See markdown stuff
https://guides.github.com/features/mastering-markdown/
https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet

#### Configure Local Repo

git init  
git add .  
git commit -m "First commit"  

#### Push Local Repo to this Remote Repo

git remote add origin https://github.com/WillRWhite/holidayhomes.git  

\# Verifies the new remote URL  
git remote -v  
git push -u origin master  

#### Clone

git clone https://github.com/WillRWhite/holidayhomes.git  

#### Synchronising Local Repo with this Remote Repo

See: https://help.github.com/articles/fetching-a-remote/

git status  
\# Synchronise chahges only  
git fetch origin  
git status  
\# The following two commands are only required if you have made changes to the local repo  
\# git reset --hard origin/master    
\# git clean -f -d  
\# now if required merge the changes  
git merge origin\master  
\# The following commands fetches and merges  
git pull  
