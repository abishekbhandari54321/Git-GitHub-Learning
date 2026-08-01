# Day 9 - Practice

## Practical 1 - Clone a Repository

Clone a public GitHub repository.

```bash
git clone https://github.com/octocat/Hello-World.git
```

Verify the repository.

```bash
git status
```

---

## Practical 2 - Check Current Branch

View the current branch.

```bash
git branch
```

Output:

```
* master
```

---

## Practical 3 - View Remote Repository

Check the connected remote repository.

```bash
git remote -v
```

Example Output:

```
origin  https://github.com/abishekbhandari54321/Hello-World.git (fetch)
origin  https://github.com/abishekbhandari54321/Hello-World.git (push)
```

---

## Practical 4 - Create a Feature Branch

Create and switch to a new branch.

```bash
git switch -c add-readme-message
```

Verify:

```bash
git branch
```

Output:

```
* add-readme-message
  master
```

---

## Practical 5 - Modify README

Open the README file.

Add the following text:

```
This change was made while learning Git branching and pull requests.
```

Save the file.

---

## Practical 6 - Check Repository Status

```bash
git status
```

Expected:

```
Changes not staged for commit
modified: README
```

---

## Practical 7 - View Changes

```bash
git diff
```

Observe:

- Lines beginning with "+" are added.
- Lines beginning with "-" are deleted.

---

## Practical 8 - Stage Changes

```bash
git add README
```

or

```bash
git add .
```

Verify:

```bash
git status
```

Expected:

```
Changes to be committed
```

---

## Practical 9 - Commit Changes

```bash
git commit -m "Updated README with learning message"
```

Verify:

```bash
git log --oneline -3
```

---

## Practical 10 - Push Feature Branch

```bash
git push -u origin add-readme-message
```

Observe that GitHub creates a new remote branch.

---

## Practical 11 - Create Pull Request

On GitHub:

1. Open your fork.
2. Click **Compare & pull request**.
3. Add a title.
4. Add a description.
5. Click **Create pull request**.

Observe the Pull Request page.

---

## Practical 12 - Understand Pull Request

Identify the following sections:

- Base Repository
- Base Branch
- Compare Branch
- Conversation
- Commits
- Files Changed
- Merge Information

Understand the purpose of each section.

---

## Practical 13 - Practice Another Feature Branch

Create another branch.

```bash
git switch -c add-login
```

Modify the README file again.

Stage the changes.

```bash
git add .
```

Commit:

```bash
git commit -m "Updates on README file"
```

Push:

```bash
git push -u origin add-login
```

Create another Pull Request.

---

## Practical 14 - Observe Repository Permissions

Notice that:

- You can create branches.
- You can commit changes.
- You can push branches.
- You can create Pull Requests.

However, you **cannot merge** a Pull Request into the original repository because you are not the owner or maintainer.

---

# Commands Practiced Today

```bash
git clone <repository-url>

git status

git branch

git remote -v

git switch -c <branch-name>

git diff

git add .

git add README

git commit -m "Commit message"

git push -u origin <branch-name>

git log --oneline -3
```

---

# Skills Practiced

✅ Cloned a repository

✅ Learned the difference between Fork and Clone

✅ Created feature branches

✅ Modified project files

✅ Viewed changes using git diff

✅ Staged files

✅ Created commits

✅ Pushed feature branches

✅ Created Pull Requests

✅ Understood GitHub collaboration workflow

✅ Learned contributor and maintainer roles

✅ Practiced real open-source contribution workflow
