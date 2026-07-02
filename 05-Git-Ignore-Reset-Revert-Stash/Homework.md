# Homework - Day 5

## Task 1

Create:

```text
demo.txt
```

Add some text and stage it.

Then unstage it using:

```bash
git reset demo.txt
```

---

## Task 2

Create:

```text
notes.txt
```

Stage it and use:

```bash
git stash
git stash pop
```

Observe what happens.

---

## Task 3

Create:

```text
private.txt
```

Add it to:

```text
.gitignore
```

Verify using:

```bash
git status --ignored
```

---

## Task 4

Create:

```text
revert-practice.txt
```

Commit it and then revert the commit.

Commands:

```bash
git add .
git commit -m "Added revert practice file"
git revert --no-edit <commit-id>
```

---

## Task 5

Answer the following questions:

1. What is `.gitignore`?
2. What is the purpose of `git stash`?
3. What is the difference between `git reset` and `git revert`?
4. What does `git stash pop` do?
5. Why is `git revert` preferred in team projects?
