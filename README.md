# Git-Assessment
Homework 2 7/23

Why do we use Git?
It allows us to save our progress at a specific stage in development and allows us to return to that stage in the future if changes were introduced that created issues.

What is the difference between Git and Github?
Git is just a way to save the progress made, where as GitHub is where that progress is actually saved to. Git just packages your information for GitHub or another Git database.

How does Git work?
Git basically saves data in different stages, which are unstaged, staged, and committed. Unstaged means that changes in the Git will not be pushed into future "snapshots", or saves, of the Git repository. Staged means that the changes are included in future versions, and finally committed means that the change has stuck around long enuogh to be in previous snapshots.

What is a Git repository?
It is a directory on your local computer that has been initialized by Git.

Initialize a Git repository
To do so, within the CLI type
  git init <filename>

add and commit changes to a Git repository
To add changes, use *git add*, and your new files will be lumped together, ready to go to GitHub. To commit, type *git commit*, add a message for some reason, and then the changes are saved! 

Add remote destinations to your local Git repository
Use *git remote add*!

push commits from your local Git repository to a remote repository
Use *git push*!

- Fork and Clone - Fork will create a identical repository to experiment with; clone will create that repository merely as a backup.
- `git add` - add new files
- `git push` - upload changes to repository
- `git commit -m 'some message'` - commit changes to repository w/ message
- `git push origin master` - push to the origin master
- `git remote -v` - change the remote location that you send the changes to (if not GitHub, send elsewhere) and be verbose about it
- `git status` - checks the status of your git (unstaged, staged, committed)
- `git remote add [remote url here] ` - designates the url as the place to push git
- `git remote remove origin` - remove the remote origin from the push