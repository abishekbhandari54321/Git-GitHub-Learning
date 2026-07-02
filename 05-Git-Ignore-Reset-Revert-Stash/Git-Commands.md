# Git Commands - Git Ignore, Reset, Revert and Stash

## Ignore a file

Create a `.gitignore` file and write:

```text
secret.txt
```

---

## Check ignored files

```bash
git status --ignored
```

Shows all ignored files.

---

## Add files to staging area

```bash
git add .
```

Adds all changes to the staging area.

---

## Remove a file from staging area

```bash
git reset <file-name>
```

Example:

```bash
git reset test.txt
```

---

## Alternative way to unstage a file

```bash
git restore --staged <file-name>
```

Example:

```bash
git restore --staged test.txt
```

---

## Temporarily save changes

```bash
git stash
```

Stores the current changes and cleans the working directory.

---

## Show all stashes

```bash
git stash list
```

Shows all saved stashes.

---

## Restore the latest stash

```bash
git stash pop
```

Restores the latest stash and removes it from the stash list.

---

## Undo a commit safely

```bash
git revert <commit-id>
```

Example:

```bash
git revert b72ee08
```

---

## Undo a commit without opening the editor

```bash
git revert --no-edit <commit-id>
```

Example:

```bash
git revert --no-edit b72ee08
```

---

## View commit history

```bash
git log --oneline
```
