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
 

 