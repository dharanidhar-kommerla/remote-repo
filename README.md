# remote-repo
How to push local repository to remote repository
---
1. create a local repository
   > mkdir local-repo<br>
   > cd local-repo<br>
   > echo "# local-repo" >> README.md  

2. initalize it
     git init

3. check the status
    > git status

4. Add files to stagging area
   > git add .

5.  commit with message
    > git commint -m "first commint"

6. select the branch
   > git brach -M main

7. create a repo in the remote-repository and push local-repo to it
   > git remote add origin <remote-repo>

8. push to remote-repo
   > git push -u origin main
