# 🚀 Quick Guide: Using GitHub (Push & Pull only)

This guide is for beginners who only need to **upload changes** (push) and **download updates** (pull) with GitHub.  

---

## 🛠️ Requirements
- A [GitHub](https://github.com) account  
- Git installed on your computer → [Download here](https://git-scm.com/downloads)  
- Access to a GitHub repository (repo)  

---

## 📂 1. Clone the repository (first time only)
If you don’t already have the project on your computer:

```bash
git clone https://github.com/username/repository.git
cd repository
```

---

## ✍️ 2. Make changes
- Open the files in your editor (VS Code, etc.)  
- Save the changes  

---

## 💾 3. Save changes locally
First, **stage** the files:

```bash
git add .
```

Then, **commit** them with a short message:

```bash
git commit -m "Your message here"
```

Example:

```bash
git commit -m "Updated the homepage text"
```

---

## ☁️ 4. Upload changes to GitHub (push)
Send your changes to GitHub:

```bash
git push
```

If Git asks you for the branch, use `main`:

```bash
git push origin main
```

---

## 🔄 5. Get the latest version from GitHub (pull)
Before making new changes, update your local copy:

```bash
git pull
```

---

## ✅ Everyday workflow
1. Open the project folder  
2. Run `git pull` (to get the latest version)  
3. Make your changes  
4. Run `git add .`  
5. Run `git commit -m "message"`  
6. Run `git push`  

---

👉 That’s it! Just **pull before you start** and **push when you finish**.  
