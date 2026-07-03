# Advanced Git Commands

## What is git diff?

`git diff` shows the changes made in a file before committing.

Example:

Old:

Hello World

New:

Hello World
Learning git diff

---

## What is git restore?

`git restore` removes uncommitted changes and brings the file back to its last committed state.

---

## What is git mv?

`git mv` renames or moves a file.

Important:

The file must already be tracked by Git.

---

## What is git rm?

`git rm` deletes a file and stages the deletion.

The file is removed from GitHub only after:

1. Commit
2. Push

---

## What is git show?

`git show` displays:

- Commit ID
- Author
- Date
- Commit message
- Changes made in that commit

---

# Git Configuration

Git stores settings in three levels:

## 1. Local Configuration

Works only for one repository.

Command:

```bash
git config --local --list
```

---

## 2. Global Configuration

Works for your user account.

Command:

```bash
git config --global user.name
git config --global user.email
```

---

## 3. System Configuration

Works for all users on the computer.

Command:

```bash
git config --system --list
```

---

# Configuration Priority

Git uses settings in this order:

Local → Global → System

Highest priority:

Local

Lowest priority:

System

---

# My Configuration

Global Username:

Abishek

Global Email:

abishekbhandari54321@gmail.com

Local Configuration:

No username and email configured.

System Configuration:

No username and email configured.
