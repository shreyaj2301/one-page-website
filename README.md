# 🌐 Website Hosting Guide

This README provides step-by-step instructions to host your website using **GitHub Pages** and **Firebase Hosting**. Whether you're working on a static site or a dynamic project, this guide will help you go live easily!

---

## 📁 Example Project Structure

my-website/ ├── index.html ├── style.css ├── script.js └── README.md

yaml
Copy
Edit

---

## ✅ Prerequisites

Before starting, ensure you have the following installed:

- Git
- GitHub account
- Node.js and npm (for Firebase)
- Firebase CLI (`npm install -g firebase-tools`)

---

## 🚀 Hosting on GitHub Pages

### 🔹 Step 1: Create a GitHub Repository

1. Go to [GitHub](https://github.com) and log in.
2. Click `+` → **New repository**.
3. Enter a name (e.g., `my-website`) and keep it **public**.
4. Click **Create repository**.

---

### 🔹 Step 2: Push Your Code to GitHub

Open your terminal or command prompt:

```bash
git init
git remote add origin https://github.com/YOUR-USERNAME/my-website.git
git add .
git commit -m "Initial commit"
git branch -M main
git push -u origin main
🔹 Step 3: Enable GitHub Pages
Go to your GitHub repository.

Click on Settings → Pages (on the sidebar).

Under Source, choose main branch and / (root) folder.

Click Save.

🔗 Your website will be live at:
https://your-username.github.io/my-website/

## Hosting on Firebase
🔹 Step 1: Set Up Firebase Project
Visit Firebase Console.

Click Add project, provide a project name, and follow the steps to create the project.

🔹 Step 2: Install Firebase CLI
bash
Copy
Edit
npm install -g firebase-tools
🔹 Step 3: Login to Firebase
bash
Copy
Edit
firebase login
🔹 Step 4: Initialize Firebase Hosting
In your project directory:

bash
Copy
Edit
firebase init
Select the following options:

✅ Hosting: Configure and deploy Firebase Hosting site

🔘 Use an existing project (choose the one you created)

📁 Set public directory (e.g., dist or just . for root)

❓ Configure as a single-page app? (Yes/No depending on your setup)

⚠️ Choose "No" when asked to overwrite index.html (unless you want to replace it)

🔹 Step 5: Deploy Your Website
bash
Copy
Edit
firebase deploy
🔗 Your website will be live at:
https://your-project-id.web.app/
