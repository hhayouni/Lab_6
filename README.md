# Lab 6

## Version Control
-  Local Version Control (Tracks changes on a Local Computer)
- Centralized Version Control (Uses a Central VCS Server for version history)
- Distributed Version Control (Every contributor has a whole copy of the project)

## How to
- Initializing a Repository in an Existing Directory :
```sh
$ git init
```

- Checking Repository Status
```sh
$ git status
```

- Adding a new file to be staged
```sh
$ git add [file_name]
```
- Adding all files to be staged :
```sh
$ git add.
```

- Unstaging a file
```sh
$ git rm --cached [file_name]
```

- ignoring a file :
```sh
$ nano .gitignore
```

- Commit
```sh
$ git commit -m “commit message”
```

- seeing the records :
```sh
$ git log
```

- Change branch name
```sh
$ git branch 0m master main
```
