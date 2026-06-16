# AFMPA1 Conference Website

This is a professional, premium, and multi-page website designed for the **First National Conference on Advanced Functional Materials and Physics Applications (AFMPA1)**.

## Features
- **Responsive Design:** Optimized for desktops, tablets, and mobile devices.
- **Multi-page Structure:** Includes Home, About, Topics, Committees, Dates, Registration, Program, Venue, and Contact.
- **Modern Aesthetic:** Clean typography, structured layouts, and a sophisticated color palette.
- **Interactive Elements:** Mobile navigation menu and registration/contact form placeholders.

## Deployment Guide

### 1. Deployment to GitHub
GitHub Pages is an excellent free option for hosting static websites.

1.  **Create a Repository:** Go to GitHub and create a new public repository named `afmpa1-website`.
2.  **Upload Files:**
    -   You can use the GitHub web interface to upload all files in this directory.
    -   Alternatively, use Git commands:
        ```bash
        git init
        git add .
        git commit -m "Initial commit"
        git branch -M main
        git remote add origin https://github.com/YOUR_USERNAME/afmpa1-website.git
        git push -u origin main
        ```
3.  **Enable GitHub Pages:**
    -   Go to **Settings** > **Pages** in your repository.
    -   Under **Build and deployment**, set the source to "Deploy from a branch" and select the `main` branch.
    -   Your website will be live at `https://YOUR_USERNAME.github.io/afmpa1-website/`.

### 2. Deployment to Vercel
Vercel offers a premium hosting experience with automatic deployments from GitHub.

1.  **Sign Up/Login:** Go to [Vercel](https://vercel.com/) and connect your GitHub account.
2.  **Import Project:** Click **"Add New"** > **"Project"** and select your `afmpa1-website` repository.
3.  **Deploy:** Click **"Deploy"**. Vercel will automatically detect the static files and provide a production-ready URL (e.g., `afmpa1-website.vercel.app`).
4.  **Benefits:** Vercel provides faster loading times (CDN), automatic SSL (HTTPS), and instant previews for every change you push to GitHub.

## Project Structure
- `index.html`: Homepage
- `css/style.css`: Main stylesheet
- `js/main.js`: Mobile menu functionality
- `assets/images/`: Directory for conference-related images
- `*.html`: Other dedicated pages (About, Committees, etc.)
