# Git Gut 🧠

A quick reference for commonly used Git commands.

---

## 1. 🚀 Clone a Repository
```bash
git clone <link>
```

---

## 2. 👤 See Git User Info
```bash
git config --global user.name
git config --global user.email
```

---

## 3. 📦 Basic Commands
```bash
git status                        # Check current status
git add .                         # Add all changes
git add <file/folder>            # Add specific file or folder
git commit -m "<message>"        # Commit with message
git push origin <branch>         # Push changes to a branch
```

---

## 4. 🌿 Branch Commands
```bash
git branch <name>                # Create a branch
git switch -c <name>             # Create and switch to new branch
git switch <name>                # Switch to existing branch
```

---

## 5. ❌ To Unclone (Stop Git Tracking)

### Method 1: Delete the folder completely.

### Method 2: Remove `.git` folder (Unclone without deleting files)
```bash
cd <foldername>
rm -rf .git
```
