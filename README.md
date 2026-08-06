# Bain GitHub Training — Hands-On Exercise

Welcome! This repository is your practice ground for the GitHub training session.

## 🎯 What You'll Do Today

By the end of this exercise you will have:

- ✅ **Cloned** this repository to your laptop
- ✅ **Created a branch** with your name
- ✅ **Edited a file** and committed your change
- ✅ **Pushed** your branch to GitHub
- ✅ **Opened a Pull Request** to merge your changes
- ✅ **Reviewed** a teammate's Pull Request

---

## 📁 Repository Structure

```
bain-github-training/
│
├── README.md              ← You are here
├── contributors.md        ← Add your name here during the exercise
├── strategy-brief.md      ← Sample project document (read-only today)
└── data/
    └── market-data.csv    ← Sample dataset (read-only today)
```

---

## 🚀 Exercise Instructions

### Step 1 — Clone this Repository

**GitHub Desktop:**
1. Open GitHub Desktop → File → Clone Repository
2. Paste: `https://github.com/ajayarn/Github-Training-For-Consultants.git`
3. Choose a folder on your laptop → Click **Clone**

**Command Line:**
```bash
git clone https://github.com/ajayarn/Github-Training-For-Consultants.git
cd Github-Training-For-Consultants
```

---

### Step 2 — Create Your Branch

Name your branch `yourname/intro` — for example `anna/intro`.

**GitHub Desktop:** Click "Current Branch" (top bar) → "New Branch" → type your branch name → Create

**Command Line:**
```bash
git checkout -b anna/intro
```

---

### Step 3 — Edit `contributors.md`

Open `contributors.md` in any text editor (Notepad, VS Code, etc.) and add a new line at the bottom:

```
- Your Name | Your Role | Your Office
```

Example:
```
- Anna Kim | Senior Associate | Seoul
```

Save the file.

---

### Step 4 — Commit Your Change

**GitHub Desktop:** Your changed file appears on the left panel → write a Summary message like `"Add Anna Kim to contributors"` → click **Commit to anna/intro**

**Command Line:**
```bash
git add contributors.md
git commit -m "Add Anna Kim to contributors"
```

---

### Step 5 — Push & Open a Pull Request

**GitHub Desktop:** Click the **"Push origin"** button in the top bar.

**Command Line:**
```bash
git push -u origin anna/intro
```

Then go to **github.com → this repository** → you'll see a yellow banner "Compare & pull request" → click it → add a title and description → click **Create pull request**.

---

### Step 6 — Review a Teammate's Pull Request

1. Go to the **Pull Requests** tab on github.com
2. Open a teammate's PR
3. Click **"Files changed"** to see what they edited
4. Click **"Review changes"** → write a comment → click **"Approve"** → **"Submit review"**

---

## ✅ Success Checklist

| Task | Done? |
|------|-------|
| Cloned the repository | ☐ |
| Created my branch | ☐ |
| Added my name to contributors.md | ☐ |
| Committed the change | ☐ |
| Pushed my branch | ☐ |
| Opened a Pull Request | ☐ |
| Reviewed a teammate's PR | ☐ |

---

## 💡 Quick Reference

| Command | What it does |
|---------|-------------|
| `git clone <url>` | Download a repo to your laptop |
| `git checkout -b name` | Create and switch to a new branch |
| `git add .` | Stage all changed files |
| `git commit -m "msg"` | Save a snapshot with a message |
| `git push -u origin HEAD` | Upload your branch to GitHub |
| `git pull` | Get the latest changes from GitHub |
| `git status` | See what files have changed |

---

*Bain & Company · GitHub Training · 2026*
