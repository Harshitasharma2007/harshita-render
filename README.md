# Harshita Sharma — Portfolio Website

A bold, neon-styled personal portfolio website hosted on Render with manual CI/CD via GitHub Actions.

## 🗂️ File Structure

```
harshita-portfolio/
├── .github/
│   └── workflows/
│       └── deploy.yml       ← GitHub Actions manual deploy pipeline
├── index.html               ← Main portfolio page
├── (H).jpeg                 ← Your profile photo
├── AWS(H).png               ← Certificate image
├── CSS3(H).png              ← Certificate image
├── FAWD(H).png              ← Certificate image
├── HTML 5 (H).png           ← Certificate image
├── JS(H).png                ← Certificate image
└── README.md                ← This file
```

## 🚀 How to Deploy

### First Time Setup
1. Push this repo to GitHub
2. Create a **Static Site** on [Render](https://render.com), connect this repo
3. Set **Publish Directory** to `.`
4. Copy the **Deploy Hook URL** from Render → Settings
5. Add it as a GitHub Secret named `RENDER_DEPLOY_HOOK`

### Every Time You Want to Deploy
1. Go to GitHub → **Actions** tab
2. Click **"Deploy to Render"**
3. Click **"Run workflow"**
4. Type `YES` and confirm

## 🛠️ Tech Stack
- HTML, CSS, JavaScript
- Supabase (feedback form)
- Render (hosting)
- GitHub Actions (CI/CD)
