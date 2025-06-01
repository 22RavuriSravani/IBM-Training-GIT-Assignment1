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

---

## 🗂 Files in the Repository

- `main.html` - The main HTML structure  
- `index.css` - Styling using CSS  
- `assets/bootstrapfavicon.jpg` - Bootstrap favicon image  
- `BOOTSTRAP ASSIGNMENT 1.docx` - Assignment documentation  

---

