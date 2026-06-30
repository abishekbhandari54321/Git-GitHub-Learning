# Homework

## 1. What is a Merge Conflict?

A merge conflict happens when Git cannot automatically merge changes from two branches.

---

## 2. Why do merge conflicts happen?

Because two branches changed the same file differently.

---

## 3. What do these symbols mean?

```text
<<<<<<<
=======
>>>>>>>
```

They are conflict markers added by Git.

---

## 4. How do you resolve a merge conflict?

Edit the file, remove conflict markers, save it, then commit the changes.

---

## 5. What is a Merge Commit?

A commit created after combining two branches.

---

## 6. What is a Pull Request?

A request to merge changes from one branch into another.

---

## 7. Why do companies use Pull Requests?

To review code and improve code quality.

---

## 8. What is the real company workflow?

main
↓
Feature Branch
↓
Commit
↓
Push
↓
Pull Request
↓
Review
↓
Merge
↓
Delete Branch

---

## 9. What does git fetch --prune do?

It removes references to deleted remote branches.

---

## 10. What is the difference between a Fast-Forward Merge and a Merge Commit?

Fast-Forward Merge:
Git moves the branch pointer directly.

Merge Commit:
Git creates a new commit to combine branches.
