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

---

## Practical 11 - Merge feature-payment into main

### Commands Used

```bash
git switch main
git pull
git merge feature-payment
```

### Output

```text
Fast-forward
```

### What Happened?

The changes from the feature-payment branch became part of the main branch.

### What I Learned

Git can perform a Fast-Forward Merge when there are no conflicting changes.

---

## Practical 12 - Push Updated Main Branch

### Command Used

```bash
git push
```

### What Happened?

The latest commits from the main branch were uploaded to GitHub.

### What I Learned

After merging locally, we need to push the updated main branch to GitHub.

---

## Practical 13 - Delete Local Branch

### Command Used

```bash
git branch -d feature-payment
```

### What Happened?

The feature-payment branch was deleted from my computer.

### What I Learned

A merged branch can be safely deleted locally.

---

## Practical 14 - Delete Remote Branch

### Command Used

```bash
git push origin --delete feature-payment
```

### What Happened?

The feature-payment branch was deleted from GitHub.

### What I Learned

Remote branches can also be deleted after they are merged.
