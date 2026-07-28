# Day 9 - GitHub Collaboration Workflow

## 1. Clone a Repository

Clone a remote GitHub repository to your local computer.

```bash
git clone <repository-url>
```

Example:

```bash
git clone https://github.com/octocat/Hello-World.git
```

---

## 2. Check Repository Status

Display the current status of the repository.

```bash
git status
```

---

## 3. List Local Branches

Display all local branches.

```bash
git branch
```

---

## 4. Create and Switch to a New Branch

Create a new branch and immediately switch to it.

```bash
git switch -c <branch-name>
```

Example:

```bash
git switch -c add-readme-message
```

---

## 5. Switch to an Existing Branch

Switch to another existing branch.

```bash
git switch <branch-name>
```

Example:

```bash
git switch master
```

---

## 6. View Changes

Display the changes made in the working directory.

```bash
git diff
```

---

## 7. Stage Changes

Stage all modified files.

```bash
git add .
```

Stage a specific file.

```bash
git add README
```

---

## 8. Commit Changes

Save staged changes to the local repository.

```bash
git commit -m "Commit message"
```

Example:

```bash
git commit -m "Updated README with learning message"
```

---

## 9. Push a New Branch

Upload a new branch to GitHub and set the upstream branch.

```bash
git push -u origin <branch-name>
```

Example:

```bash
git push -u origin add-readme-message
```

---

## 10. Push Latest Changes

Upload the latest commits.

```bash
git push
```

---

## 11. Pull Latest Changes

Download the latest changes from the remote repository.

```bash
git pull
```

---

## 12. Delete a Local Branch

Delete a merged local branch.

```bash
git branch -d <branch-name>
```

Example:

```bash
git branch -d add-readme-message
```

---

## 13. Show Remote Repository

Display the configured remote repository.

```bash
git remote -v
```

---

## 14. View Commit History

Display recent commit history.

```bash
git log --oneline
```

Display the last three commits.

```bash
git log --oneline -3
```

---

# GitHub Features Learned

- Fork Repository
- Clone Repository
- Feature Branch Workflow
- Pull Request (PR)
- Upstream Repository
- Base Branch
- Compare Branch
- Contributor Workflow
- Repository Maintainer Workflow
- Open Source Contribution Process

---

# Professional GitHub Workflow

Repository
↓

Fork

↓

Clone

↓

Create Feature Branch

↓

Modify Files

↓

git diff

↓

git add

↓

git commit

↓

git push

↓

Create Pull Request

↓

Code Review

↓

Merge Pull Request

↓

Delete Feature Branch

↓

git pull
