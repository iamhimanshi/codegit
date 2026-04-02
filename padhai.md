<!-- every command info will be stored here -->

git config --global user.name "name"
git config --global user.email " " 

git config --global core.editor "code --wait"

git config --global core.autocrlf
<!-- edit vaues with -->
git config --global -e


U - untracked  (git is unaware of this file)
A - added or staged (git is aware of this file)
C - commited (git is tracking the file)

<!-- to know status of current points -->
in terminal :- git log --oneline

<!-- going back to some previous saved point -->
they are of three types :- 
    git reset --hard HEAD~ 1/2/3   ---->> if want to go back 1 write ~1, if want to go back 2 write ~2 and so on      
    <!-- this will delete all the changes you have done after the last commit also will delete from files -->
    git reset --soft HEAD~
    <!-- this will unstage the changes but keep them in the working directory -->
    git reset --mixed HEAD~
    <!-- this will unstage the changes and discard them -->
<!-- HEAD is a reference to the current commit -->



<!-- status and logs -->
 
git status -s --> this will show the status of the files in a short format (unka sirf jo commited nhi h ya commit hobe ke baad change hua h)

git log  --> this will show the commit history in a detailed format

git log --oneline --> this will show the commit history in a short format

git log --graph --> this will show the commit history in a graphical format


<!-- branches -->  brraches are used to create a separate line of development in a repository. It allows you to work on different features or bug fixes without affecting the main codebase.

git branch --> this will show the list of branches in the repository

<!-- conflicts -->
<!-- when two or more people are working on the same file and they make changes to the same line of code, it will create a conflict. Git will not be able to automatically merge the changes and will require manual intervention to resolve the conflict. -->