# Merge Conflicts and Pull Requests

## What is a Merge Conflict?

A merge conflict occurs when Git cannot automatically merge changes because two branches modified the same file differently.

---

## Why do Merge Conflicts happen?

- Two developers change the same file.
- Two developers change the same lines of code.
- Git cannot decide which version should be kept.

---

## Conflict Markers

Git adds special markers:

```text
<<<<<<< HEAD
Content from current branch
=======
Content from another branch
>>>>>>> feature-navbar
```

- HEAD → Current branch.
- ======= → Separator.
- feature-navbar → Incoming branch.

---

## How to Resolve a Merge Conflict?

1. Open the conflicted file.
2. Decide which changes to keep.
3. Remove conflict markers.
4. Save the file.
5. Run:

```bash
git add .
git commit -m "Resolved merge conflict"
```

---

## What is a Merge Commit?

A merge commit is created when Git combines two branches after a conflict or a non-fast-forward merge.

---

## What is a Pull Request (PR)?

A Pull Request is a request to merge changes from one branch into another branch.

It allows other developers to review the code before merging.

---

## Why do companies use Pull Requests?

- Code Review
- Team Collaboration
- Better Code Quality
- Fewer Bugs
- Learning from other developers

---

## Real Company Workflow

main
↓
Create feature branch
↓
Write code
↓
Commit
↓
Push branch
↓
Create Pull Request
↓
Code Review
↓
Approve
↓
Merge
↓
Delete branch

---

## What is git fetch --prune?

It removes references to remote branches that no longer exist on GitHub.

Example:

```bash
git fetch --prune
```

---

# Summary

Today I learned:

- Merge Conflicts
- Conflict Markers
- Resolving Merge Conflicts
- Merge Commits
- Pull Requests
- GitHub Workflow
- Cleaning old remote references
