Step 1: commit changes
$ nano helloworld.c
$ git add helloworld.c
$ git commit -m "Added a comment"

Step 2: push changes to remote repository
$ git branch
$ git push origin newworld

Step 3: merge changes into main
merge and close pull request

Step 4: update main with latest changes from repository
$ cd hello-world
$ git checkout main
$ git pull origin main

Step 5: merges changes updates to main into branch
$ git checkout newworld
$ git merge main

Step 6: updates remote branch with updated local branch
$ git push origin newworld
$ git log
