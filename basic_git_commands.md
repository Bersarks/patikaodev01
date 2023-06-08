## You can get information about basic Git commands here. For more information, you can visit [this](https://blog.testproject.io/2019/06/18/git-commands/) link.
### **1. git clone**

This command is used for downloading the latest version of a remote project and copying it to the selected location on the local machine. It looks like this:

git clone <repository url>

Here’s an example:

### ![Git clone command](https://blog.testproject.io/wp-content/uploads/2021/03/GitClone-512x118.png "Git clone command")

To clone a specific branch, you can use

git clone <repository url> -b <branch name>

### **2. git fetch**

This Git command will get all the updates from the remote repository, including new branches.

### **3. git checkout**

You can use the  **checkout** command to switch the branch that you are currently working on.

git checkout <branch name>

If you want to create a new branch and switch to it, you can do it by using this command:

git checkout -b <branch name>

### **4. git init**

This is the command you need to use if you want to start a new empty repository or to reinitialize an existing one in the project root. It will create a .git directory with its subdirectories. It should look like this:

git init <repository name>

### **5. git commit**

This one is probably the most used Git command. After changes are done locally, you can save them by “committing” them. A commit is like local a snapshot of the current state of the branch, to which you can always come back. To create a new commit, type this command in Git Bash:

git commit -m "<commit message>"

If all goes well, you will see the changes in the commit:

![Git Commit](https://blog.testproject.io/wp-content/uploads/2021/03/GitCommit-512x71.png "Git Commit")

### **6. git push**

Git push will push the locally committed changes to the remote branch. If the branch is already remotely tracked, simply use it like this (with no parameters):

git push

If the branch is not yet tracked, and only resides on the local machine, you need to run the command like this:

git push --set-upstream <remote branch>  <branch name>

Like this:

![Git Push](https://blog.testproject.io/wp-content/uploads/2021/03/GitPush-512x35.png "Git Push")

### **7. git diff**

You can use this command to see the unstaged changes on the current branch. Here’s an example of a branch with an edited feature file:

![Git Diff](https://blog.testproject.io/wp-content/uploads/2021/03/GitDiff-512x143.png "Git Diff")

If you want to see the staged changes, run the diff command like this:

git diff --staged

Or you can compare two branches:

gif diff <branch1>  <branch2>

### **8. git pull**

Using git pull will fetch all the changes from the remote repository and merge any remote changes in the current local branch.

### **9. git add**

This is the command you need to use to stage changed files. You can stage individual files:

git add <file path>

Or all files:

git add .

### **10. git branch**

Using git branch will list all the branches of the repository:

![Git Branch](https://blog.testproject.io/wp-content/uploads/2021/03/GitBranch.png "Git Branch")

Or you can use it to create a new branch, without checking it out:

git branch <new branch>

To delete a branch, run it like this:

git branch -d <branch name>

### **1. git clone**

This command is used for downloading the latest version of a remote project and copying it to the selected location on the local machine. It looks like this:

git clone <repository url>

Here’s an example:

### ![Git clone command](https://blog.testproject.io/wp-content/uploads/2021/03/GitClone-512x118.png "Git clone command")

To clone a specific branch, you can use

git clone <repository url> -b <branch name>

### **2. git fetch**

This Git command will get all the updates from the remote repository, including new branches.

### **3. git checkout**

You can use the  **checkout** command to switch the branch that you are currently working on.

git checkout <branch name>

If you want to create a new branch and switch to it, you can do it by using this command:

git checkout -b <branch name>

### **4. git init**

This is the command you need to use if you want to start a new empty repository or to reinitialize an existing one in the project root. It will create a .git directory with its subdirectories. It should look like this:

git init <repository name>

### **5. git commit**

This one is probably the most used Git command. After changes are done locally, you can save them by “committing” them. A commit is like local a snapshot of the current state of the branch, to which you can always come back. To create a new commit, type this command in Git Bash:

git commit -m "<commit message>"

If all goes well, you will see the changes in the commit:

![Git Commit](https://blog.testproject.io/wp-content/uploads/2021/03/GitCommit-512x71.png "Git Commit")

### **6. git push**

Git push will push the locally committed changes to the remote branch. If the branch is already remotely tracked, simply use it like this (with no parameters):

git push

If the branch is not yet tracked, and only resides on the local machine, you need to run the command like this:

git push --set-upstream <remote branch>  <branch name>

Like this:

![Git Push](https://blog.testproject.io/wp-content/uploads/2021/03/GitPush-512x35.png "Git Push")

### **7. git diff**

You can use this command to see the unstaged changes on the current branch. Here’s an example of a branch with an edited feature file:

![Git Diff](https://blog.testproject.io/wp-content/uploads/2021/03/GitDiff-512x143.png "Git Diff")

If you want to see the staged changes, run the diff command like this:

git diff --staged

Or you can compare two branches:

gif diff <branch1>  <branch2>

### **8. git pull**

Using git pull will fetch all the changes from the remote repository and merge any remote changes in the current local branch.

### **9. git add**

This is the command you need to use to stage changed files. You can stage individual files:

git add <file path>

Or all files:

git add .

### **10. git branch**

Using git branch will list all the branches of the repository:

![Git Branch](https://blog.testproject.io/wp-content/uploads/2021/03/GitBranch.png "Git Branch")

Or you can use it to create a new branch, without checking it out:

git branch <new branch>

To delete a branch, run it like this:

git branch -d <branch name>
