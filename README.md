# Computational Soil Science Lab — Website

A clean, professional research group website hosted for free via **GitHub Pages**.

## 📁 Files
```
├── index.html      ← Main website (all sections)
├── style.css       ← All styles
├── script.js       ← Navbar, scroll, animations
└── README.md       ← This file
```

---

## 🚀 Deploy to GitHub Pages (Step-by-Step)

### 1. Create the GitHub Repository

Go to [github.com/new](https://github.com/new) and create a repository named:

```
fajrintanah.github.io
```

> ⚠️ The name must match exactly: `yourusername.github.io`

Set it to **Public** and click **Create repository**.

---

### 2. Open this folder in VS Code terminal

```bash
cd path/to/css-website
```

---

### 3. Initialize Git and push

```bash
git init
git add .
git commit -m "Initial commit: CSS Lab website"
git branch -M main
git remote add origin https://github.com/fajrintanah/fajrintanah.github.io.git
git push -u origin main
```

---

### 4. Enable GitHub Pages

1. Go to your repo on GitHub
2. Click **Settings** → **Pages** (left sidebar)
3. Under **Source**, select `main` branch, folder `/ (root)`
4. Click **Save**

✅ Your site will be live at:  
👉 **https://fajrintanah.github.io**

(Takes ~1–2 minutes to go live the first time)

---

## ✏️ How to Customize

### Change your name/email
Open `index.html` and search for:
- `Fajrin Tanah` → replace with your real name
- `csslab@university.ac.id` → your email
- `Department of Soil Science` → your department

### Add/edit publications
Find the `#publications` section in `index.html` and copy/edit the `.pub-item` blocks.

### Add team members
Find the `#team` section and copy a `.team-card` block for each person.

### Add your profile photo
Replace the `<div class="team-avatar pi">` with:
```html
<img src="images/your-photo.jpg" alt="Your Name" style="width:100%;height:140px;object-fit:cover;">
```

### Update the stats
Find `.stats-bar` in `index.html` and change the numbers.

---

## 🔄 Update the site anytime

```bash
git add .
git commit -m "Update: added new publication"
git push
```

Changes go live in ~30 seconds.

---

## 💡 Tips
- Use [Google Scholar](https://scholar.google.com) to keep your publications list updated
- Add a `favicon.ico` file to the root folder for a browser tab icon
- For a custom domain (e.g. `csslab.university.edu`), add a `CNAME` file with the domain name
