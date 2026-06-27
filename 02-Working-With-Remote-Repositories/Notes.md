# Working with Remote Repositories

## What is a Repository?

A repository (repo) is a folder whose files and changes are tracked by Git.

Example:
A React project, Django project, or any code project can become a Git repository after running:

```bash
git init
```

---

## What is a Remote Repository?

A remote repository is a Git repository stored on a remote server like GitHub.

It allows:

- Backup of code
- Sharing code with other developers
- Collaboration on projects
- Accessing the project from multiple computers

---

## What is git clone?

`git clone` downloads a complete Git repository from GitHub to your local computer.

Command:

```bash
git clone <repository-url>
```

Example:

```bash
git clone https://github.com/username/project.git
```

---

## What is git fetch?

`git fetch` checks for new changes on GitHub and downloads information about those changes, but it does not update your local files.

Command:

```bash
git fetch
```

After `git fetch`, your branch may become behind `origin/main` if there are new commits on GitHub.

---

## What is git pull?

`git pull` downloads and applies the latest changes from GitHub to your local repository.

Command:

```bash
git pull
```

`git pull` is equivalent to:

```bash
git fetch
git merge
```

---

## What is git push?

`git push` uploads your local commits to GitHub.

Command:

```bash
git push
```

---

## Difference between git fetch and git pull

| Command   | Downloads Changes | Updates Local Files |
| --------- | ----------------- | ------------------- |
| git fetch | Yes               | No                  |
| git pull  | Yes               | Yes                 |

---

## What is git remote -v?

`git remote -v` shows the GitHub repository connected to your local repository.

Command:

```bash
git remote -v
```

---

## What is git log?

`git log` shows the complete commit history of the repository.

Command:

```bash
git log
```

Press `q` to exit.

---

## What is git log --oneline?

`git log --oneline` shows a short and clean version of the commit history.

Command:

```bash
git log --oneline
```

---

# Summary

Today I learned:

- What is a repository
- What is a remote repository
- git clone
- git fetch
- git pull
- git push
- git remote -v
- git log
- git log --oneline
