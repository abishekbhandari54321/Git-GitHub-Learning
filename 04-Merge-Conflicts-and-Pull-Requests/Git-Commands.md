# Git Commands - Merge Conflicts and Pull Requests

## Check repository status

```bash
git status
```

Shows the current state of the repository.

---

## Merge a branch

```bash
git merge <branch-name>
```

Example:

```bash
git merge feature-navbar
```

---

## Abort a merge

```bash
git merge --abort
```

Cancels the current merge operation.

---

## Stage resolved files

```bash
git add .
```

Marks the conflict as resolved.

---

## Commit after resolving conflicts

```bash
git commit -m "Resolved merge conflict"
```

Creates a merge commit.

---

## Push changes

```bash
git push
```

Uploads changes to GitHub.

---

## Create and switch to a branch

```bash
git switch -c <branch-name>
```

Example:

```bash
git switch -c feature-footer
```

---

## Push a branch to GitHub

```bash
git push -u origin <branch-name>
```

Example:

```bash
git push -u origin feature-footer
```

---

## Download latest changes

```bash
git pull
```

Updates the local repository.

---

## Delete local branch

```bash
git branch -d <branch-name>
```

Example:

```bash
git branch -d feature-footer
```

---

## Remove deleted remote branch references

```bash
git fetch --prune
```

Removes old remote branch references from the local repository.

---

## View commit history graph

```bash
git log --graph --oneline --all
```

Shows the branch and merge history visually.
