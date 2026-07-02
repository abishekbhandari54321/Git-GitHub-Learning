# Practical Exercises

## Practical 1 - Ignore a File

Created:

```text
secret.txt
```

Created:

```text
.gitignore
```

Content:

```text
secret.txt
```

### Command

```bash
git status --ignored
```

### What I Learned

Git ignored `secret.txt`.

---

## Practical 2 - Stage Files

### Command

```bash
git add .
git status
```

### What I Learned

Files moved to the staging area.

---

## Practical 3 - Unstage a File

### Command

```bash
git reset test.txt
```

### What I Learned

The file was removed from the staging area but was not deleted.

---

## Practical 4 - Save Work Temporarily

Created:

```text
temp.txt
```

### Command

```bash
git stash
```

### What I Learned

Git temporarily saved my work and cleaned the working directory.

---

## Practical 5 - View Stashes

### Command

```bash
git stash list
```

### What I Learned

Git showed all saved stashes.

---

## Practical 6 - Restore Stashed Work

### Command

```bash
git stash pop
```

### What I Learned

Git restored my files and removed the stash.

---

## Practical 7 - Create a Temporary Commit

Created:

```text
revert-demo.txt
```

### Commands

```bash
git add .
git commit -m "Added revert demo file"
```

### What I Learned

I created a commit to practice `git revert`.

---

## Practical 8 - Revert a Commit

### Command

```bash
git revert --no-edit b72ee08
```

### What Happened?

Git created a new commit:

```text
Revert "Added revert demo file"
```

The file `revert-demo.txt` disappeared.

### What I Learned

`git revert` does not delete history. It creates another commit that undoes the changes.
