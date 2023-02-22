# Git
Git Practice
# Perform this commands 

# As github branch is main and our git branch is master we have to change git branch by 
     mkdir gg
     cd gg
     git init
     touch d.txt
     git add .
     git commit -m "nn"
     git branch -M main
     git branch
     git remote add origin <ssh link>
     git push -u origin main


  # Git Stash -- with this we will store our resumed work here
    git stash --- and the file will be stashed 
    git stash list -- will show you the stash list
    git stash apply stash@{}
    git stash clear -- will clear the stash list
  
  # Git reset -- By this if a a file which is stagged (by git add .)and the file is incorrect so 
  # If you want to take it back to workspace use this 
     git reset .
  
  # Git revert -- By this will tell users that this file has wrong data
  # This is used when we commit a wrong file
     git revert commit id ----(git log --oneline)will get commit id
  
  # git tag -- By this will give some tag to commits/files so that in future from this will get these files
     git tag -a tag_name -m "Message" commit id
  
  
