# Git Commands - Branching

## Show all local branches

```bash
git branch
```

Shows all branches in the local repository.

---

## Show all local and remote branches

```bash
git branch -a
```

Shows local and remote branches.

---

## Create a new branch

```bash
git branch <branch-name>
```

Example:

```bash
git branch feature-login
```

---

## Switch to another branch

```bash
git switch <branch-name>
```

Example:

```bash
git switch feature-login
```

---

## Create and switch to a new branch

```bash
git switch -c <branch-name>
```

Example:

```bash
git switch -c feature-payment
```

---

## Merge a branch into the current branch

```bash
git merge <branch-name>
```

Example:

```bash
git merge feature-login
```

---

## Delete a branch

```bash
git branch -d <branch-name>
```

Example:

```bash
git branch -d feature-login
```

---

## Push a branch to GitHub

```bash
git push -u origin <branch-name>
```

Example:

```bash
git push -u origin feature-payment
```

---

## Delete a remote branch

```bash
git push origin --delete <branch-name>
```

Example:

```bash
git push origin --delete feature-payment
```

Deletes a branch from GitHub (remote repository).

---

## Check repository status

```bash
git status
```

Shows the current state of the repository.

---

## View commit history

```bash
git log
```

Shows the complete commit history.

---

## View short commit history

```bash
git log --oneline
```

Shows a short and clean version of the commit history.
