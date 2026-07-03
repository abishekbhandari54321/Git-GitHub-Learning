# Git Commands - Advanced Git

## Show changes in files

```bash
git diff
```

Shows the difference between the last committed version and the current changes.

---

## Restore a file

```bash
git restore <file-name>
```

Example:

```bash
git restore 07-Advanced-Git-and-GitHub/diff-demo.txt
```

Restores the file to its last committed state.

---

## Rename a file

```bash
git mv <old-file-name> <new-file-name>
```

Example:

```bash
git mv 07-Advanced-Git-and-GitHub/old-name.txt 07-Advanced-Git-and-GitHub/new-name.txt
```

---

## Delete a file

```bash
git rm <file-name>
```

Example:

```bash
git rm 07-Advanced-Git-and-GitHub/delete-me.txt
```

---

## Show commit details

```bash
git show
```

Shows details of the latest commit.

```bash
git show <commit-id>
```

Example:

```bash
git show 445736f
```

---

## Show all Git configurations

```bash
git config --list
```

---

## Show global username

```bash
git config --global user.name
```

---

## Show global email

```bash
git config --global user.email
```

---

## Show system configuration

```bash
git config --system --list
```

---

## Show local configuration

```bash
git config --local --list
```
