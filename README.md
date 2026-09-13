# SE-Git-hw

This repository contains the work for Assignment 1 in CINS 5318 Software Engineering.

## Purpose

The project demonstrates the use of Git and GitHub for version control, branching,
pull requests, conflict resolution, documentation, and issue tracking.

## Programs

### Hello World

```bash
python3 hello.py
```

Expected output:

```text
Hello, World!
```

### Apple program

```bash
python3 apple.py
```

Expected output:

```text
I eat a red and green apple
```

## Git and GitHub workflow

1. The repository was created and cloned locally.
2. `hello.py` and this README were added in the initial commit.
3. `feature-1` was created for `apple.py` and pushed to GitHub.
4. A pull request was reviewed by a classmate and merged into `main`.
5. GitHub Issues were used to track documentation tasks.

## Merge conflict demonstration

Two branches, `conflict-red` and `conflict-green`, were created from the same
version of `main`. Each branch changed the same line in `apple.py` to a different
color. After `conflict-red` was merged, merging `conflict-green` caused Git to
report a content conflict in `apple.py`.

The conflict was resolved manually by removing Git's conflict markers and
combining both changes into this final statement:

```python
print("I eat a red and green apple")
```

The resolved file was staged, committed, tested, and pushed to `main`.
