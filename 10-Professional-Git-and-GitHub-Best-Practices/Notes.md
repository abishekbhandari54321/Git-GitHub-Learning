# Day 10 - Professional Git & GitHub Best Practices

## Professional Branch Naming

Companies use meaningful branch names instead of random names.

Examples:

feature/login

feature/payment

bugfix/navbar

docs/update-readme

hotfix/payment-error

refactor/authentication

---

## Professional Commit Messages

Avoid messages like:

- update
- fix
- changes
- done

Use meaningful messages instead.

Examples:

docs: update README

feat: add login page

fix: resolve payment bug

refactor: simplify authentication module

---

## Git History

Useful commands:

git log

git log --oneline

git log --oneline --decorate

git log --oneline --graph --all

These commands help developers understand the project history.

---

## HEAD

HEAD points to the current commit you are working on.

Whenever a new commit is created, HEAD automatically moves to the latest commit.

---

## main vs origin/main

main

- Local main branch on your computer.

origin/main

- Main branch on GitHub (remote repository).

---

## Professional Git Workflow

Professional workflow:

Pull latest changes

↓

Create Feature Branch

↓

Write Code

↓

Commit

↓

Push

↓

Create Pull Request

↓

Code Review

↓

Approval

↓

Merge into main

↓

Delete feature branch

---

## Code Review

Code review improves code quality.

A reviewer may suggest improvements before approving the Pull Request.

Developers should update the same feature branch and push the changes.

The existing Pull Request updates automatically.

---

## Branch Protection Rules

Branch protection helps protect important branches like main.

Common rules:

- Require Pull Request
- Require Code Review
- Require Status Checks
- Prevent Force Push
- Prevent Branch Deletion

---

## GitHub Wiki

GitHub Wiki is used for project documentation.

It is like a notebook for the project.

A Wiki may contain:

- Installation Guide
- Project Structure
- API Documentation
- User Guide
- FAQ

---

## GitHub Insights

GitHub Insights provides repository statistics.

Examples:

- Contributors
- Traffic
- Commits
- Code Frequency
- Dependency Graph
- Network
- Forks

---

## GitHub Pages

GitHub Pages allows developers to host websites directly from GitHub repositories.

It can be used for:

- Portfolio Website
- Documentation Website
- Project Showcase
- Personal Website
