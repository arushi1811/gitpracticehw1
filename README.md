# gitpracticehw1

This repo was created to practice git from the command line.

The steps I took are as follows:

1. Created this repo on Github and cloned it on my local machine. 
  $ git clone <repo http url>
2. Added a file "one.txt" , staged, commited, and pushed it
   $ new-item one.txt
   $ git add .
   $ git commit -m "added one"
   $ git push -u origin main
  
3. Created a branch new branch, added a file "two.txt", and made changes in one
   $ git branch newb
   $ git checkout newb
   $ new-item two.txt
   <steps from part 2 to commit changes>

4. Merged the branches
   $ git checkout main
   $ git merge newb
   <commited and pushed changes>
     
 5. Reverted to previous commit
    $ git checkout <commit hash> .
    <staged, commited, and pushed changes>
     
   
