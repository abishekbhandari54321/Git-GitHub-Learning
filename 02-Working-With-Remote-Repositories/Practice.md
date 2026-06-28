# Practical Exercises

## Practical 1 - git clone

### Command Used

```bash
git clone https://github.com/abishekbhandari54321/Git-GitHub-Learning.git
```

### Output

A new folder named `Git-GitHub-Learning` was created in my D drive.

### What Happened?

The complete repository was downloaded from GitHub to my computer.

### What I Learned

- `git clone` downloads the entire repository.
- It also downloads the commit history.
- The downloaded folder is also a Git repository.

---

## Practical 2 - git fetch

### Command Used

```bash
git fetch
```

### Output

```text
From https://github.com/abishekbhandari54321/Git-GitHub-Learning
f2658a7..390a4da main -> origin/main
```

### What Happened?

Git found that there was one new commit on GitHub.

### What I Learned

- `git fetch` checks for updates from GitHub.
- It downloads information about new commits.
- It does NOT update my local files.

---

## Practical 3 - git status after git fetch

### Command Used

```bash
git status
```

### Output

```text
Your branch is behind 'origin/main' by 1 commit, and can be fast-forwarded.
(use "git pull" to update your local branch)
```

### What Happened?

Git informed me that my local repository is one commit behind GitHub.

### What I Learned

- My local repository knew about the new commit.
- The files were still not downloaded.

---

## Practical 4 - git pull

### Command Used

```bash
git pull
```

### Output

(Write the output you get after running the command.)

### What Happened?

The latest changes from GitHub were downloaded and applied to my local repository.

### What I Learned

- `git pull` downloads and applies changes.
- `git pull` is similar to:

```bash
git fetch
git merge
```

---

## Practical 5 - git remote -v

### Command Used

```bash
git remote -v
```

### Output

```text
origin  https://github.com/abishekbhandari54321/Git-GitHub-Learning.git (fetch)
origin  https://github.com/abishekbhandari54321/Git-GitHub-Learning.git (push)
```

### What I Learned

- This command shows the remote repository connected to my local repository.

---

## Practical 6 - git log

### Command Used

```bash
git log
```

### What Happened?

Git displayed the complete commit history.

### What I Learned

- Every commit has an ID.
- Every commit has an author.
- Every commit has a date and message.

---

## Practical 7 - git log --oneline

### Command Used

```bash
git log --oneline
```

### Output

(Write your own commit history here.)

### What I Learned

- This command shows the commit history in a short format.
