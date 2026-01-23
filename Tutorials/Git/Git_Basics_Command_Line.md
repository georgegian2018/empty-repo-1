# Tutorial: Git Basics Using the Command Line

## Objective
This tutorial describes the procedure for initializing a Git repository,
tracking files, and pushing changes to a remote repository.

## Prerequisites
- Git installed
- GitHub account
- Command-line access

## Procedure

### Step 1: Initialize a repository
```bash
git init
```

# Step 2: Track files
```bash
git add .
git commit -m "Initial commit"
```

# Step 3: Push to a remote repository

```bash
git branch -M main
git remote add origin <repository-url>
git push -u origin main
```

# Verification

Run:
```bash
git status
```

Expected result: working tree clean

**Common Issues**

- Authentication errors
- Incorrect branch name
- Missing remote URL

**References**

- Git Documentation
- GitHub Documentation


---

## 8️⃣ Templates (CRITICAL)

### `Templates/Tutorial_Template.md`

```md
# Tutorial: <Title>

## Objective

## Prerequisites

## Procedure
### Step 1
### Step 2

## Verification

## Common Issues

## References
