# Revisions and the Cloud ✏️☁️

## What is Version Control?
> Version Control is a system that allows you to revisit various versions of a file or set of files by recording changes. Through version control, one can revert a file or project to a previous version, track modifications and modifying individuals, and compare changes. By utilizing a Version Control System (VCS), mistakes with files can easily be rectified.

## What is cloning in Git?
> By cloning the file, you have copied all versions of all files for a project. This command leads to the creation of a directory called “test,” with an initialized .git directory inside it, which has copies of all versions of all files for the specified project. The command also automatically checks out — or retrieves for editing — a copy of the newest version of the project.
> ``$ git clone https://github.com/test``

## What is the command to track and stage files?
> Track **one file** only by using the following format:
>
> ``git add filename``
>
> Track **all files** in a repository by using the following command:
>
> ``$ git add *``

**After using these commands, files are tracked and staged for committing.**

## What is the command to take a snapshot of your changed files?
> ``$ git commit -m "Example Commit"``
> 
> To Undo:
> ``$ git revert HEAD``

## What is the command to send your changed files to Github?
> ``$ git push origin master``
