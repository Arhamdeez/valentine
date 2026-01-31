# Valentine's Day Website 💕

A cute, romantic Valentine's Day page with heart particles, a runaway "No" button, and a celebration screen.

## Push to GitHub

1. **Create a new repo on GitHub**
   - Go to [github.com/new](https://github.com/new)
   - Name it (e.g. `valentines-site`)
   - Don’t add a README, .gitignore, or license (we already have them)

2. **From your machine, in the project folder:**

   ```bash
   cd /Users/app/valentines-site
   git init
   git add .
   git commit -m "Initial commit: Valentine's Day site"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
   git push -u origin main
   ```

   Replace `YOUR_USERNAME` and `YOUR_REPO_NAME` with your GitHub username and repo name.

## Deploy on Vercel

1. **Sign in**
   - Go to [vercel.com](https://vercel.com) and sign in (GitHub is easiest).

2. **Import the repo**
   - Click **Add New…** → **Project**
   - Select your GitHub account and the `valentines-site` repo
   - Click **Import**

3. **Deploy**
   - **Framework Preset:** leave as “Other” (or “None”)
   - **Root Directory:** leave as `.` (repo root)
   - **Build Command:** leave empty
   - **Output Directory:** leave empty
   - Click **Deploy**

4. **Result**
   - Vercel will build and give you a URL like `https://valentines-site-xxx.vercel.app`
   - `index.html` is served at the root, so that URL is your live site.

## Optional: custom domain

In the Vercel project → **Settings** → **Domains**, add your domain and follow the DNS instructions.
