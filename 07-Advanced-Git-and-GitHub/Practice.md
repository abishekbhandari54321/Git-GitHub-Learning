# Practical Exercises

## Practical 1 - git diff

Created:

07-Advanced-Git-and-GitHub/diff-demo.txt

Content:

Hello World

Added:

Learning git diff

Command:

```bash
git diff
```

Output:

```diff
-Hello World
+Hello World
+Learning git diff
```

What I Learned:

`git diff` shows the changes before committing.

---

## Practical 2 - git restore

Command:

```bash
git restore 07-Advanced-Git-and-GitHub/diff-demo.txt
```

What Happened:

The file returned to:

Hello World

What I Learned:

`git restore` removes uncommitted changes.

---

## Practical 3 - git mv

Commands:

```bash
git mv 07-Advanced-Git-and-GitHub/old-name.txt 07-Advanced-Git-and-GitHub/new-name.txt
```

Output:

```text
renamed:
07-Advanced-Git-and-GitHub/old-name.txt ->
07-Advanced-Git-and-GitHub/new-name.txt
```

What I Learned:

`git mv` works only with tracked files.

---

## Practical 4 - git rm

Commands:

```bash
git rm 07-Advanced-Git-and-GitHub/delete-me.txt
git commit -m "Deleted file using git rm"
git push
```

What I Learned:

`git rm` deletes a file and stages the deletion.

---

## Practical 5 - git show

Command:

```bash
git show
```

Output:

```text
commit 923e6cd...
Author: Abishek
Date: Fri Jul 3 12:16:47 2026 +0530

Deleted file using git rm
```

What I Learned:

`git show` shows detailed information about a commit.

---

## Practical 6 - git config

Commands:

```bash
git config --global user.name
git config --global user.email
git config --system --list
git config --local --list
git config --list
```

Outputs:

```text
Abishek
abishekbhandari54321@gmail.com
```

What I Learned:

Git configuration has three levels:

- Local
- Global
- System
