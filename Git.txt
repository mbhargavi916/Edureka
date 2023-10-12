Local working directory: The first stage of a Git project life cycle is the local working directory where our project resides, which may or may not be tracked.
Initialization: To initialize a repository, we give the command git init. With this command, we will make Git aware of the project file in our repository.
Staging area: Now that our source code files, data files, and configuration files are being tracked by Git, we will add the files that we want to commit to the staging area by the git add command. This process can also be called indexing. The index consists of files added to the staging area.
Commit: Now, we will commit our files using the git commit -m ‘our message’ command.
We have successfully committed our files to the local repository. But how does it help in our projects? The answer is, when we need collaborative projects, files may have to be shared with our team members.

This is when the next stage of the Git life cycle occurs, i.e., in GitHub, we publish our files from the local repository to the remote repository. And how do we do that? We do that by using the git push command.