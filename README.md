A swift application

#initialise 
 git init

#add all files
 git add *

#first commit
 git commit -m 'first commit (for iPhone only)'

#at this stage create a GitHub repository
git remote add origin https://github.com/ranadas/FineMe.git
git push -u origin master



git checkout -b develop

git commit -m 'for develop'

git push -u origin develop
