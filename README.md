# test
testing for charlie

Learning Git

Live Site: http://maxwellcarlscott.com/all-hosted/test/

Update Current time in index.html
Change files to get a feel for git

:: Steps ::

Checking out this Project:

1. Open up terminal
2. CD to your websites folder
3. $ git checkout https://github.com/maxwellcarl/test.git   <- ( location of git hub project you want to work on )
4. Edit the files  ( update index.html with current time or whatever you want )

View Changes and Push to Repo:

1. cd to project root folder in terminal
2. $ git status  ( this shows which files you've edited )
3. $ git add .   ( this stages all edited files for commit )
4. $ git commit -m "edited time"   ( this commits changes in qoutes add a message for the commit i.e. updated index.html or changed time )
5. $ git push origin master    ( pushes the repo with your latest commits to the repository. they will now show up on the repo and on the live server. )

Creating a new branch to work on:

1. git branch   ( returns current working branch )( most likely master branch if none have been made )
2. git checkout -b [new branch name]    ( creates new branch of HEAD )
3. git push origin [new branch name]

Google more on merging / branching etc if you'd like or just work on master.

https://help.github.com/
