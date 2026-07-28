# Day 9 - Homework

## Objective

Practice the complete GitHub collaboration workflow used by software developers and open-source contributors.

---

# Practical 1 - Fork a Repository

Fork a public GitHub repository to your GitHub account.

Example:

- octocat/Hello-World

Understand the difference between:

- Fork
- Clone

---

# Practical 2 - Clone Your Fork

Clone your fork to your local computer.

Example command:

```bash
git clone https://github.com/<your-username>/Hello-World.git
```

Verify that the repository has been cloned successfully.

---

# Practical 3 - Create a Feature Branch

Create a new feature branch.

Example:

```bash
git switch -c add-readme-message
```

Check the current branch using:

```bash
git branch
```

---

# Practical 4 - Modify a File

Open the README file.

Add a few new lines describing your learning.

Save the file.

---

# Practical 5 - View Changes

Check the repository status.

```bash
git status
```

View the changes.

```bash
git diff
```

Understand the meaning of:

- - Added lines
- - Deleted lines

---

# Practical 6 - Stage and Commit

Stage the modified file.

```bash
git add .
```

Commit the changes.

```bash
git commit -m "Updated README with learning message"
```

---

# Practical 7 - Push the Feature Branch

Push the branch to GitHub.

```bash
git push -u origin add-readme-message
```

Verify that the branch appears on GitHub.

---

# Practical 8 - Create a Pull Request

Create a Pull Request from your feature branch.

Learn the following parts of a Pull Request:

- Base Repository
- Base Branch
- Compare Branch
- Title
- Description
- Conversation
- Commits
- Files Changed
- Merge Information

---

# Practical 9 - Understand Open Source Contribution

Understand the complete contribution workflow.

Contributor Workflow:

Fork Repository

↓

Clone Repository

↓

Create Feature Branch

↓

Modify Files

↓

Commit Changes

↓

Push Branch

↓

Create Pull Request

↓

Repository Maintainer Reviews

↓

Merge Pull Request

---

# Practical 10 - Understand Repository Permissions

Learn why contributors cannot directly merge changes into another person's repository.

Understand the responsibilities of:

- Contributor
- Repository Owner
- Maintainer

---

# Practical 11 - Practice Git Commands

Practice the following commands without looking at notes:

```bash
git status
git branch
git switch -c new-branch
git diff
git add .
git commit -m "Commit message"
git push -u origin new-branch
git remote -v
git log --oneline
git pull
```

---

# What I Learned

- Difference between Fork and Clone
- How developers contribute to open-source projects
- Why feature branches are important
- How to create and push a new branch
- How Pull Requests work
- Structure of a Pull Request
- Difference between contributor and maintainer
- Real-world GitHub collaboration workflow
