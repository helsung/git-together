# git-together

Let's create a scenario where you are dealing with a git conflict - something that you'll come across many, many times!

1. One person in the pair should fork this repo and both persons should clone from the forked repo

2. Each person should `git checkout -b branchName` and change the colors of their choice in `index.js` and `style.css`

3. Commit changes to local repo and push your branch to your remote `git push origin branchName`

From here, one person should drive while the other navigates... 

4. On Github, open a PR and merge the branches. 

5. Uh oh, you'll notice that when you try to merge the second branch, there are conflicts!!!

6. Let's resolve conflicts in your IDE - first step is to check out to your `main` branch and `git pull`. Why? When you merged the first branch onto main, the latest `main` is not reflected in your local repo

7. checkout to the branch with conflicts and `git merge main`. Discuss with your partner how to resolve conflicts and then commit.

8. Now on Github, you'll see that the PR shows the branch is clean of conflicts and ready to merge to main

9. Merge and when both partners checkout to main and pull, you should see the freshest copy of main

Repeat steps and switch driver/ navigator roles!

