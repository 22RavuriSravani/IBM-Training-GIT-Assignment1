# IBM Training GIT Assignment 1

## 📂 Project Setup

This repository contains files related to a Bootstrap assignment, including HTML, CSS, and image assets.

---

## ✅ Git Commands Used

### 1. Initialize Git Repository

```bash
git init
```

### 2. Add and Commit Files

```bash
git add .
git commit -m "Initial commit - Added Bootstrap assignment files"
```

### 3. Connect to Remote and Push

```bash
git remote add origin https://github.com/22RavuriSravani/IBM-Training-GIT-Assignment1.git
git branch -M main
git push -u origin main
```

### 4. Pull (Check for Remote Updates)

```bash
git pull origin main
```

### 5. Add README.md

```bash
nano README.md    # or create README.md in your preferred editor
git add README.md
git commit -m "Added README.md"
git push
```

### 6. Rename HTML File

```bash
git mv index.html main.html
git commit -m "Renamed index.html to main.html"
git push
```

### 7. Move Image to Assets Folder

```bash
mkdir assets
git mv bootstrapfavicon.jpg assets/
git commit -m "Moved bootstrapfavicon.jpg to assets folder"
git push
```

### 8. Delete PDF File

```bash
git rm "BOOTSTRAP ASSIGNMENT 1.pdf"
git commit -m "Removed BOOTSTRAP ASSIGNMENT 1.pdf"
git push
```

### 9. Revert a Commit (Undo Changes)

```bash
git revert 4922ec7b19a8ce03f93331e41e55b064e95834bc
```

---

## 📋 Summary
1. git init — Initialize a new Git repository
2. git add, git commit — Stage changes and commit them to the repository
3. git mv, git rm — Move/rename files and remove/delete files
4. git push, git pull — Push commits to and pull updates from the remote repository
5. git branch -M — Rename the current branch (e.g., to main)
6. mkdir — Create a new directory/folder
7. nano — Create or edit files directly from the terminal
8. git revert — Create a new commit that undoes changes from a previous commit

---
## 🗂 Files in the Repository

- `main.html` - The main HTML structure  
- `index.css` - Styling using CSS  
- `assets/bootstrapfavicon.jpg` - Bootstrap favicon image  
- `BOOTSTRAP ASSIGNMENT 1.docx` - Assignment documentation  

---

