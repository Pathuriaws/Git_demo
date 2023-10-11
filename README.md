# Git Day-2 _(10-11-23)_

Git Commands

```Git add .```

This command adds all changed files in the current working directory to the staging area.

```git commit -m "message"```

This command creates a new commit with the given message. The commit will contain all the files that were staged in the previous step.

```Git Branch```

```git branch <branchname>```

This command creates a new branch with the given name.

```git checkout -b <branchname>```

This command creates and switches to a new branch with the given name.

```git checkout <branchname>```

This command switches to the branch with the given name.

```git branch```

This command lists all branches in the local repository.

```git branch -D <branchname>```

This command deletes the branch with the given name. You must be on a different branch before deleting a branch.

```git log```

This command shows the commit history of the current branch.

#Git hub

```git clone <httplink>```

This command clones an existing repository from GitHub.

```vi calculator.sh```

This command opens the file calculator.sh in the Vi editor.

```:wq!```

This command saves the changes to the file and exits Vi.

```git add .```

This command adds all changed files in the current working directory to the staging area.

```git commit -m "message"```

This command creates a new commit with the given message. The commit will contain all the files that were staged in the previous step.

```git remote -v```

This command shows which remote repositories the local repository is connected to.

```git push origin```

This command pushes all local commits to the origin remote repository.

```git log <branchname>```

This command shows the commit history of the branch with the given name.

```git cherry-pick 4db0934c37e5009998732130f65410f12ac51523```

This command applies the commit with the given SHA-1 hash to the current branch.

Clone an existing repository from GitHub

```git clone https://github.com/user/repo.git```

Create a new branch

```git branch new-feature```

Switch to the new branch

```git checkout new-feature```

Make some changes to the code

Add the changes to the staging area

```git add .```

Create a commit with a message

```git commit -m "Added new feature"```

Push the commit to the remote repository

```git push origin new-feature```
