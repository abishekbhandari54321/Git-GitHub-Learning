# Homework

## Task 1

Create a new tag:

```bash
git tag v2.0
```

---

## Task 2

Push the tag:

```bash
git push origin v2.0
```

---

## Task 3

Delete the local tag:

```bash
git tag -d v2.0
```

---

## Task 4

Create another workflow:

```yaml
name: Welcome Workflow

on:
  push:

jobs:
  welcome:
    runs-on: ubuntu-latest

    steps:
      - run: echo "Welcome to GitHub Actions!"
```

---

## Task 5

Research:

- What is CI/CD?
- What is Continuous Integration?
- What is Continuous Deployment?
- How do companies use GitHub Actions?
