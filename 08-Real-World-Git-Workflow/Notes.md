# Day 8 - GitHub Collaboration and Project Management

## 1. Fork

A fork creates a personal copy of another user's repository under your own GitHub account.

Example:

Original Repository
↓
Fork
↓
Your GitHub Account

A fork is useful when:

- You do not have permission to directly modify a repository.
- You want to contribute to an open-source project.
- You want to experiment with another person's project.

---

## 2. Clone

`git clone` downloads a remote repository to your computer.

Command:

git clone <repository-url>

Example:

git clone https://github.com/octocat/Hello-World.git

After cloning:

GitHub Repository
↓
git clone
↓
Local Computer

---

# GitHub Issues

An Issue is used to track:

- Bugs
- Features
- Tasks
- Improvements
- Other work

Example:

Issue: Fix Login Page

An Issue can contain:

- Title
- Description
- Labels
- Assignees
- Milestones
- Relationships
- Projects

---

# Labels

Labels categorize issues.

Common labels:

- bug
- enhancement
- feature
- documentation

Examples:

bug
→ Something is not working.

enhancement
→ Improve an existing feature.

documentation
→ Documentation-related work.

Example:

Fix Login Page
Label: bug

---

# Assignees

An assignee is the person responsible for working on an issue.

Example:

Issue: Fix Login Page
Assignee: Abishek

This means Abishek is responsible for working on the issue.

---

# GitHub Projects

GitHub Projects helps organize and track work.

A Kanban board can contain columns such as:

To do → In Progress → Done

Meaning:

### To do

The task has not started.

### In Progress

The task is currently being worked on.

### Done

The task has been completed.

Example workflow:

To do
↓
In Progress
↓
Done

---

# GitHub Milestones

A milestone groups multiple issues under one larger goal.

Example:

Milestone: Version 1.0

├── Add Login Feature
└── Fix Homepage Button

Milestone progress:

0% → 50% → 100%

Example:

2 issues
2 issues closed
100% complete

A milestone can represent:

- A software version
- A release
- A project goal
- A development phase

---

# Issue Relationships

GitHub allows issues to be connected to each other.

## Add Parent

Used when an issue is a smaller task belonging to a larger issue.

Parent Issue
↓
Child Issue

---

## Blocked By

Used when an issue cannot be completed until another issue is completed.

Example:

Add Login Feature
↓
must be completed first
↓
Fix Login Page

From the Fix Login Page issue's point of view:

Fix Login Page
Blocked by: Add Login Feature

---

## Blocking

Used when the current issue prevents another issue from being completed.

Example:

Database Setup
↓
blocks
↓
Login Page

---

# GitHub Discussions

GitHub Discussions are used for:

- Questions
- Ideas
- Conversations
- Community discussions

Example:

Discussion:

What should I learn after Git and GitHub?

## Issue vs Discussion

Issue:

- Used for tasks and bugs.
- Needs action.
- Example: Fix Login Page.

Discussion:

- Used for questions and conversations.
- Starts a conversation.
- Example: What should I learn next?

---

# GitHub Issue Filters

GitHub allows issues to be searched and filtered.

## Show Issues with a Specific Label

label:bug

Shows issues with the `bug` label.

---

## Show Open Issues

is:open

Shows open issues.

---

## Show Closed Issues

is:closed

Shows closed issues.

---

## Combine Filters

label:bug is:open

Shows open issues with the `bug` label.

---

# Day 8 Summary

The main workflow learned:

Fork
↓
Clone
↓
Create Issues
↓
Add Labels
↓
Assign Issues
↓
Add Issues to Projects
↓
Create Milestones
↓
Track Progress
↓
Connect Related Issues
↓
Use Discussions for Questions

---

# Important Difference

Git is mainly used for:

- Version control
- Tracking code changes
- Branches
- Commits
- Merging

GitHub provides additional collaboration and project-management features such as:

- Issues
- Projects
- Milestones
- Labels
- Assignees
- Discussions

These features help development teams plan, organize, and manage software projects.
