# Badhar Business Group - Web Deployment & GitHub Push Guide

This folder contains a fully responsive, offline-first web version of **Badhar Business Group (QuarrySync Pro)** ledger dashboard styled with the elegant, high-contrast **Immersive UI** design theme.

---

## 🚀 Quick Deployment to Vercel (1-Click)

You can deploy this beautiful dashboard to **Vercel** for free in under 60 seconds:

### Step 1: Download your files
1. Download the workspace files as a **ZIP** from Google AI Studio (via the project/settings menu on the top right).
2. Extract the ZIP. Locate the `web` folder which contains `index.html` and this `README.md`.

### Step 2: Push to GitHub
1. Create a new repository on your [GitHub Account](https://github.com/new).
2. Upload the contents of the `web` folder (specifically the `index.html` file) into that repository. You can drag and drop it into GitHub or use the terminal:
   ```bash
   git init
   git add index.html
   git commit -m "Deploy Badhar Business Group Web Ledger"
   git branch -M main
   git remote add origin YOUR_GITHUB_REPO_URL
   git push -u origin main
   ```

### Step 3: Connect to Vercel
1. Go to [Vercel](https://vercel.com/) and log in with your GitHub account.
2. Click **Add New** -> **Project**.
3. Import your newly created GitHub repository.
4. Click **Deploy**. Vercel will automatically host your `index.html` as a fast, production-ready static website!

---

## 🎨 Immersive UI Design Features

- **Deep Obsidian Theme**: Clean eye-safe slate backgrounds matched with dynamic lavender purples.
- **Offline-First Persistence**: Utilizes browser `localStorage` to save all machine inputs, rates, income logs, and operational expenses completely locally. Your data persists even after refreshing or losing internet access.
- **Dynamic Chart Trends**: Interactive bar charts (via Chart.js) visualizing daily earnings and outgoing costs.
- **Full Settings Suite**: Export transaction logs to CSV, download offline JSON backups, or restore past backups securely with 1-click.
