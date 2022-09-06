1. How to list all the branches?
you can use git branch command to list all the branches. $ git branch -a

2. How to check all the possible commands of Git?
use git help command. $ git help --all

3. How to check all the options of a command?
use git help command. $git command --all

4. How to check the commit history?
we use git log command. $git log

5. How to commit the changes?
we use the git commit message that message describe that what we change. $git commit -m "commit message"

6. How to discard changes of a specific file (test.html) in the working directory?
we can discard changes of a specific file then we use a git restore command. $git restore (test.html)

7. How to stage the changes of a specific file (test.html)?
we want to stage the changes of a specific file we use a git add command. $ git add (test.html)

8. What are the different ways to stage all the changes?
we use git add command. $ git add -all or $ git add -A

9. How to check the status?
we use git status command. $ git status

10. How check status in short format?
we use git short command. $ git status -s or $ git status --short

11. How to initialize the git?
use git init command. $ git init

12. How to list all the configurations?
use git config command. $git config --list

13. How to configure email for a specific repo?
for user we use $ git config --user.email "emailid"

14. How to configure email at global?
for global we use $ git config --global user.email "emailid"

15. How to configure user name at global?
for global we use $ git config --global user.name "your name"

16. How to configure user name for a specific repo?
for user we use $ git config --user.name "your name"

17. Explain how you will generate the SSH key?
-> fist login into your github account. -> after that click on your profile and then go to settings. -> in the setting click SSH and GPG keys. -> click on the new ssh key. -> then type the title and bottom of the page show the add SSH key and click on that then we generate the SSH key

18. How to create a branch (my-first-branch)?
we use branch command. $git checkout -b (my-first-branch)

19. How to checkout to a branch (my-first-branch)?
to checkout your first branch. $ git checkout (my-first-branch)

20. How to create a branch & checkout to that branch (my-second-branch)?
we use the command for create new branch is $ git checkout -b (my-second-branch) and checkout to that branch is $ git checkout (my-second-branch)

21. How to delete a branch (my-third-branch)?
to delete the branch $ git branch -D (my-third-branch)

22. How to merge the branch (my-fourth-branch)?
first we create the branch by $ git branch -b (my-fourth-branch) and then we switched to master branch by using $ git checkout master and then we use the merge command $ git merge (my-fourth-branch)

23. How to pull the changes from 'main' branch?
when we create new branch and make some changes and git checkout to new branch after that we use pull command to merge the main branch command for pull is $ git pull origin

24. How to clone a repo using https url?
To clone the repo by using https url is we use the git clone command $ git clone "repo httos url"

25. How to clone a repo using ssh url?
use clone command $ git clone "repo ssh url

26. How to clone a repo from a specific branch?
to clone a repo from specific branch is $ git clone -b

27. How to roll back to a specific commit?
we use $ git checkout --> ROLL BACK TO PREVIOUS COMMIT IS $ git reset / git reset $ git revert / git revert

28. How to change the commit message of the last commit?
we use $ git commit --amend -m "new commit message"

29. How to list all the stashes?
we use $ git stash list

30. How to stash the changes?
we use $ git stash

31. How to apply the topmost stash and leave it in the stash list?
   $ git stash apply
32. How to apply the topmost stash and remove it from the stash list?
   $ git stash pop
33. How to apply a specific stash based on the stash number?
   $ git stash apply n  "n" is the stash number
      $ git stash apply n  "n" is the stash number
34. How to drop a specific stash based on the stash number?
   $ git stash drop <stash number>
35. How to clear the complete stash list?
we use clear command. $ git stash clear or $ git stash drop

36. Why we use .gitignore file?
.gitignore is used to files will not tracked by the git
