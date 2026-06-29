# Git Branches

## What is a Branch?

A branch is an independent line of development in Git.

It allows developers to work on new features or fixes without affecting the main project.

---

## Why do we need branches?

Suppose our website is already working.

Now we want to add:

- Login System
- Payment System
- Shopping Cart

If we directly make changes in the main branch and something goes wrong, the entire project may break.

Therefore, developers create separate branches.

---

## Real Company Workflow

main
├── feature-login
├── feature-payment
├── feature-cart
└── bug-fix-navbar

Different developers work on different branches.

When the work is completed, the branch is merged into the main branch.

---

## What is git branch?

Shows all local branches.

The `*` symbol indicates the current branch.

Example:

```text
* main
  feature-login
```

---

## What is git branch -a?

Shows all local and remote branches.

Example:

```text
* main
  feature-login
  remotes/origin/main
```

---

## What is git switch?

Changes the current branch.

Example:

```bash
git switch feature-login
```

---

## What is git switch -c?

Creates a new branch and switches to it immediately.

Example:

```bash
git switch -c feature-payment
```

---

## What is git merge?

Combines changes from one branch into another branch.

Example:

```bash
git merge feature-login
```

---

## What is git branch -d?

Deletes a branch after it has been merged.

Example:

```bash
git branch -d feature-login
```

---

## What is git push -u origin <branch-name>?

Uploads a local branch to GitHub.

Example:

```bash
git push -u origin feature-payment
```

---

---

## What is a Fast-Forward Merge?

A Fast-Forward Merge happens when Git can simply move the main branch pointer forward to the latest commit without creating an extra merge commit.

Example:

Before Merge:

main
\
 feature-payment

After Merge:

main, feature-payment
|
Latest Commit

---

## Local Branch vs Remote Branch

Local Branch:

- Exists on your computer.
- Example: feature-payment

Remote Branch:

- Exists on GitHub.
- Example: origin/feature-payment

---

## Deleting Branches

After a branch has been merged into main, it is usually deleted because it is no longer needed.

Delete local branch:

```bash
git branch -d feature-payment
```

Delete remote branch:

```bash
git push origin --delete feature-payment
```

# Summary

Today I learned:

- What is a branch
- Why branches are used
- Creating branches
- Switching branches
- Creating and switching branches in one command
- Working in feature branches
- Merging branches
- Fast-Forward Merge
- Deleting local branches
- Deleting remote branches
- Pushing branches to GitHub
- Difference between local and remote branches
