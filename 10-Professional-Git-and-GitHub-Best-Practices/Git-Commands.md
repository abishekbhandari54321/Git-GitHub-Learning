# Day 10 - Professional Git & GitHub Best Practices

## Create and Switch to a New Branch

```bash
git switch -c feature/day10-practice
```

Creates a new branch and switches to it.

---

## Check Current Branches

```bash
git branch
```

Shows all local branches.

---

## Check Repository Status

```bash
git status
```

Shows modified, staged, and untracked files.

---

## Stage All Changes

```bash
git add .
```

Stages all modified and new files.

---

## Create a Commit

```bash
git commit -m "docs: organize Day 9 and Day 10 learning materials"
```

Creates a new commit with a professional commit message.

---

## View Last 5 Commits

```bash
git log --oneline -5
```

Displays the latest 5 commits.

---

## View Commit History with Branch Names

```bash
git log --oneline --decorate
```

Shows commit history with branch names and tags.

---

## View Commit Graph

```bash
git log --oneline --graph --all
```

Displays the commit history in graph format.

---

## Professional Commit Prefixes

feat: New feature

fix: Bug fix

docs: Documentation

refactor: Code improvement

test: Tests

style: Formatting changes

chore: Maintenance work
