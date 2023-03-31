# Git Commands

## Basic overview how Git commands work.

* Create a repository (project) into Git hosting tool like **[GitHub](https://github.com/)** or **[Bitbucket](https://bitbucket.org/)**.
* Copy or clone the repository to your local machine.
* Add a file to the local repository and commit.
* Push the changes to the main branch.

## What is Git ?

Git is a version control system. It helps you keep track of code changes. It is used to collaborate on code.

## Git Version Check

```
git --version
```

## Configure Git

```
git config --global user.name "user-name"
```
```
git config --global user.email "user-email"
```

## Initialize Git

```
git init
```

## Git Status

```
git status / git status --short
```

## Git Add All Files

```
git add --all / git add -A
```

## Git Commit

```
git commit -m "added all files / updated / deleted"
```

```
git commit -a -m "added all files / updated / deleted"
```

## Git Add Single File

```
git add file.txt
```

## Git Commit Single File

```
git commit -m "added file / updated / deleted" file.txt
```

## Git Commit Two or More Files

```
git commit -m "added file / updated / deleted" file.txt file2.txt
```

## Git Check Log

```
git log
```

## Git Help

```
git help --all / git commit -help
```

## Git Remove Repository

```
rm -fr .git
```

## Git Get the current remote path

```
git remote
```

## Git Remove the remote path

```
git remote remove <remote path>
```

## Git Add the remote origin

```
git remote add origin <your git repo http path>
```

## Git Check the current Remote Connection

```
git remote -v
```

## Git Remove Remote Origin

```
git remote rm origin
```

## Git Unstage

```
git rm --cached
```

## Git Unstage Single File

```
git rm --cached file.txt
```

## Git Add All Files Except One

```
git add -- . ':!<path>'
```

## Git Add All Files Except Two or More

```
git add --all -- ':!path/to/file1' ':!path/to/file2' ':!path/to/folder1/*'
```

```
git add -- . ':!path/to/file1' ':!path/to/file2' ':!path/to/folder1/*'
```

## Git change branch

```
git branch -M main
```
