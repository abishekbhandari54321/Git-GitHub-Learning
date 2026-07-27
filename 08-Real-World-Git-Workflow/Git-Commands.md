# Day 8 - GitHub Collaboration and Project Management Commands

## 1. Clone a Repository

Clone a GitHub repository to your computer:

git clone https://github.com/username/repository-name.git

Example:

git clone https://github.com/octocat/Hello-World.git

This downloads the complete repository to your computer.

---

## 2. Check Repository Status

git status

Shows:

- Current branch
- Uncommitted changes
- Untracked files
- Staged files

---

## 3. Check Commit History

git log --oneline

Shows a short list of commits.

Show only the last 5 commits:

git log --oneline -5

---

# GitHub Issue Search Filters

These filters are used in the Issues search box on GitHub.

## Show Issues with a Specific Label

label:bug

Shows only issues with the `bug` label.

Example:

label:enhancement

---

## Show Open Issues

is:open

Shows only open issues.

---

## Show Closed Issues

is:closed

Shows only closed issues.

---

## Combine Filters

label:bug is:open

This shows open issues that have the `bug` label.

---

# Important Note

Most Day 8 features are used directly on GitHub.com.

Examples:

- Creating Issues
- Adding Labels
- Assigning Issues
- Creating Projects
- Creating Milestones
- Creating Discussions

These actions do not require a local Git command.
