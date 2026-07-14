# Git Quick Notes

## Check Status
```bash
git status
```

## Add All Files
```bash
git add .
```

## Commit Changes
```bash
git commit -m "Your commit message"
```

Example:
```bash
git commit -m "Update project"
```

## Push Code
```bash
git push origin main
```

If using another branch:
```bash
git push origin branch-name
```

---

# Branch Commands

## List All Branches
```bash
git branch
```

## Create New Branch
```bash
git branch branch-name
```

Example:
```bash
git branch feature-login
```

## Create & Switch to New Branch
```bash
git checkout -b branch-name
```

Example:
```bash
git checkout -b feature-auth
```

## Switch Branch
```bash
git checkout branch-name
```

Example:
```bash
git checkout main
```

## Switch Back to Main
```bash
git checkout main
```

---

# Pull Latest Changes
```bash
git pull origin main
```

---

# Clone Repository
```bash
git clone <repository-url>
```

Example:
```bash
git clone https://github.com/username/project.git
```

---

# View Commit History
```bash
git log
```

Short version:
```bash
git log --oneline
```

---

# Delete Branch

Local:
```bash
git branch -d branch-name
```

Force delete:
```bash
git branch -D branch-name
```

Remote:
```bash
git push origin --delete branch-name
```

---

# Rename Branch

Current branch:
```bash
git branch -m new-branch-name
```

Another branch:
```bash
git branch -m old-branch-name new-branch-name
```

---

# Check Remote Repository
```bash
git remote -v
```

---

# First Time Push a New Branch
```bash
git push -u origin branch-name
```

---

# Daily Workflow

```bash
git status
git pull origin main
git add .
git commit -m "Describe your changes"
git push origin main
```

---

# Feature Branch Workflow

```bash
git checkout main
git pull origin main

git checkout -b feature-name

# Make changes

git add .
git commit -m "Add new feature"
git push -u origin feature-name
```