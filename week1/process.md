1- Modify
The first stage is what happens when you create, edit, or delete files. Git isn't actually involved in this point at this point. You don't have to do anything special, just write code.

2- Stage
Before Git can protect a file you need to stage it. When you stage a file you notify Git that you intend to commit a specific version of the file. A commit is what it's called when you save a specific version of a file or a set of files into your repository.
The staging area, also called an index, is where Git stores the specific version of your file or files when you stage them.
It's important to note that just staging a file isn't the same as committing them. You can still edit a file and re-stage it without recording the change in your repository history.
In a nutshell, the staging area is just a list of files you want to commit.

3- Commit
Once you have added files to the staging area you can commit them. When you commit, you are instructing Git to record the files in the staging area into a record in the repository history. Now these files are protected!



