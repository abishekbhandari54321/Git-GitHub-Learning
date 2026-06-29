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
