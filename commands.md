# 🚀 Git Cheat Sheet: Master Git Commands & Concepts  

Welcome to the ultimate Git guide! Whether you're a beginner or seasoned developer, this file will help you understand Git commands with clarity and precision. 🌟  

---

## 🏁 Getting Started  

### 🔹 Initialize a Repository  
- **`git init`**  
  Initialize a new Git repository in your current directory. This creates a `.git` folder for tracking version history.  

---

## 📁 Managing Files  

### ➕ Adding Files  
- **`git add <filename>`**  
  Stage a specific file for the next commit.  
  Example: `git add nibba.txt`  

- **`git add .`**  
  Stage **all changes** (new, modified, or deleted) in your working directory.  

### ❌ Removing Files  
- **`git rm <filename>`**  
  Remove a file from your working directory and stage the deletion for the next commit.  

---

## 📊 Viewing Status  

- **`git status`**  
  Check the current state of your working directory and staging area. It shows:  
  - Untracked files  
  - Modified files  
  - Staged files  

---

## 💾 Committing Changes  

- **`git commit -m "<message>"`**  
  Record the staged changes with a brief commit message.  
  Example: `git commit -m "Added new features"`  

- **`git commit`**  
  Opens an editor for writing a detailed commit message.  

---

## ⚙️ Configuring Git  

### 🌐 Set Up User Information  
- **`git config --global user.name "<name>"`**  
  Set your global Git username.  

- **`git config --global user.email "<email>"`**  
  Set your global Git email address.  

---

## 🌿 Branching & Merging  

### 📂 Managing Branches  
- **`git branch`**  
  List all branches. The current branch is marked with `*`.  

- **`git branch <branch-name>`**  
  Create a new branch.  

- **`git switch <branch-name>`**  
  Switch to another branch.  

- **`git checkout -b <branch-name>`**  
  Create and switch to a new branch simultaneously.  

### 🔗 Merging Branches  
- **`git merge <branch-name>`**  
  Merge the specified branch into the current branch.  

---

## 🔄 Undoing Changes  

### 🕒 Restore Changes  
- **`git restore <filename>`**  
  Discard changes in the working directory for a specific file.  

- **`git restore --staged <filename>`**  
  Unstage a file that was added to the staging area.  

---

## 🔍 Viewing Logs  

- **`git log`**  
  Display the commit history in detail.  

- **`git log --oneline`**  
  Show a simplified, single-line view of the commit history.  

---

## 🛠️ Advanced Concepts  

### 🛑 Staging Area  
The **staging area** is a buffer between the working directory and the repository. It helps you control what gets committed.  

### 🌿 Branching  
Branches allow you to work on new features or bug fixes in isolation without affecting the main codebase.  

### 📡 Remote Repositories  
Collaborate with others by pushing and pulling changes to/from a **remote repository** (e.g., GitHub, GitLab).  

- **`git push`**  
  Upload changes from your local repository to the remote.  

- **`git pull`**  
  Fetch and integrate changes from the remote repository.  

### 🏷️ Tags  
Tags mark specific points in history, such as a release version.  

- **`git tag <tagname>`**  
  Create a tag for the current commit.  

---

## ✨ Pro Tips  

1. **Ignore Unnecessary Files:**  
   Use a `.gitignore` file to exclude files or directories from being tracked by Git.  

2. **Commit Often, Commit Smart:**  
   Commit small, logical chunks of work to make your history meaningful.  

3. **Stay Synced:**  
   Regularly pull changes from the remote repository to avoid conflicts.  

4. **Explore Aliases:**  
   Save time with custom aliases, e.g.,  
   ```bash
   git config --global alias.st status
   git config --global alias.co checkout
   git config --global alias.br branch
