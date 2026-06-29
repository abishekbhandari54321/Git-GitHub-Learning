# Homework

## 1. What is a branch?

A branch is an independent line of development in Git where developers can work without affecting the main project.

---

## 2. Why do we create branches?

We create branches to safely develop new features and fix bugs without breaking the main project.

---

## 3. What is the difference between git branch and git switch?

- `git branch` creates or shows branches.
- `git switch` changes from one branch to another.

---

## 4. What does git switch -c do?

It creates a new branch and switches to it immediately.

---

## 5. Why do we merge branches?

We merge branches to bring completed work into the main branch.

---

## 6. Why do we delete branches after merging?

Because they are no longer needed and keeping unnecessary branches makes the repository messy.

---

## 7. Explain a real company workflow using branches.

Developers create separate branches for their features and bug fixes.

Example:

main
├── feature-login
├── feature-payment
├── feature-cart
└── bug-fix-navbar

After completing their work, they merge the branch into `main` and then delete the branch.

---

## 7. What is a Fast-Forward Merge?

A Fast-Forward Merge is a merge in which Git simply moves the branch pointer to the latest commit without creating a new merge commit.

---

## 8. What is the difference between a local branch and a remote branch?

Local Branch:
Exists on your computer.

Remote Branch:
Exists on GitHub.

---

## 9. Why should we delete feature branches after merging?

Because they are no longer needed and deleting them keeps the repository clean and organized.

---

## 10. Write the complete feature branch workflow.

main
↓
Create feature branch
↓
Write code
↓
Commit changes
↓
Push branch
↓
Merge into main
↓
Push main
↓
Delete branch
