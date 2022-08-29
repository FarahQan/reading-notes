# Definition of Git

Git is a free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency.

---

<br>

# Definition of Github

GitHub, is an Internet hosting service for software development and version control using Git. It provides the distributed version control of Git plus access control, bug tracking, software feature requests, task management, continuous integration, and wikis for every project.

---

<br>

## Generate SSH key :

- How to configure SSH with our github account ?
  <br>
  1- Follow : [Link](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)
  <br>
  2- Follow : [Link](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account)

---

## Git commands :

### there are two ways to clone repo from github :

<br>

1 - Using git clone

```
git clone <github.com/your_repo>
```

2 - Using git remote

- **git init** : to link your folder with github and create .git

```
git init
```

- **git remote** : to clone the repo

```
git remote add origin <Link_of_ssh_repo>
```

- **Check if locally connected to remote**

```
git remote --v
```

---

### A - C - P commands

```
  git add .
```

```
  git commit -m “your commit name”
```

```
  git push origin master or main
```

---

### Remove last commit

```
git reset HEAD~
```

---

### Show all your commits

```
git log
```

---

### Get files from remote

```
git pull origin <branch_name>
```

---

### Change branch name

```
git branch -m <old_name> <new_name>
```

---

### Create new branch

```
git checkout -b <branch_name>
```

---

### Change branch

```
git checkout <branch_name>
```

---

### when your remote branch is ahead of commits

```
git push -f origin <branch_name>
```

---

### if you want to save your current changes without losing it

1 - **Open source control in vs code**
<br>

2 - **From the three dots choose stash (include untracked)**
<br>

3 - **You can choose it from apply stash**
