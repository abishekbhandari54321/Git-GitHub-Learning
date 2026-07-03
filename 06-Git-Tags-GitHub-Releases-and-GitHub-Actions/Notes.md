# Git Tags, GitHub Releases and GitHub Actions

# What is a Git Tag?

A tag is a label attached to a specific commit.

Tags are generally used to mark important versions of a project.

Examples:

- v1.0
- v2.0
- v3.1

---

# Why do we use Tags?

Suppose your project is completed and ready for users.

You can create:

v1.0 → First release

Later:

v1.1 → Bug fixes

v2.0 → Major update

Tags help us identify these versions easily.

---

# What is GitHub Release?

A GitHub Release is a published version of your project based on a tag.

It allows users to:

- Download source code
- See release notes
- Track project versions

---

# What is GitHub Actions?

GitHub Actions is an automation tool provided by GitHub.

It can automatically:

- Run tests
- Build projects
- Deploy applications
- Execute scripts

---

# What is a Workflow?

A workflow is a set of automated instructions written in YAML.

Example:

```yaml
name: Hello Workflow

on:
  push:
```

This means:

Whenever code is pushed, GitHub will run the workflow.

---

# What is YAML?

YAML stands for:

Yet Another Markup Language.

GitHub Actions workflows are written using YAML files.

Example:

```yaml
name: Hello Workflow
on: push
```

---

# Workflow Location

GitHub Actions only works if the workflow file is stored here:

.github/workflows/

Example:

Git-GitHub-Learning
│
└── .github
└── workflows
└── hello.yml

---

# Summary

Today I learned:

- Git Tags
- GitHub Releases
- GitHub Actions
- Workflow files
- YAML basics
- Creating my first automation workflow
