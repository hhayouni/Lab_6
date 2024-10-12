# Lab 6

---
# Git
Version Control and Collaboration / Git is essential to use a version control system for software development and other documentation works.
(Modified, Staged, Commited)

---
# How to install
- Linux / Mac / Windows (check pre-installed version)
```sh
$ git --version
```
=>
- Linux : 
```sh
$ sudo apt install git-all
```
- Mac : 
Binary installer, Building from Source, Installing git-gui :
```sh
$ brew install git-gui
```

- Windows : Run "Git Bash"
=> powershell ? 'winget install --id Git.Git -e --source winget'
---
# Config => First setting
1. System level: --system option. Affects all uses and repositories on the system (administrative)
- file: /etc/gitconfig
2. Global (user) level: --global option. Affects all repositories of a current user
- file: ~/.config/git/config
3. Local level: --local option. Specific to the current repository
- file: .git/gitconfig

---
# Next
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
> Adding **all** files to be staged :
```sh
$ git add .
```

- Unstaging a file
```sh
$ git rm --cached [file_name]
```

- Commit
```sh
$ git commit -m “commit message”
```

- Change branch name
```sh
$ git branch
* master
$ git branch 0m master main
$ git branch
* main
$ git status
~~
```
