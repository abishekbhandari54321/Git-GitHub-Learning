# Practical Exercises

## Practical 1 - View Current Branch

### Command Used

```bash
git branch
```

### Output

```text
* main
```

### What I Learned

The `*` symbol shows the current branch.

---

## Practical 2 - Create a Branch

### Command Used

```bash
git branch feature-login
```

### What Happened?

A new branch named `feature-login` was created.

### What I Learned

Creating a branch does not automatically switch to it.

---

## Practical 3 - Switch Branch

### Command Used

```bash
git switch feature-login
```

### Output

```text
Switched to branch 'feature-login'
```

### What I Learned

I moved from the `main` branch to the `feature-login` branch.

---

## Practical 4 - Create a File in the Branch

Created:

```text
feature-login.txt
```

Content:

```text
This file was created in the feature-login branch.
```

### What I Learned

Files created in one branch do not automatically appear in another branch.

---

## Practical 5 - Switch Back to Main

### Command Used

```bash
git switch main
```

### What Happened?

The `03-Branches` folder and `feature-login.txt` disappeared because they only existed in the `feature-login` branch.

### What I Learned

Branches have their own separate changes.

---

## Practical 6 - Switch Again to feature-login

### Command Used

```bash
git switch feature-login
```

### What Happened?

The `03-Branches` folder and `feature-login.txt` appeared again.

### What I Learned

Git restores the files according to the selected branch.

---

## Practical 7 - Merge Branch

### Command Used

```bash
git switch main
git merge feature-login
```

### What Happened?

The changes from `feature-login` were merged into `main`.

### What I Learned

Merging combines the work from one branch into another.

---

## Practical 8 - View All Branches

### Command Used

```bash
git branch -a
```

### What I Learned

This command shows both local and remote branches.

---

## Practical 9 - Create and Switch in One Command

### Command Used

```bash
git switch -c feature-payment
```

### What I Learned

This command creates and switches to a new branch in one step.

---

## Practical 10 - Push a Branch to GitHub

### Commands Used

```bash
git push -u origin feature-payment
```

### What I Learned

A new branch can be uploaded to GitHub.
