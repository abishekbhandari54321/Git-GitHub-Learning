# Practical Exercises

---

## Practical 1 - Create a Tag

Command:

```bash
git tag v1.0
```

What I Learned:

Created my first Git tag.

---

## Practical 2 - View Tags

Command:

```bash
git tag
```

Output:

```text
v1.0
```

What I Learned:

This command shows all tags.

---

## Practical 3 - Push Tag to GitHub

Command:

```bash
git push origin v1.0
```

What I Learned:

Uploaded my tag to GitHub.

---

## Practical 4 - Create a GitHub Release

Steps:

1. Open GitHub.
2. Go to Releases.
3. Click Create Release.
4. Select tag v1.0.
5. Add title and description.
6. Publish release.

What I Learned:

GitHub Releases are based on tags.

---

## Practical 5 - Create GitHub Actions Folder

Created:

```text
.github
└── workflows
```

What I Learned:

GitHub Actions only works in this location.

---

## Practical 6 - Create Workflow File

Created:

```text
hello.yml
```

What I Learned:

Workflow files are written in YAML.

---

## Practical 7 - Create Hello Workflow

Code:

```yaml
name: Hello Workflow

on:
  push:

jobs:
  hello:
    runs-on: ubuntu-latest

    steps:
      - name: Print Hello
        run: echo "Hello from GitHub Actions!"
```

What I Learned:

GitHub automatically runs the workflow whenever I push code.

---

## Practical 8 - Fix Workflow Error

Error:

```text
No event triggers defined in `on`
```

Solution:

Corrected the YAML file.

What I Learned:

Even a small YAML mistake can break GitHub Actions.

---

## Practical 9 - Successful Workflow Run

Output:

```text
✅ hello
```

What I Learned:

I successfully created and executed my first GitHub Action workflow.
