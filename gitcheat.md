#GitCheatSheet
'git config --global user.name "[name]''
Configure git on the computer using the github UN

'git config --global user.email "[email address]''
same as above except with email address used on github

'git config --list'
checks that it set it up right 

'git init'
initializes the git repository so it knows to pay attention to this folder
You should see something like Initialized empty Git repository in /Users/gcdri/Desktop/GitPractice/.git/

'git remote add origin [URL of your remote repo]''
connects to github; links local and remote repository

'git remote -v'
confrims that it worked ... shoudl see this: 
Origin https://github.com/jojokarlin/Git_DRI_Jan_2017 (fetch)
Origin https://github.com/jojokarlin/Git_DRI_Jan_2017 (push)

'git status'
tells you if changes have been made but not "staged" (i.e. not added) or committed.

'git log' 
a lot of all your recent movements in life 

'git add [[filename]]''
adds the file to staging and gets it ready to be committed

'git commit -m "[clear message describing the changes you made]"''
commits changes with a clear -message that says what you changed it

'git push origin master'
pushes committed file to github