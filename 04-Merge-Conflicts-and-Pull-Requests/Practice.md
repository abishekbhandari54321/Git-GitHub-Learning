# Practical Exercises

## Practical 1 - Create feature-navbar Branch

```bash
git switch -c feature-navbar
```

Created a new branch for learning merge conflicts.

---

## Practical 2 - Create conflict-demo.txt

Created:

04-Merge-Conflicts-and-Pull-Requests/conflict-demo.txt

---

## Practical 3 - Create a Merge Conflict

Command:

```bash
git merge feature-navbar
```

Output:

```text
CONFLICT (add/add): Merge conflict in conflict-demo.txt
Automatic merge failed.
```

---

## Practical 4 - Resolve Merge Conflict

Edited:

```text
conflict-demo.txt
```

Final Content:

```text
Hello World
Hello from Feature Navbar Branch
```

Commands:

```bash
git add .
git commit -m "Resolved merge conflict in conflict-demo.txt"
git push
```

---

## Practical 5 - Create feature-footer Branch

```bash
git switch -c feature-footer
```

---

## Practical 6 - Create footer.txt

Created:

```text
footer.txt
```

Content:

```text
Footer feature created.
```

---

## Practical 7 - Create Pull Request on GitHub

Created Pull Request:

```text
Added footer feature
```

---

## Practical 8 - Merge Pull Request

Merged the Pull Request on GitHub successfully.

---

## Practical 9 - Delete Branches

Delete local branch:

```bash
git branch -d feature-footer
```

Delete remote branch:

Performed using GitHub.

---

## Practical 10 - Clean Remote References

```bash
git fetch --prune
```

Removed old remote branch references.
