VCS - Version Control System
1.1 ->l lac line
1.2 ->1.5 lac line
1.3 ->2 lac line
VCS is used for tack and save changes to file.

:- for working working directory convert into git Repository
cmd- git init (store all tracking info)
cmd- git status
provide details of current branch master and feature branch
there is any commit or not and untrack file

cmd- git add <file> untracked file (working directory)convert into stageing area -> git repositroy.
for all file git add \* or git add .
start just current untracked file put into staged area and git add . provide more feature subdirectory file

before commit alway code should be in staged area means git add .
otherwise it wil not commit

cmd- git commit -"Message" Commiting chnages
every commit have unique SHA-1 has for tracking
this is used for staged to save into git repository

cmd git log - for show history of commit
cmd git log --oneline

cmd git diff , git diff commit1 commit2
it is show the diffrence bw working directory to staging area.
code review and debugging before commiting
cmd- git clone "url or path"
cmd- git fetch -> it is used to retrive the latest update from a remote repository without merging them into our local branch.
what you modified just not merge
cmd- git merge
