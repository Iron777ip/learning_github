# learning_github

     Git functions

Git  -- help – fiend all you need for the git information.
Git config --global user.name “add the username that will be shown on the git changes” 
Git config –global user.email “please add the email that will shou on git hub”  
Git config –global color.ui auto this enables command line coloured output
Git config that will print configuration information instructions
Git config -l this will show up configuration data that have been added to a git information
Mkdir <directory name> create a directory “also called folder from the terminal”ls
Git init . – create a new empty repository. Brand new project
Rm -rf .git remove the repository or delete the folder .git
Git init . current directory
Git add – add files to the repository 
Touch <filename.type> create files inside the directory or repository
Git status – gives the status of the changes that we made 
Git add <filename.type>– updating changes that have been made (add to the staging area)
Git rm –cached <filename.type> undo the added changes (unstage) 
Git add . – means add all the files from this current directory down words 
Git rm -r –cached . this is removing all the files added from the staging area 
Git add -A – add every single file that has been created do not mater location of the directory 
Git commit -m “add the comments” committing the changes that have been done previously moving the files from the staging area and save them to the safe point
Git log -is the history of the commits in the repository 
Git show – show the history of the hash id selected 
Git log –pretty=”%h %s” the shortest version of the sha-1-hash (unique id )of the commit
Vi filename.type – is file modification 

Press I to insert the text Console.log(“insert the text”); esc to exit then : wq
Cat – it shows what is in the file 
Git diff – is the difference between what I have in current working directory and what has been committed 
Git restore – restore the file that have been changed
Git commit –amend -m “change the message”  massages have to be well descriptive to be understand by others
Git remote add origin <git link> add the repository to the git hub via command line
************Branch****************
     
main branch it is by defalt 

git branch -- will shou the nranch that you are in at the moment
git branch -r to see all the remort branchess
git branch -a -- check all brachies that you have
git branch <name of the new branch> -- this is the way we create a branch
git checkout <name of the branch that we want to swich>
git checkout - -- this will check out to the previous branch
git push --set-upstream origin <name of the branch> or git push -u origin -- this is the way we ate pushing the branch into the origin
git checkout -b <new branch name> - creates a new branch and moves into that new branch
git branch -d <name of the branch that we want to delete> - this is tha way to delete the branch we mast be in to the main branch

merging into the branch
     
git merge <name of the branch that we want to mergi into the new branch or main> - this is a method that will merge into the branch
git log --online -- this is checking online chagies
