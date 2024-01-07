git init
1. Hello this is a demo project for learning git.
2. Create git repo (.git folder)
3. Un-versioned project to versioned project

git commit
1. meaningful state - versioned copy of this state -> 1.0
2. move to staging area
3. commit the file to the local repo

git push
1. moving your code from local to remote
2. We need to have a GitHub account
3. github account setup in Intellij

git pull
1. Get the latest changes from remote to working copy
2. pull is directly fetching code to remote to local + merge from local
  
git branches
1. Branches create a new line of development without affecting the master / main branch

git - adding new feature
1. Pull latest changes
2. Create a branch
3. Make changes
4. Commit the changes
5. push the code to remote
6. Create a pull request
7. merge the code once approved

git - merge conflicts
1. Merge conflicts happen when you merge branches that have competing commits and git needs your help to find the final change
2. In most occasions git can automatically merge code

git - revert / drop / undo commits
1. Revert / Reset commit -> History will be maintained in Git log. Revert maintains the reverted changes in the git log history, later if required we can cherry-pick a commit to work from there.
2. Drop commit -> No history will be maintained. Dropping a commit loses all the changes made in that particular commit, loses all the traces
3. Undo commit -> Drop the commit but the file changes will be still valid

git - cherry-pick a commit with intellij
1. cherry-picking is the process of picking up the commits from one branch and applying it on the another