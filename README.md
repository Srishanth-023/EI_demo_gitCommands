Learning git commands...

## 🧰 Basic Git Commands

Use the following Git commands to initialize, track, commit, branch, and merge your Git projects efficiently.

---

### 🔹 1. Initialize a Git Repository
```bash
# Initializes a new Git repository in your current project folder.
git init
```

---

### 🔹 2. Check Current Repository Status
```bash
# Displays the state of the working directory and staging area.
git status
```

---

### 🔹 3. Add Files to Staging Area
```bash
# Stages a specific file.
git add <filename>

# Stages all modified and new files in the current directory.
git add .
```

---

### 🔹 4. Commit Changes
```bash
# Saves staged changes to the local repository with a message.
git commit -m "Your commit message"
```

---

### 🔹 5. View Commit History
```bash
# Lists past commits with hashes, authors, and messages.
git log
```

---

### 🔹 6. Set Remote Repository
```bash
# Links your local repo to a remote one named 'origin'.
git remote add origin <repository-URL>
```

---

### 🔹 7. Push Changes to Remote
```bash
# Pushes local commits to the remote branch and sets upstream.
git push -u origin main  # or master or your branch name
```

---

### 🔹 8. Clone an Existing Repository
```bash
# Downloads a copy of the remote repository to your local machine.
git clone <repository-URL>
```

---

### 🔹 9. Create a New Branch
```bash
# Creates a new branch without switching to it.
git branch <branch-name>
```

---

### 🔹 10. Switch Between Branches
```bash
# Switches to the specified branch.
git checkout <branch-name>
```

---

### 🔹 11. Create and Switch to a Branch (Shortcut)
```bash
# Creates a new branch and switches to it immediately.
git checkout -b <branch-name>
```

---

### 🔹 12. List All Local Branches
```bash
# Shows all local branches. The current one is marked with '*'.
git branch
```

---

### 🔹 13. Merge a Branch into Current Branch
```bash
# Merges changes from the specified branch into the current one.
git merge <branch-name>

# Example:
# If you're on 'main' and want to bring in changes from 'feature':
# git merge feature
```

---

### 🔹 14. Merge a Branch into Current Branch
```bash
# Cloning a repo from open source
git clone <repo-link>

# It created a local copy of the global repo.
# It must done only if the project is not available in local.
```

---

