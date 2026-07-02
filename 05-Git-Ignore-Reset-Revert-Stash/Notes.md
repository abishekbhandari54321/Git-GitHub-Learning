# Git Ignore, Reset, Revert and Stash

## What is .gitignore?

`.gitignore` is a file that tells Git which files or folders should not be tracked.

Examples:

- Password files
- Secret keys
- Environment files
- Temporary files
- Build files

Example:

```text
secret.txt
```

Git will ignore this file.

---

## What is git reset?

`git reset` removes files from the staging area.

It does NOT delete the file.

Example:

```bash
git reset test.txt
```

The file remains on the computer but is no longer staged.

---

## What is git restore --staged?

It also removes a file from the staging area.

Example:

```bash
git restore --staged test.txt
```

This is the modern way of unstaging files.

---

## What is git stash?

`git stash` temporarily saves unfinished work.

It is useful when:

- You are working on a feature.
- Suddenly you need to switch branches.
- You don't want to commit incomplete work.

Example:

```bash
git stash
```

---

## What is git stash list?

Shows all saved stashes.

Example:

```bash
git stash list
```

---

## What is git stash pop?

Restores the latest stash.

Example:

```bash
git stash pop
```

---

## What is git revert?

`git revert` safely undoes a commit.

It creates a new commit that reverses the changes.

Example:

```bash
git revert b72ee08
```

---

## Why is git revert important?

Professional developers use `git revert` because:

- It keeps commit history.
- It is safe for team projects.
- It does not rewrite Git history.

---

# Difference between git reset and git revert

| Command    | Purpose                                         |
| ---------- | ----------------------------------------------- |
| git reset  | Removes staged files or moves HEAD              |
| git revert | Creates a new commit that undoes another commit |

---

# Summary

Today I learned:

- `.gitignore`
- `git reset`
- `git restore --staged`
- `git stash`
- `git stash list`
- `git stash pop`
- `git revert`
