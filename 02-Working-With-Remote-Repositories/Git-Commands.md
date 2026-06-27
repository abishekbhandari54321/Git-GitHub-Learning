# Git Commands - Working with Remote Repositories

## Clone a Repository

Downloads a complete repository from GitHub to your computer.

```bash
git clone <repository-url>
```

Example:

```bash
git clone https://github.com/username/project.git
```

---

## Fetch Changes

Downloads information about new commits from GitHub but does not update local files.

```bash
git fetch
```

---

## Pull Changes

Downloads and applies the latest changes from GitHub to your local repository.

```bash
git pull
```

---

## Push Changes

Uploads your local commits to GitHub.

```bash
git push
```

---

## View Connected Remote Repository

Shows the GitHub repository connected to your local project.

```bash
git remote -v
```

---

## View Complete Commit History

Shows all commits in detail.

```bash
git log
```

Press `q` to exit.

---

## View Short Commit History

Shows commit history in one line per commit.

```bash
git log --oneline
```
